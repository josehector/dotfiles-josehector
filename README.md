# dotfiles-plugin-base

## Getting started

This repository is a plugin to be used with [dotfiles project](https://github.com/autentia/dotfiles).

If you want to use this plugin you would need to have `dotfiles` installed in your computer.

## How to install the plugin

If you already have `dotfiles` installed you can add this plugin with the following command:

```shell
dotfiles install-plugin https://github.com/autentia/dotfiles-plugin-base.git
```

## How to update the plugin

Plugins are linked to git repository, so you can execute the following command to update it:

```shell
dotfiles update-plugin dotfiles-plugin-base
```

## File structure

```shell
├─ bin   # This folder contains custom binaries. 
├─ git   # This folder contains your git config.
├─ os    # This folder contains your specific config for your Operating System.
├─ ssh   # This folder contains specific functions related with ssh
├─ zsh   # This folder contains your config scripts for your terminal.
```

## Configuration included

### Brewfile
- Apps
  - Caffeine
  - AppCleaner
  - Google Chrome
  - Spotify
  - Docker

- Commands
  - git
  - vim
  - neovim
  - fzf
  - httpie
  - tree
  - jq

### Modified keys

Caps Lock key (⇪) -> (^) Control

### System defaults

- Finder
  - Disable press-and-hold for keys in favor of key repeat
  - Disable window animations and Get Info animations
  - Use list view in all Finder windows by default
  - Keep folders on top when sorting by name
  - Finder: show all filename extensions
  - Show icons for hard drives, servers, and removable media on the desktop
  - Avoid creating .DS_Store files on network or USB volumes
  - Show hidden files
  - Show the ~/Library folder
  - Show the /Volumes folder
- File Vault
  - Enable File Vault
- Screenshots
  - Set up directory to save screenshots inside ~/Downloads/screenshots
  - Save screenshots in PNG format
- Dock
  - Show in Dock just opened applications
  - Automatically hide and show the dock
  - Disable changes in the Dock
  - The size of the largest magnification: 50 (Min 16, Max 128)
  - Position of the Dock: bottom.
- Menu Extras
  - 5 is the number of seconds to delay after login before adding or removing menu extras
  - Things that shows in the menu extra:
    - AirPort
    - Bluetooth
    - CPU
    - Clock
    - Volume
  - Show battery percentage
- iCloud
  - Start iTunes from responding to the keyboard media keys
  - Save to disk (not to iCloud) by default
- Terminal
  - Only use UTF-8 in Terminal.app
- Spotify
  - Disabled auto-start

### Functions

- create_ssh_config
- repositories_status

## License

[Apache License](https://github.com/autentia/dotfiles-plugin-base/blob/main/LICENSE.txt)

