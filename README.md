# 🎮 Awesome Game Engine Recompilation & Emulation ⚡

<p align="center">
  <img src="./assets/banner.svg" alt="Awesome Game Engine Recompilation & Emulation" width="100%" />
</p>

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a>
  <a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Game-Engine-Recompilation-Emulation/stargazers"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Game-Engine-Recompilation-Emulation?style=social" alt="GitHub stars" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Game-Engine-Recompilation-Emulation/network/members"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Game-Engine-Recompilation-Emulation?style=social" alt="GitHub forks" /></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

---

## 🕹️ Top Game Engine Recompilation, Decompilation & Emulation Ecosystem

> A curated directory of battle-tested SaaS/commercial cloud streaming platforms and open-source game engine recompilers, decompilation frameworks, clean-room native engine reimplementations, cycle-accurate console emulators, and low-latency self-hosted remote play solutions.

* **Keywords / Topics**: `game-engine`, `recompilation`, `emulation`, `reverse-engineering`, `game-preservation`, `static-recompilation`, `decompilation`, `cloud-gaming`, `ghidra`, `n64recomp`, `xenonrecomp`, `rpcs3`, `dolphin-emu`.
* **Last Updated**: November 2026.

---

### 📑 Table of Contents
- [📊 Sector Overview & Market Dynamics](#-sector-overview--market-dynamics)
- [☁️ SaaS / Hosted Commercial Platforms](#️-saas--hosted-commercial-platforms)
- [💻 Open-Source GitHub Projects](#-open-source-github-projects)
- [🛠️ Key Architectural Patterns & Porting Methods](#️-key-architectural-patterns--porting-methods)
- [🤝 How to Contribute](#-how-to-contribute)
- [📈 Star History](#-star-history)
- [💖 Support & Sponsorship](#-support--sponsorship)
- [⚠️ License & Disclaimer](#️-license--disclaimer)

---

## 📊 Sector Overview & Market Dynamics

The global Cloud Gaming, Retro Preservation & Game Engine Porting sector is projected at **$10.2B–$13.5B+ in 2026**, registering an accelerating **20%–26% CAGR** spurred by high-speed fiber rollout, handheld PC hardware (Steam Deck, ROG Ally), and breakthrough developments in binary translation and static recompilation. 

The industry demonstrates a sharp **bifurcated market structure**:
1. **Commercial Cloud Streaming**: Highly concentrated (*winner-take-most*) dominated by hyperscalers possessing global bare-metal GPU footprints (Microsoft Xbox Cloud Gaming, Amazon Luna, NVIDIA GeForce NOW, and Valve Steam Remote Play).
2. **Recompilation & Engine Reimplementation**: 100% decentralized and open-source driven, wherein independent developers and preservationists use tools like `Ghidra`, `Splat`, `N64Recomp`, and `XenonRecomp` to extract game binaries and generate native PC executables running at uncapped frame rates (60–240 FPS+), ultrawide resolutions, and modern graphics APIs (DirectX 12, Vulkan, Metal).

---

## ☁️ SaaS / Hosted Commercial Platforms

*Sorted descending by estimated company valuation / annual revenue scale.*

| Platform | Company Valuation / Revenue Scale | Pricing (Starting Tier) | Free Tier / Trial Limits | Description |
| :--- | :--- | :--- | :--- | :--- |
| **[Amazon Luna](https://amazon.com)** | **~$2.0T+ Market Cap** (~$630B+ annual revenue; part of Amazon.com, Inc.) | **$9.99 / month** (Luna+ subscription) or included with Amazon Prime ($14.99/mo) | **7-Day Free Trial** for Luna+; perpetual free rotating game library access included with Amazon Prime membership | Enterprise cloud gaming service streaming PC and retro titles to Fire TV, PC, Mac, iOS, Android, and smart displays. |
| **[Xbox Cloud Gaming (Microsoft)](https://xbox.com)** | **~$3.0T+ Market Cap** (~$245B+ annual revenue; Microsoft Gaming) | **$9.99 / month** (Game Pass Core/Standard) or **$19.99 / month** (Game Pass Ultimate) | **100% Free Forever for Fortnite** (No subscription required; play free on web/mobile with free Microsoft account); 14-day promo trials for $1 | Cloud console gaming running custom Xbox Series X server blades streaming hundreds of native Xbox and retro backward-compatible titles. |
| **[GeForce NOW (NVIDIA)](https://nvidia.com)** | **~$3.0T+ Market Cap** (~$130B+ annual revenue; NVIDIA Corporation) | **$9.99 / month** (Performance tier) or **$19.99 / month** (Ultimate RTX 4080/5080 tier) | **Forever Free Basic Tier** (Ad-supported, **1-hour max session duration**, standard rig queue, renew sessions indefinitely) | Cloud GPU streaming service that links to user-owned game libraries on Steam, Epic Games Store, Xbox, Ubisoft, and GOG. |
| **[Steam Remote Play (Valve)](https://steampowered.com)** | **~$10B–$15B+ Est. Valuation** (~$10B+ annual Steam ecosystem revenue; privately held) | **$0 / Free Feature** (Standard 30% storefront cut on commercial game purchases) | **100% Free Forever** (Unlimited ultra-low-latency WAN/LAN streaming, 4K/120fps streaming, and Remote Play Together multiplayer) | Native remote streaming built into the Steam client allowing gamers to broadcast self-hosted PC games, ports, and emulators across devices. |
| **[Shadow PC (OVHcloud / Octave Klaba)](https://shadow.tech)** | **Backed by Octave Klaba / OVHcloud** (~€1B+ annual group revenue; Euronext: OVH) | **$19.99 / month** (Discovery plan) or **$32.99 – $49.99 / month** (Boost & Power GPU plans) | **No Perpetual Free Tier** (14-day statutory EU refund window; occasional first-month trial discounts down to $9.99) | High-performance dedicated Windows 11 cloud workstation and gaming PC streaming full desktop environments for emulators, recomp tools, and dev environments. |
| **[Boosteroid](https://boosteroid.com)** | **~$100M–$200M Est. Valuation** (~$20M–$40M est. ARR; leading independent cloud operator) | **€7.49 / month** (Annual billing at €89.89/year) or **€9.89 / month** (Standard monthly) | **Free Account / Speed Test** (Free connection latency and rig diagnostic test; active paid plan required to launch game sessions) | Independent cloud gaming platform offering browser-based and client-based 1080p/60fps and 4K/120fps access to top PC titles across Europe and North America. |
| **[Antstream Arcade](https://antstream.com)** | **~$30M–$50M Est. Valuation** (~$5M–$10M est. ARR; $20M+ venture funding) | **$3.99 / month** ($39.99/year annual plan) or **$99.99 one-time** (Lifetime access pass) | **Forever Free Ad-Supported Tier** (Unlimited access to 1,300+ retro arcade & console games supported by pre-roll video ads and daily challenge gems) | Fully licensed cloud retro gaming service streaming 1,300+ classic games from Commodore 64, Amiga, Arcade, Atari, Mega Drive, and PlayStation 1. |
| **[Blacknut](https://blacknut.com)** | **~$20M–$40M Est. Valuation** (~$5M–$10M est. ARR; European cloud provider) | **$14.99 / month** (or €14.99/month for 5 simultaneous profiles with parental controls) | **14-Day Free Trial** (Full catalog access for 14 days without charge; requires payment method registration; cancel anytime) | Family-oriented cloud gaming service providing unlimited access to 500+ curated PC, console, and casual titles on Smart TVs, mobiles, and PCs. |
| **[Utomik](https://utomik.com)** | **~$15M–$30M Est. Valuation** (~$5M+ est. ARR; hybrid cloud & fast-download) | **$8.99 / month** (Standard PC Plan) or **$11.99 / month** (PC + Cloud TV Multi-screen) | **14-Day Free Trial** (Full access to 1,400+ games across PC download and cloud streaming for 14 days before billing starts) | Hybrid "play-as-you-download" and cloud streaming platform offering 1,400+ indie, retro, and AAA titles with instant cloud jumping. |
| **[RetroArch Web Player (Libretro)](https://libretro.com)** | **Community Open-Source / Non-Profit** (Funded via OpenCollective & Patreon community) | **$0 / Free Open-Source** (Optional Patreon patronage for build infrastructure) | **100% Free Forever** (Unlimited browser WebAssembly emulation of 80+ console cores, cloud saves, and Netplay) | WebAssembly-compiled Libretro frontend running in standard web browsers, enabling cloud-based emulation without local installations. |

---

## 💻 Open-Source GitHub Projects

*Curated list of flagship open-source recompilation frameworks, decompilation suites, game engine reimplementations, and console emulators. Sorted descending by GitHub star count.*

| Repository & Stargazers Badge | Primary Focus / Category | License | Description |
| :--- | :--- | :--- | :--- |
| **[NationalSecurityAgency/ghidra](https://github.com/NationalSecurityAgency/ghidra)** <br> [![Stars](https://img.shields.io/github/stars/NationalSecurityAgency/ghidra?style=social&color=white)](https://github.com/NationalSecurityAgency/ghidra/stargazers) | SRE & Decompilation Toolchain | Apache-2.0 | World-class software reverse engineering (SRE) suite used worldwide for disassembling, decompiling, and analyzing game executables for recompilation. |
| **[SunshineStream/Sunshine](https://github.com/SunshineStream/Sunshine)** <br> [![Stars](https://img.shields.io/github/stars/SunshineStream/Sunshine?style=social&color=white)](https://github.com/SunshineStream/Sunshine/stargazers) | Self-Hosted Game Streaming Server | GPL-3.0 | Self-hosted low-latency game stream host for Moonlight with support for AMD, Intel, and NVIDIA GPUs, ultra-low input latency, and virtual gamepads. |
| **[RPCS3/rpcs3](https://github.com/RPCS3/rpcs3)** <br> [![Stars](https://img.shields.io/github/stars/RPCS3/rpcs3?style=social&color=white)](https://github.com/RPCS3/rpcs3/stargazers) | PS3 Console Emulator & Debugger | GPL-2.0 | Landmark open-source Sony PlayStation 3 emulator and debugger written in C++ for Windows, Linux, and macOS, supporting 4K/60fps+ rendering. |
| **[moonlight-stream/moonlight-qt](https://github.com/moonlight-stream/moonlight-qt)** <br> [![Stars](https://img.shields.io/github/stars/moonlight-stream/moonlight-qt?style=social&color=white)](https://github.com/moonlight-stream/moonlight-qt/stargazers) | GameStream / Sunshine Client | GPL-3.0 | Cross-platform GameStream client allowing users to play PC games, recompiled ports, and emulators remotely on Windows, macOS, Linux, Android, and iOS. |
| **[OpenRA/OpenRA](https://github.com/OpenRA/OpenRA)** <br> [![Stars](https://img.shields.io/github/stars/OpenRA/OpenRA?style=social&color=white)](https://github.com/OpenRA/OpenRA/stargazers) | Real-Time Strategy Engine | GPL-3.0 | Open-source RTS game engine for classic Westwood titles (Command & Conquer, Red Alert, Dune 2000) with modern multiplayer and high-res display support. |
| **[OpenRCT2/OpenRCT2](https://github.com/OpenRCT2/OpenRCT2)** <br> [![Stars](https://img.shields.io/github/stars/OpenRCT2/OpenRCT2?style=social&color=white)](https://github.com/OpenRCT2/OpenRCT2/stargazers) | Simulation Engine Reimplementation | GPL-3.0 | Open-source clean-room C++ re-implementation of RollerCoaster Tycoon 2 with online multiplayer, uncapped FPS, and custom plugin scripting. |
| **[PCSX2/pcsx2](https://github.com/PCSX2/pcsx2)** <br> [![Stars](https://img.shields.io/github/stars/PCSX2/pcsx2?style=social&color=white)](https://github.com/PCSX2/pcsx2/stargazers) | PS2 Console Emulator | GPL-3.0 | Premier open-source PlayStation 2 emulator for Windows, Linux, and macOS offering Vulkan/Direct3D rendering, internal resolution scaling up to 8K, and widescreen patches. |
| **[dolphin-emu/dolphin](https://github.com/dolphin-emu/dolphin)** <br> [![Stars](https://img.shields.io/github/stars/dolphin-emu/dolphin?style=social&color=white)](https://github.com/dolphin-emu/dolphin/stargazers) | GameCube & Wii Emulator | GPL-2.0+ | State-of-the-art Nintendo GameCube and Wii emulator featuring Netplay, 4K resolution scaling, texture replacement packs, and ultra-wide aspect ratios. |
| **[diasurgical/devilutionX](https://github.com/diasurgical/devilutionX)** <br> [![Stars](https://img.shields.io/github/stars/diasurgical/devilutionX?style=social&color=white)](https://github.com/diasurgical/devilutionX/stargazers) | Action RPG Engine Reimplementation | Source-Available | Reverse-engineered native source port of Diablo and Hellfire running natively on modern OSes, mobile, consoles, and WebAssembly with multiplayer support. |
| **[xenia-project/xenia](https://github.com/xenia-project/xenia)** <br> [![Stars](https://img.shields.io/github/stars/xenia-project/xenia?style=social&color=white)](https://github.com/xenia-project/xenia/stargazers) | Xbox 360 Console Emulator | BSD-3-Clause | Groundbreaking open-source Xbox 360 research emulator pioneering high-performance JIT compilation and Vulkan/D3D12 GPU emulation. |
| **[N64Recomp/N64Recomp](https://github.com/N64Recomp/N64Recomp)** <br> [![Stars](https://img.shields.io/github/stars/N64Recomp/N64Recomp?style=social&color=white)](https://github.com/N64Recomp/N64Recomp/stargazers) | Static Binary Recompiler Tool | MIT | Revolutionary offline static recompiler translating Nintendo 64 MIPS machine code binaries into native, optimized C/C++ source code. |
| **[Zelda64Recomp/Zelda64Recomp](https://github.com/Zelda64Recomp/Zelda64Recomp)** <br> [![Stars](https://img.shields.io/github/stars/Zelda64Recomp/Zelda64Recomp?style=social&color=white)](https://github.com/Zelda64Recomp/Zelda64Recomp/stargazers) | Native PC Recompiled Game Port | GPL-3.0 | Static recompilation project bringing The Legend of Zelda: Majora's Mask and Ocarina of Time to PC with 240+ FPS, ultrawide support, and gyroscope aiming. |
| **[OpenMW/openmw](https://github.com/OpenMW/openmw)** <br> [![Stars](https://img.shields.io/github/stars/OpenMW/openmw?style=social&color=white)](https://github.com/OpenMW/openmw/stargazers) | Open-World RPG Engine | GPL-3.0 | Clean-room modern C++ engine reimplementation of The Elder Scrolls III: Morrowind featuring enhanced physics, Lua modding, and VR support. |
| **[hedge-dev/XenonRecomp](https://github.com/hedge-dev/XenonRecomp)** <br> [![Stars](https://img.shields.io/github/stars/hedge-dev/XenonRecomp?style=social&color=white)](https://github.com/hedge-dev/XenonRecomp/stargazers) | Static Binary Recompiler for Xbox 360 | MIT | Groundbreaking static binary recompilation tool translating Xbox 360 PowerPC executables into native x86_64/ARM64 C++ code for PC ports. |
| **[HarbourMasters/Shipwright](https://github.com/HarbourMasters/Shipwright)** <br> [![Stars](https://img.shields.io/github/stars/HarbourMasters/Shipwright?style=social&color=white)](https://github.com/HarbourMasters/Shipwright/stargazers) | Native PC Port of Ocarina of Time | Open-Source | Clean-room native PC port of The Legend of Zelda: Ocarina of Time (Ship of Harkinian) utilizing matched decompilations for modern feature sets. |
| **[hedge-dev/UnleashedRecomp](https://github.com/hedge-dev/UnleashedRecomp)** <br> [![Stars](https://img.shields.io/github/stars/hedge-dev/UnleashedRecomp?style=social&color=white)](https://github.com/hedge-dev/UnleashedRecomp/stargazers) | Static Recompilation PC Port | GPL-3.0 | Unofficial native PC port of the Xbox 360 version of Sonic Unleashed powered by XenonRecomp static recompilation and D3D12 graphics. |
| **[XProger/OpenLara](https://github.com/XProger/OpenLara)** <br> [![Stars](https://img.shields.io/github/stars/XProger/OpenLara?style=social&color=white)](https://github.com/XProger/OpenLara/stargazers) | Classic Action Engine Reimplementation | BSD-2-Clause | Classic Tomb Raider engine reimplementation supporting modern shaders, VR, first-person camera, and WebGL running directly in browsers. |
| **[CorsixTH/CorsixTH](https://github.com/CorsixTH/CorsixTH)** <br> [![Stars](https://img.shields.io/github/stars/CorsixTH/CorsixTH?style=social&color=white)](https://github.com/CorsixTH/CorsixTH/stargazers) | Simulation Engine Reimplementation | MIT / Custom | Open-source modern clone and reimplementation of Theme Hospital with high-resolution UI, modern audio engines, and cross-platform builds. |
| **[decompme/decomp.me](https://github.com/decompme/decomp.me)** <br> [![Stars](https://img.shields.io/github/stars/decompme/decomp.me?style=social&color=white)](https://github.com/decompme/decomp.me/stargazers) | Collaborative Decompilation Platform | MIT | Community web platform allowing developers to collaborate in decompiling binary assembly functions into 100% matched C code across multiple compilers. |
| **[ethteck/splat](https://github.com/ethteck/splat)** <br> [![Stars](https://img.shields.io/github/stars/ethteck/splat?style=social&color=white)](https://github.com/ethteck/splat/stargazers) | Binary Splitting & Disassembly Tool | MIT | Essential binary splitting and asset extraction toolchain used across N64, PS1, and PS2 decompilation projects to generate buildable C trees. |
| **[XDanfr/RaymanOriginsRecomp](https://github.com/XDanfr/RaymanOriginsRecomp)** <br> [![Stars](https://img.shields.io/github/stars/XDanfr/RaymanOriginsRecomp?style=social&color=white)](https://github.com/XDanfr/RaymanOriginsRecomp/stargazers) | Static Recompilation Port | GPL-3.0 | Static recompilation project porting Rayman Origins (Xbox 360 binary) to modern systems using XenonRecomp without distributing copyrighted assets. |

---

## 🛠️ Key Architectural Patterns & Porting Methods

Modern game preservation and native porting typically follow one of three architectural patterns:

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                       MODERN PRESERVATION WORKFLOWS                         │
├─────────────────────────┬──────────────────────────┬────────────────────────┤
│ 1. Static Recompilation │ 2. Decompilation Match   │ 3. Clean-Room Engine   │
├─────────────────────────┼──────────────────────────┼────────────────────────┤
│ • Disassemble ROM/XEX   │ • Disassemble assembly   │ • Analyze game formats │
│ • Recompile PPC/MIPS    │ • Write matching C code  │ • Rewrite entire logic │
│   instructions to C++   │ • Byte-identical output  │ • Modern C++/C#/Rust   │
│ • Link native SDL/DX12  │ • Native engine wrapper  │ • Original assets only │
│   (e.g., N64Recomp,     │   (e.g., Shipwright,     │   (e.g., OpenMW,       │
│    XenonRecomp)         │    DevilutionX)          │    OpenRCT2, OpenRA)   │
└─────────────────────────┴──────────────────────────┴────────────────────────┘
```

---

## 🤝 How to Contribute

We welcome contributions from game engine developers, reverse engineers, and retro preservationists!

1. 🍴 **Fork** this repository.
2. 🌿 Create a branch for your entry: `git checkout -b add/cool-recomp-project`.
3. 📝 Add your entry to either the **SaaS / Commercial** or **Open-Source** table following the existing format.
4. 🌟 Ensure the star badge follows the format: `[![Stars](https://img.shields.io/github/stars/{owner}/{repo}?style=social&color=white)](https://github.com/{owner}/{repo}/stargazers)`.
5. 🚀 Submit a **Pull Request** with a concise description of why the project fits the list.

---

## 📈 Star History

[![Star History Chart](https://www.star-history.com/svg?repos=ishandutta2007/Awesome-Game-Engine-Recompilation-Emulation&type=date&legend=top-left)](https://www.star-history.com/#ishandutta2007/Awesome-Game-Engine-Recompilation-Emulation&type=date&legend=top-left)

---

## 💖 Support & Sponsorship

Thank you for visiting and supporting the **Awesome Game Engine Recompilation & Emulation** directory! 

Preserving gaming history through open-source tooling, static binary recompilers, clean-room engines, and high-performance emulation requires continuous research and community collaboration. If you found this list helpful, please consider:

* ⭐ **Starring** the repository on GitHub to boost discoverability.
* 🍴 **Forking** and contributing missing tools or documentation.
* 📢 **Sharing** with your fellow emulator developers, modders, and reverse engineers.
* ☕ **Buying a coffee or sponsoring** the maintainer via the [GitHub Sponsors Dashboard](https://github.com/sponsors/ishandutta2007).

---

## ⚠️ License & Disclaimer

* This repository is distributed under the [MIT License](LICENSE).
* All trademarks, product names, logos, and company names cited herein are the property of their respective owners. Their inclusion does not imply affiliation or endorsement.
* This repository does not host, provide, or distribute copyrighted ROMs, ISOs, or game assets. All recompilers and reimplementations require legally obtained user assets.
