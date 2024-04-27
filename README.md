# Config Setup

Configuration Management

## Quick setup

- `sudo pacman -S git ansible wl-clipboard`
- Setup up ssh authentication with github
- `ansible-pull -K -U https://github.com/jobin-nelson/config-setup --skip-tags hyprland`

## Install selected items

- `ansible-pull -K -U https://github.com/jobin-nelson/config-setup -t hyprland`
