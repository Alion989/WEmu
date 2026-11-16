<div align="center">

<img src="https://raw.githubusercontent.com/Alion989/WEmu/main/logo.png" width="150" alt="WEmu logo">

# WEmu

**Windows games & apps on Android, powered by Wine, Box64 and FEX.**

![Platform](https://img.shields.io/badge/platform-Android-3DDC84?logo=android&logoColor=white)
![Status](https://img.shields.io/badge/status-under%20development-orange)
![Package](https://img.shields.io/badge/package-ge.alion.wemu-0069FF)

</div>

---

## About

WEmu is a Windows runner for Android in the spirit of Winlator. It runs `.exe` files on your phone
through **Wine** with **Box64 / FEXCore / WowBox64** translation, and gives every game its own
container with its own settings.

> ⚠️ WEmu is **under development**. Expect rough edges, and please report what breaks.

## Features

| | |
|---|---|
| 🍷 **Wine runners** | Install several Wine builds (including ARM64EC Proton) and pick one per game |
| ⚙️ **Translation layers** | Box64, FEXCore and WowBox64 with editable profiles |
| 🎮 **Graphics** | DXVK, VKD3D-Proton and Turnip drivers, selectable per game |
| 📦 **Containers** | A separate Wine prefix for every game |
| 🧩 **Components** | Download Wine, drivers and translators in the app, or import your own |
| 🛠️ **Base Components** | One-tap install of Visual C++, Wine Mono, Wine Gecko and more into a game's container |
| 🕹️ **Input profiles** | Built-in gamepad profile, touch controls and custom profiles |
| 🔄 **Updates** | The app and the root filesystem update from inside WEmu |

## Getting started

1. Download the latest APK from the [Releases](https://github.com/Alion989/WEmu/releases) page and install it.
2. On first launch WEmu asks for the **rootfs**. Download it when offered, or import a `.wu` file.
3. Open **Components** and download a Wine build, a translator (Box64 / FEX) and graphics drivers.
4. Add a game, choose its `.exe`, and tune its settings.
5. Press play. 🎉

## Base Components

Open a game's settings and press **Base Components** to see the available packages.
Each one is **downloaded once**, then **installed per game**:

- **Installer** type: the Wine desktop opens and the installer runs by itself.
- **Extract** type: the files are unpacked straight into the container, with a progress bar and no desktop.


## Requirements

- Android 9 or newer, 64-bit (ARM64) device
- A GPU with Vulkan support (Adreno recommended)
- Several GB of free storage for the rootfs and containers


## Special Thanks

A huge thank you to everyone whose work made WEmu possible:

- **Bruno Sales ([brunodev85](https://github.com/brunodev85))**, creator of Winlator
- **[ptitSeb](https://github.com/ptitSeb)** and the Box64 contributors
- **The [FEX-Emu](https://github.com/FEX-Emu) team**
- **[WineHQ](https://www.winehq.org/)** and everyone who contributes to Wine
- **[Valve](https://github.com/ValveSoftware)** and the Proton team
- **[doitsujin](https://github.com/doitsujin)** (Philip Rebohle) and the DXVK contributors
- **[Hans-Kristian Arntzen](https://github.com/HansKristian-Work)** and the VKD3D-Proton team
- **The [Mesa](https://www.mesa3d.org/) community** and the Freedreno / Turnip developers
- **The Wine Mono and Wine Gecko maintainers**

And to every open-source developer whose work we build on. ❤️

## Disclaimer

WEmu is not affiliated with Microsoft, Wine or any game publisher. Use it only with software you own.

---

<div align="center">Made with ❤️ by <a href="https://github.com/Alion989">@Alien</a></div>
