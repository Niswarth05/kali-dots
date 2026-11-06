# Kali Dots

A minimal, clean and modern Hyprland desktop configuration built specifically for Kali Linux.

![status](https://img.shields.io/badge/status-initial%20development-orange)
![version](https://img.shields.io/badge/version-v0.1.0-blue)
![distro](https://img.shields.io/badge/distro-Kali%20Linux-557C94)

> **Heads up:** this project is in early development. Nothing is installable yet.

## Screenshots

Coming soon.

## Goals

- A lightweight, dark, minimal desktop with subtle animations
- Built for Kali Linux and installed with APT (no Arch tooling)
- Safe installation: back up existing configs, never remove GNOME
- Consistent spacing, fonts and colors across every app
- Fully documented and beginner friendly

## Components

| Component | Purpose |
|---|---|
| Hyprland | Window manager |
| Quickshell | Desktop shell and status bar |
| Rofi | Application launcher |
| Kitty | Terminal |
| Zsh | Shell |
| Starship | Shell prompt |
| GTK | Application appearance |

Waybar configs are kept as an optional alternative to Quickshell.

## Supported distribution

- Kali Linux Rolling (tested on 2026.3)

GNOME stays installed as a fallback session. If something breaks, log out and pick GNOME at the login screen.

## Project structure

```text
kali-dots/
├── configs/       App configs (hypr, quickshell, rofi, kitty, waybar, gtk, zsh)
├── scripts/       Desktop utilities and the installer
├── wallpapers/    Wallpaper collection
├── assets/        Images and other project assets
├── docs/          Documentation
└── backups/       Local config backups (not tracked by Git)
```

## Roadmap

- [ ] Phase 1: Project foundation
- [ ] Phase 2: Hyprland configuration
- [ ] Phase 3: Quickshell bar
- [ ] Phase 4: Rofi, Kitty, Zsh, Starship
- [ ] Phase 5: Appearance (wallpapers, GTK, icons, fonts, colors)
- [ ] Phase 6: Utilities (clipboard, screenshots, notifications, power menu)
- [ ] Phase 7: APT-based installer
- [ ] Phase 8: Testing and first release

## Installation

Not available yet. The installer will:

- use APT for all dependencies
- check that packages exist before installing
- back up your existing configs first
- create symlinks instead of overwriting files
- never touch your GNOME installation

## Inspiration

Design inspiration comes from the 43PR dotfiles. Kali Dots has its own configs, scripts and installer, written for Kali.

## Contributing

Contributions are not open yet while the foundation is being built. Check back after the first release.

## License

To be decided.
