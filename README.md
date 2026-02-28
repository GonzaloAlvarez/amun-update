# Amun Update

**amun-update** is a plugin for [amun](https://github.com/GonzaloAlvarez/amun) that updates and upgrades system packages across platforms.

---

## Usage

Run the update plugin through amun:

```bash
amun update
```

## Supported Platforms

| Platform | Package Manager | Operations |
|----------|----------------|------------|
| Debian/Ubuntu | apt | update, full-upgrade, autoremove, autoclean |
| macOS | Homebrew | update, upgrade, cask upgrade (greedy), cleanup |
| Arch Linux | pacman | -Syu (sync, refresh, upgrade), orphan removal |

## License

GNU GENERAL PUBLIC LICENSE
Version 3, 29 June 2007

Copyright (c) 2025 Gonzalo Alvarez
