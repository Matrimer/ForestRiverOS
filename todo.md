# For installation
- Create "greeter" user automatically
- Install default helix config
- /home/linuxbrew needs to be readable by user for brew to work

# Install luakit

# User settings
- List of config-files and a way of editing them

# Configurations
- Configure foot terminal (DMS provides a config with color scheme, but text size is tiny)
- ~/.config/environment.d
- Configure yazi file manager (Or possible nnn or MC)
- Configure zoxide

## Helix:
- Configure automatic compiling/running of things

# Ujust scripts
- nvidia/nvidia-optimus

# Add .local/bin to path


# Add configs/dotprofile for yash.
.config/yash/profile


# Add mime/xdg-open default applications

# Desktop Shell
- MPD client
- Launcher GUI + TUI apps
- Settings application
- Widgets: bluetooth, wifi, battery, notification, clipboard, mpd, workspaces, performance, audio, brightness, date+time, weather

# MPD
- Run MPD as user to make reading ~/Music/ easier
- enable systemd mpd.service (as user?)
- Create spotify backend


# Documentation
- Zenbrowser and Tridactyl
- Luakit
- Filemanagers: Yazi, nnn, MC
- editors: Helix, nano?
- Terminal emulator basics

# Bugs:
- For some reason there is /bin/yash and /usr/bin/yash, and only /bin/yash is in /etc/shells. pkexec fails using the former one
