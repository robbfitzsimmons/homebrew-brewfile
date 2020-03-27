# Robb's Brewfile.
# Contains commonly-used applications when provisioning a new Mac.

## Taps
tap "homebrew/cask" # GUI apps.
tap "homebrew/cask-drivers" # Software drivers (printers, etc.)
tap "homebrew/cask-fonts" # Open-source / free font files.
tap "homebrew/cask-versions"  # Alternate versions of Casks.
tap "homebrew/services" # Control services installed via Brew.
tap "osgeo/osgeo4mac" # Open source geospatial software.
tap "buo/cask-upgrade" # Upgrade brew casks via `brew cu`.
tap "yleisradio/terraforms" # Manage multiple `terraform` installations.

## DEVELOPMENT ENVIRONMENT
### Common development environment dependencies.

#### CLI / Shell
brew "coreutils" # Unix core utils for Mac.
brew "htop" # System monitoring.
brew "libgit2" # Git functions API.
brew "libffi" # C functions interface.
brew "openssl" # TLS and SSL cryptography library.
brew "openssh" # SSH secure server access.
brew "wget" # Retrieve content fron web servers.
brew "zsh" # Highly configurable terminal.
brew "zsh-completions" # Better auto-completions.
brew "zsh-syntax-highlighting" # Colorize Zsh.

#### DevOps
brew "awscli" # CLI access to Amazon Web Services.
brew "heroku" # CLI access to Heroku.
brew "packer" # Container -> image workflow tool.
brew "tfenv" # Terraform environment manager.

#### Go
brew "go" # Go language.

#### Java
brew "java" # Java language.

#### JavaScript
brew "jq" # JQuery CLI.
brew "node" # Node JS runtime.
brew "nvm" # Node version manager.
brew "v8" # Chrome JavaScript engine.
brew "yarn" # JavaScript package manager.

#### Python
brew "pipenv" # Python package manager for development.
brew "pipx" # Python package manager for CLI tools.
brew "pyenv" # Python version manager for local/global `python`.
brew "pyenv-virtualenv" # Virtual environment manager for pyenv.

#### Ruby
brew "rbenv" # Ruby version management.

#### R
brew "r" # R language.
cask "rstudio-preview" # IDE for the R language.

#### Geospatial
brew "cairo" # 2D graphics library.
brew "gdal" # Raster / vector geospatial data lib.
brew "gdk-pixbuf" # Image loading and manipulation.
brew "geos" # Geometry engine for simple features.
brew "netcdf" # Grid-oriented data formats.
brew "osmium-tool" # OpenStreetMap manipulation library.
brew "pango" # Text encoding
brew "proj" # Conversion between carto projections.
brew "protobuf" # Protocol buffers
cask "qgis" # GIS GUI.
brew "udunits" # Conversion of physical units measures.

#### Databases
brew "postgres" # SQL database
brew "postgis" # Postgres GIS support
brew "redis" # In-memory data store.

## VIRTUAL MACHINES
### Virtual machine management / reproducibility / portability.
cask "docker" # Container management.
brew "whalebrew" # Install Docker images with homebrew.


## DEVELOPER APPS
### Software for making software.
cask "dash" # Developer documentation.
cask "iterm2" # The best console emulator.
cask "keybase" # Easy PGP-key file sharing.
cask "sublime-text" # Text editor.
cask "sublime-merge" # Diff/merge tool.

## CONVENIENCE AND HELPERS
brew "speedtest-cli" # CLI for the Ookla network speed test.
brew "ffmpeg" # FFmpeg video encoder.

### QuickLook Plugins
#### Extends the functionality of QuickLook (spacebar preview) for Finder.
cask "qlcolorcode" # Code syntax highlighting.
cask "qlmarkdown" # Preview Markdown files.
cask "quicklook-csv" # Preview CSV data files.
cask "quicklook-json" # Preview JSON data files.

## PRODUCTIVITY APPS
### The most common Mac desktop apps - browser, file control, etc.
cask "1password" # Password and other secure doc storage.
cask "adobe-creative-cloud" # Adobe (Photoshop, Illustrator, etc.)
cask "aerial" # Those cool Apple TV flyover screensavers.
cask "alfred" # Alternative file search / hotkeys.
cask "banktivity" # Bank tracking app.
cask "basecamp" # Collaboration tool.
cask "bartender" # Rearrange / hide Mac menu bar apps.
cask "chatology" # Save and search iMessage.
cask "daisydisk" # Hard drive visualization.
cask "dropbox" # File storage and sync.
cask "droplr" # Screenshot management.
cask "evernote" # Note and document storage.
cask "google-chrome" # Browser, quasi-OS, eater-of-RAM.
cask "gpg-suite" # CLI and prefpane for PGP encryption.
cask "istat-menus" # System status bar.
cask "kaleidoscope" # File diffing tool.
cask "little-snitch" # Incoming/outgoing request filter.
cask "mactex" # LaTex text processor.
cask "mailplane" # Gmail GUI.
cask "parallels" # Virtual machine manager.
cask "postico" # PostgreSQL database client.
cask "quickbooks-online" # Accounting app.
cask "rectangle" # Keyboard-driven window manager.
cask "rescuetime" # Where did my day go?
cask "screens" # VNC GUI.
cask "shimo" # OpenVPN client.
cask "slack" # Group chat, when I must.
cask "spotify" # Streaming music client.
cask "superduper" # Bootable clones of your hard drive.
cask "transmit" # FTP and S3 client.

## MAC APP STORE APPS
### Install Apps previously purchased through the Mac App Store.
### Run "brew install mas" and "mas signin" before running this portion;
### the MAS setup can't be run for the first time within the Brewfile.
brew "mas" # Mac App Store formulas for brew.
mas "deliveries", id: 924726344 # Mail / delivery tracker.
mas "fantastical", id: 975937182 # Calendar and reminders manager.
mas "gemini", id: 1090488118 # Dedupes files and directories.
mas "tabletool", id: 1122008420 # Simple CSV editor.
mas "xcode", id: 497799835 # Command line compiler tools.
mas "xscope", id: 889428659	# Pixel sampler and hex code editor.
mas "TripIt", id: 1475712010 # Trip management tool.
mas "Tweetbot", id: 557168941 # Twitter client

## FONTS
cask "font-hasklig" # Source Sans fork with ligatures.
cask "font-montserrat" # Sans-serif header font.
cask "font-nixie-one" # Typewriter-style font (Linnaean logo).
