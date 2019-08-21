# Robb's Brewfile.
# Contains commonly-used applications when provisioning a new Mac.

## Taps
tap "homebrew/cask"                     # GUI apps.
tap "homebrew/cask-drivers"				# Software drivers (printers, etc.)
tap "homebrew/cask-fonts"               # Open-source / free font files.
tap "homebrew/cask-versions"            # Alternate versions of Casks.
tap "homebrew/services"					# Control services installed via Brew.
tap "osgeo/osgeo4mac"					# Open source geospatial software.
tap "heroku/brew"

## DEVELOPMENT ENVIRONMENT
### Common development environment dependencies.
### More complex / more-likely-to-be-problematic (e.g. R install) go in VMs.

#### CLI / Shell
brew "libgit2"							# Git functions API.
brew "libffi"							# C functions interface.
brew "openssl"	                        # TLS and SSL cryptography library.
brew "openssh"                          # SSH secure server access.
brew "wget"                             # Retrieve content fron web servers.
brew "zsh"		                        # Highly configurable terminal.
brew "zsh-completions"	                # Better auto-completions.
brew "zsh-syntax-highlighting"          # Colorize Zsh.

#### DevOps
brew "awscli"    		                # CLI access to Amazon Web Services.
brew "heroku"		                    # CLI access to Heroku.

#### JavaScript
brew "jq"								# JQuery CLI.
brew "node"		                        # Node JS runtime.
brew "nvm"		                        # Node version manager.
brew "v8"								# Chrome JavaScript engine.
brew "yarn"								# JavaScript package manager.

#### Python
brew "python2"                          # Python 2.x.
brew "python"                           # Python 3.x.
brew "pipenv"							# Python package manager.

#### Ruby
brew "rbenv"		                    # Ruby version management.

#### R
brew "r"                              	# R language.
cask "rstudio-preview"			        # IDE for the R language.

#### Geospatial
brew "cairo"                          	# 2D graphics library.
brew "gdal"								# Raster / vector geospatial data lib.
brew "gdk-pixbuf"						# Image loading and manipulation.
brew "geos"                           	# Geometry engine for simple features.
brew "netcdf"							# Grid-oriented data formats.
brew "osmium-tool"						# OpenStreetMap manipulation library.
brew "pango"							# Text encoding
brew "proj"             				# Conversion between carto projections.
brew "protobuf"							# Protocol buffers
brew "udunits"                        	# Conversion of physical units measures.

#### Databases
brew "postgres"							# SQL database
brew "redis"		                    # In-memory data store.
brew "unixodbc"							# Database drivers.

## VIRTUAL MACHINES
### Virtual machine management / reproducibility / portability.
cask "docker"                           # Container management.
brew "docker-machine-parallels"         # Docker containers in Parallels VMs.
brew "packer"                           # Container -> image workflow tool.

## DEVELOPER APPS
### Software for making software.
cask "dash"		                        # Developer documentation.
cask "iterm2" 	                        # The best console emulator.
cask "keybase"		                    # Easy PGP-key file sharing.
cask "sublime-text"                     # Text editor.
cask "sublime-merge"                    # Diff/merge tool.

## CONVENIENCE AND HELPERS
brew "speedtest-cli"                    # CLI for the Ookla network speed test.
brew "ffmpeg"							# FFmpeg video encoder.

### QuickLook Plugins
#### Extends the functionality of QuickLook (spacebar preview) for Finder.
cask "qlcolorcode"                      # Code syntax highlighting.
cask "qlmarkdown"                       # Preview Markdown files.
cask "quicklook-csv"                    # Preview CSV data files.
cask "quicklook-json"                   # Preview JSON data files.

## PRODUCTIVITY APPS
### The most common Mac desktop apps - browser, file control, etc.
cask "1password"		                # Password and other secure doc storage.
cask "adobe-creative-cloud"             # Adobe (Photoshop, Illustrator, etc.)
cask "alfred"     			            # Alternative file search / hotkeys.
cask "basecamp"                         # Collaboration tool.
cask "bartender" 	    	            # Rearrange / hide Mac menu bar apps.
cask "chatology"		                # Save and search iMessage.
cask "daisydisk"		                # Hard drive visualization.
cask "dropbox"			                # File storage and sync.
cask "evernote"                         # Note and document storage.
cask "google-chrome"		            # Browser, quasi-OS, eater-of-RAM.
cask "gpg-suite"                        # CLI and prefpane for PGP encryption.
cask "istat-menus"		                # System status bar.
cask "kaleidoscope"                     # File diffing tool.
cask "little-snitch"		            # Incoming/outgoing request filter.
cask "mactex"							# LaTex text processor.
# cask "parallels"                        # Virtual machine manager.
cask "postico"			                # PostgreSQL database client.
cask "shimo"                            # OpenVPN client.
cask "slack"							# Group chat, when I must.
cask "spotify"			                # Streaming music client.
cask "superduper"		                # Bootable clones of your hard drive.
cask "transmit"			                # FTP and S3 client.

## MAC APP STORE APPS
### Install Apps previously purchased through the Mac App Store.
### Run "brew install mas" and "mas signin" before running this portion;
### the MAS setup can't be run for the first time within the Brewfile.
brew "mas"                              # Mac App Store formulas for brew.
mas "deliveries",     id: 924726344 	# Mail / delivery tracker.
mas "divvy", 		  id: 413857545		# Tiling window manager.
mas "fantastical",    id: 975937182     # Calendar and reminders manager.
mas "gemini",         id: 1090488118	# Dedupes files and directories.
mas "tabletool",      id: 1122008420    # Simple CSV editor.
mas "tweetbot",       id: 557168941     # Twitter client.
mas "xscope",	      id: 889428659		# Pixel sampler and hex code editor.


## FONTS
cask "font-hasklig"                   	# Source Sans fork with ligatures.
cask "font-montserrat"                	# Sans-serif header font.
cask "font-nixie-one"                 	# Typewriter-style font (Linnaean logo).

## UNUSED (for now).
### Things that have been in this Brewfile previously, but aren't frequently used.
### (Commenting out in an attempt to skinny down my system; uncomment to bring back.)
## Brew:
# brew "go"                             # Go language.
# brew "automake"						# Makefiles.
# brew "carthage"                       # Manage Swift dependencies.
# brew "freetype"                       # Font rendering library.
# brew "youtube-dl"                     # YouTube downloader CLI.
# brew "locateme"                       # CLI to retrieve machine's location.

## Brew Cask:
# cask "hazel"			                # File system automation and cleaning.
# cask "paw"                            # HTTP(S) and REST client.
# cask "osxfuse"                        # Extend macOS file handling to S3.
# cask "gmvault"                        # CLI to archive / back up Gmail.
# cask "tad"                            # CSV file viewer.

## Mac App Store:
# mas "deliveries",     id: 924726344   # Package and shipment tracker.
# mas "paprika",        id: 1303222628  # Recipe manager.
# mas "ia-writer",      id: 775737590   # Plain text editor.
# mas "wifi-explorer",  id: 494803304   # Information on wireless networks.
