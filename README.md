# 🎮 Awesome Game Porting & Reverse Engineering 🛠️

<p align="center">
  <img src="./assets/banner.svg" alt="Awesome Game Porting and Reverse Engineering Banner" width="100%" />
</p>

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a>
  <a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Game-Porting-Reverse-Engineering/stargazers"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Game-Porting-Reverse-Engineering?style=flat-square&logo=github&color=gold" alt="GitHub_Stars" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Game-Porting-Reverse-Engineering/network/members"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Game-Porting-Reverse-Engineering?style=flat-square&logo=github&color=blue" alt="GitHub forks" /></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

---

## ⚡ Executive Summary & SEO Keywords

> **Keywords**: `game porting`, `reverse engineering`, `static recompilation`, `binary decompilation`, `Ghidra`, `Proton`, `DXVK`, `MoltenVK`, `Wine`, `game preservation`, `N64Recomp`, `Zelda64Recomp`, `console-to-pc ports`, `cloud gaming`, `emulation layer`, `Vulkan translation`.

A curated, production-grade index of software suites, frameworks, translation layers, and open-source engines powering **game porting**, **binary decompilation**, **static recompilation**, and **video game preservation**. Designed for systems software engineers, preservationists, emulator developers, and reverse engineers porting legacy console binaries (N64, PS2, Xbox, Wii, GameCube) to modern architectures (x86_64, ARM64, Apple Silicon Metal, and Linux SteamOS).

---

## 📑 Table of Contents

- [📊 Sector Overview & Market Dynamics](#-sector-overview--market-dynamics)
- [☁️ SaaS & Commercial Game Streaming / Porting Platforms](#️-saas--commercial-game-streaming--porting-platforms)
- [💻 Open-Source Reverse Engineering, Porting & Recompilation Projects](#-open-source-reverse-engineering-porting--recompilation-projects)
- [🌟 Star History](#-star-history)
- [🛠️ How to Contribute](#️-how-to-contribute)
- [💖 Support & Sponsorship](#-support--sponsorship)
- [⚠️ Disclaimer](#️-disclaimer)

---

## 📊 Sector Overview & Market Dynamics

The global Cloud Gaming, Game Preservation & Cross-Platform Porting Tools market is valued at approximately **$10.5B–$13.8B in 2026** (projected to surpass **$25B by 2030**, growing at a ~24% CAGR). The commercial cloud gaming and managed emulation sector is **moderately concentrated among market leaders** (such as NVIDIA GeForce NOW, Boosteroid, and Shadow PC) due to immense multi-region GPU infrastructure capital expenditure. Conversely, the surrounding binary decompilation, assembly matching, static recompilation, and graphics translation runtime ecosystem remains **highly fragmented and dominated by community-driven open-source projects**.

---

## ☁️ SaaS & Commercial Game Streaming / Porting Platforms

*Commercial cloud streaming, remote virtual workstations, and curated retro ecosystems sorted in descending order of company valuation / annual revenue scale.*

| 🏢 Platform | 📝 Description | 📈 Company Scale (Valuation / Revenue) | 💳 Starting Paid Tier | 🎁 Free Tier / Trial Limit |
| :--- | :--- | :--- | :--- | :--- |
| **[GeForce NOW (NVIDIA)](https://nvidia.com)** | Cloud RTX GPU game-streaming platform running PC libraries from Steam, Epic, Xbox, and GOG across Windows, macOS, Linux, browsers, and handhelds. | **Part of NVIDIA Corp.** (~$130B+ annual revenue; ~$3T+ market cap) | **$9.99 / month** ($49.99 / 6 months Performance) or **$19.99 / month** ($99.99 / 6 months Ultimate RTX 4080) | **Forever Free Basic Tier** (Ad-supported, **1-hour session limit** per session with standard queue access) |
| **[Shadow PC (OVHcloud / Octave Klaba)](https://shadow.tech)** | Dedicated cloud Windows 11 gaming and reverse-engineering workstation streamed at low latency to macOS, Linux, iOS, and Android. | **Backed by Octave Klaba / OVHcloud** (~€1B+ OVHcloud group revenue) | **$19.99 / month** (Shadow PC Lite/Discovery) or **$32.99 – $49.99 / month** (Boost / Power RTX GPU tiers) | **No Free Tier / 0-Day Trial** (Requires paid upfront subscription; access to test network ping and speed tool prior to purchase) |
| **[Boosteroid](https://boosteroid.com)** | Leading European independent cloud gaming platform streaming AAA and classic PC titles at up to 4K/120fps across Linux, macOS, browsers, and TVs. | **~$100M–$200M Est. Valuation** (~$20M–$40M est. ARR) | **€7.49 / month** (billed annually at €89.89/year) or **€12.89 / month** monthly for Ultra 4K | **No Free Tier / 0-Day Trial** (Free account includes in-browser latency and network speed diagnostic tool before purchasing) |
| **[Antstream Arcade](https://antstream.com)** | Official cloud retro-gaming platform streaming 1,300+ licensed arcade, Amiga, Commodore, SNES, and PlayStation classics with cloud saves. | **~$30M–$50M Est. Valuation** (~$5M–$10M est. ARR; $20M+ venture funding) | **$3.99 / month** ($39.99 / year billed annually) or **$99.99 one-time** Lifetime Pass | **Forever Free Tier** (Ad-supported gameplay with 1,300+ retro games, daily challenges, and tournaments supported by pre-roll ads) |
| **[Utomik](https://utomik.com)** | Subscription cloud and fast-chunked-download PC/retro gaming platform curating 1,400+ indie, classic, and family titles on PC and smart TVs. | **~$15M–$30M Est. Valuation** (~$5M+ est. ARR) | **$8.99 / month** (PC Only Plan) or **$11.99 / month** (Cloud + PC Multi-screen Plan) | **14-Day Free Trial** (Full unlimited access to 1,400+ games across PC/Cloud for 14 days, converts to paid plan unless cancelled) |
| **[LaunchBox / Big Box (Unbroken Software)](https://launchbox-app.com)** | Windows/Android retro-game launcher, metadata scraper, and 10-foot arcade cabinet frontend integrating emulators and native PC ports. | **~$5M–$15M Est. Scale** (Profitable independent retro software company) | **$30.00 / year** (1-year license with updates) or **$75.00 one-time** Forever Updates license for Big Box mode | **Forever Free Desktop Tier** (Unlimited game library management, emulation launching, metadata scraping, and community integrations) |
| **[Recalbox (Commercial Hardware / RGB Dual Ecosystem)](https://recalbox.com)** | Open-source retro-gaming OS paired with official Recalbox RGB Dual CRT hardware adapters, pre-flashed kits, and Patreon early builds. | **~$2M–$5M Est. Scale** (Commercial hardware sales & accessories) | **€39.00 – €89.00 one-time** (Hardware kits / RGB Dual CRT adapters; core OS is free) | **Forever Free OS** (Unlimited free downloadable bootable images for Raspberry Pi, PC, and handheld devices with 100+ emulators) |
| **[RetroArch (Libretro Cloud / Store Ecosystem)](https://retroarch.com)** | Cross-platform frontend for Libretro cores running hundreds of open-source emulators and native game-engine ports with netplay and CRT shaders. | **Non-Profit / Community Scale** ($150K–$300K/year Patreon & OpenCollective funding) | **$0.00 / Free Open-Source** (Optional Patreon donations from $1 to $50/month) | **Forever Free & Open-Source** (Unrestricted access to all Libretro cores, netplay, shaders, and cross-platform releases on Steam/App Stores) |
| **[Playnite (Hosted Addon & Metadata Ecosystem)](https://playnite.link)** | Open-source unified PC and emulated/ported game library manager with hosted plugin/theme repositories and full-screen controller UI. | **Community Project Scale** ($20K–$50K/year Patreon donations) | **$0.00 / Free Open-Source** (Optional Patreon support) | **Forever Free & Open-Source** (Unrestricted MIT license for full desktop & fullscreen mode, scraper plugins, and cloud integrations) |
| **[Batocera.linux (Hosted OS & Content Ecosystem)](https://batocera.org)** | Plug-and-play retro-gaming Linux OS distribution with hosted theme/bezel repositories supporting x86_64, Raspberry Pi, and ARM handhelds. | **Community Project Scale** ($15K–$40K/year OpenCollective & donations) | **$0.00 / Free Open-Source** (100% free bootable OS) | **Forever Free & Open-Source** (Unrestricted access to complete bootable OS, emulator cores, scraping, and themes with no usage limits) |

---

## 💻 Open-Source Reverse Engineering, Porting & Recompilation Projects

*Open-source GitHub repositories sorted in descending order of GitHub_Stars. Each Stars_Badge links directly to the project's stargazers page.*

| 📦 Repository & GitHub_Stars | 🏷️ License | 🎯 Category | 📖 Description |
| :--- | :--- | :--- | :--- |
| **[Ghidra](https://github.com/NationalSecurityAgency/ghidra)**<br><a href="https://github.com/NationalSecurityAgency/ghidra/stargazers"><img src="https://img.shields.io/github/stars/NationalSecurityAgency/ghidra?style=social&color=white" alt="Ghidra Stars"/></a> | Apache-2.0 | Reverse Engineering Suite | National Security Agency (NSA) flagship software reverse engineering framework with decompiler, disassembly analyzer, and scripting interface. |
| **[ImHex](https://github.com/WerWolv/ImHex)**<br><a href="https://github.com/WerWolv/ImHex/stargazers"><img src="https://img.shields.io/github/stars/WerWolv/ImHex?style=social&color=white" alt="ImHex Stars"/></a> | GPL-2.0 | Binary & Hex Editor | Modern interactive hex editor tailored for reverse engineers, binary analysts, and security researchers with custom pattern language (Pattern Language). |
| **[Proton](https://github.com/ValveSoftware/Proton)**<br><a href="https://github.com/ValveSoftware/Proton/stargazers"><img src="https://img.shields.io/github/stars/ValveSoftware/Proton?style=social&color=white" alt="Proton Stars"/></a> | Custom / BSD | OS Compatibility Layer | Valve's compatibility runtime based on Wine and translation layers, powering Steam Play and enabling thousands of Windows games to run seamlessly on Linux/SteamOS. |
| **[radare2](https://github.com/radareorg/radare2)**<br><a href="https://github.com/radareorg/radare2/stargazers"><img src="https://img.shields.io/github/stars/radareorg/radare2?style=social&color=white" alt="radare2 Stars"/></a> | LGPL-3.0 | Disassembler & Debugger | UNIX-like reverse engineering framework, command-line hex editor, binary debugger, and code disassembler supporting dozens of architectures. |
| **[Frida](https://github.com/frida/frida)**<br><a href="https://github.com/frida/frida/stargazers"><img src="https://img.shields.io/github/stars/frida/frida?style=social&color=white" alt="Frida Stars"/></a> | wxWindows | Dynamic Instrumentation | Dynamic instrumentation toolkit enabling developers and reverse engineers to inject JavaScript snippets and custom code into native app processes. |
| **[DXVK](https://github.com/doitsujin/dxvk)**<br><a href="https://github.com/doitsujin/dxvk/stargazers"><img src="https://img.shields.io/github/stars/doitsujin/dxvk?style=social&color=white" alt="DXVK Stars"/></a> | zlib/libpng | Graphics Translation Layer | High-performance Vulkan-based translation layer for Direct3D 8, 9, 10, and 11, serving as a core foundation for gaming on Linux and Proton. |
| **[OpenRCT2](https://github.com/OpenRCT2/OpenRCT2)**<br><a href="https://github.com/OpenRCT2/OpenRCT2/stargazers"><img src="https://img.shields.io/github/stars/OpenRCT2/OpenRCT2/stargazers"><img src="https://img.shields.io/github/stars/OpenRCT2/OpenRCT2?style=social&color=white" alt="OpenRCT2 Stars"/></a> | GPL-3.0 | Native Game Port | Ground-up open-source C++ recreation and port of RollerCoaster Tycoon 2 with multiplayer support, high resolution scaling, and native 64-bit binaries. |
| **[RetroArch](https://github.com/libretro/RetroArch)**<br><a href="https://github.com/libretro/RetroArch/stargazers"><img src="https://img.shields.io/github/stars/libretro/RetroArch?style=social&color=white" alt="RetroArch Stars"/></a> | GPL-3.0 | Multi-System Frontend | Frontend for Libretro API capable of hosting modular emulation cores, game engines, CRT shaders, netplay, and native ports across all desktop and mobile platforms. |
| **[Playnite](https://github.com/JosefNemec/Playnite)**<br><a href="https://github.com/JosefNemec/Playnite/stargazers"><img src="https://img.shields.io/github/stars/JosefNemec/Playnite?style=social&color=white" alt="Playnite Stars"/></a> | MIT | Library Frontend | Open-source video game library manager supporting PC games, ported builds, and 50+ emulators with full-screen controller mode and automatic metadata scraping. |
| **[RenderDoc](https://github.com/baldurk/renderdoc)**<br><a href="https://github.com/baldurk/renderdoc/stargazers"><img src="https://img.shields.io/github/stars/baldurk/renderdoc?style=social&color=white" alt="RenderDoc Stars"/></a> | MIT | Graphics Debugger | Stand-alone graphics frame debugger for Vulkan, D3D11, D3D12, and OpenGL, indispensable for graphics engine porting and shader pipeline reverse engineering. |
| **[DevilutionX](https://github.com/diasurgical/devilutionX)**<br><a href="https://github.com/diasurgical/devilutionX/stargazers"><img src="https://img.shields.io/github/stars/diasurgical/devilutionX?style=social&color=white" alt="DevilutionX Stars"/></a> | Sustainable Use | Source Port Engine | Source engine recreation of Diablo 1 and Hellfire supporting modern resolutions, cross-platform multiplayer, touch controls, and native ports across 25+ platforms. |
| **[N64Recomp](https://github.com/N64Recomp/N64Recomp)**<br><a href="https://github.com/N64Recomp/N64Recomp/stargazers"><img src="https://img.shields.io/github/stars/N64Recomp/N64Recomp?style=social&color=white" alt="N64Recomp Stars"/></a> | MIT | Static Recompiler | Offline static binary recompilation framework that analyzes MIPS3 N64 game binaries and re-emits native C code to create native PC executables without emulation. |
| **[Zelda64Recomp](https://github.com/Zelda64Recomp/Zelda64Recomp)**<br><a href="https://github.com/Zelda64Recomp/Zelda64Recomp/stargazers"><img src="https://img.shields.io/github/stars/Zelda64Recomp/Zelda64Recomp?style=social&color=white" alt="Zelda64Recomp Stars"/></a> | MIT | Native PC Recompilation | Native PC port of The Legend of Zelda: Majora's Mask and Ocarina of Time powered by static recompilation, offering unlocked framerates, ray tracing hooks, and ultrawide displays. |
| **[OpenMW](https://github.com/OpenMW/openmw)**<br><a href="https://github.com/OpenMW/openmw/stargazers"><img src="https://img.shields.io/github/stars/OpenMW/openmw?style=social&color=white" alt="OpenMW Stars"/></a> | GPL-3.0 | Modern Reimplementation | Free, open-source reimplementation of The Elder Scrolls III: Morrowind engine written in C++ with modern physics, multiplayer (TES3MP), and cross-platform native support. |
| **[Ship of Harkinian](https://github.com/HarbourMasters/Shipwright)**<br><a href="https://github.com/HarbourMasters/Shipwright/stargazers"><img src="https://img.shields.io/github/stars/HarbourMasters/Shipwright?style=social&color=white" alt="Ship of Harkinian Stars"/></a> | MIT | Native Decompiled Port | Complete native PC port of The Legend of Zelda: Ocarina of Time built from matching C decompilation, featuring 60FPS+ interpolation, gyro aiming, and HD texture packs. |
| **[MoltenVK](https://github.com/KhronosGroup/MoltenVK)**<br><a href="https://github.com/KhronosGroup/MoltenVK/stargazers"><img src="https://img.shields.io/github/stars/KhronosGroup/MoltenVK?style=social&color=white" alt="MoltenVK Stars"/></a> | Apache-2.0 | Graphics Translation Layer | Khronos-backed Vulkan implementation running directly over Apple's Metal graphics framework, enabling Vulkan games and engines to execute on macOS, iOS, and tvOS. |
| **[Box64](https://github.com/ptitSeb/box64)**<br><a href="https://github.com/ptitSeb/box64/stargazers"><img src="https://img.shields.io/github/stars/ptitSeb/box64?style=social&color=white" alt="Box64 Stars"/></a> | MIT | Dynamic Translation | Linux userspace x86_64 emulator with dynamic recompilation for ARM64 and RISC-V devices, allowing Windows/x86 PC games to run natively on Raspberry Pi and handhelds. |
| **[Rizin](https://github.com/rizinorg/rizin)**<br><a href="https://github.com/rizinorg/rizin/stargazers"><img src="https://img.shields.io/github/stars/rizinorg/rizin?style=social&color=white" alt="Rizin Stars"/></a> | LGPL-3.0 | Reverse Engineering Framework | Free, community-driven reverse engineering framework, disassembler, and hex analysis suite with Cutter GUI, focused on clean architecture and stability. |
| **[Batocera.linux](https://github.com/batocera-linux/batocera.linux)**<br><a href="https://github.com/batocera-linux/batocera.linux/stargazers"><img src="https://img.shields.io/github/stars/batocera-linux/batocera.linux?style=social&color=white" alt="Batocera Stars"/></a> | GPL-2.0 | Retro Gaming OS | Complete retro-gaming Linux distribution turnkey solution bootable via USB/SD card for x86 PCs, handheld consoles, and single-board computers. |
| **[vkd3d-proton](https://github.com/HansKristian-Work/vkd3d-proton)**<br><a href="https://github.com/HansKristian-Work/vkd3d-proton/stargazers"><img src="https://img.shields.io/github/stars/HansKristian-Work/vkd3d-proton?style=social&color=white" alt="vkd3d-proton Stars"/></a> | LGPL-2.1 | Graphics Translation Layer | Direct3D 12 to Vulkan translation library for Proton, targeting modern AAA games and native Windows-to-Linux graphics runtime translation. |
| **[Recalbox OS](https://github.com/recalbox/recalbox-os)**<br><a href="https://github.com/recalbox/recalbox-os/stargazers"><img src="https://img.shields.io/github/stars/recalbox/recalbox-os?style=social&color=white" alt="Recalbox Stars"/></a> | GPL-2.0 | Retro Gaming OS | French retro-gaming operating system supporting Raspberry Pi, PC, Odroid, and handhelds with built-in CRT 15kHz video output and web administration. |
| **[decomp.me](https://github.com/decompme/decomp.me)**<br><a href="https://github.com/decompme/decomp.me/stargazers"><img src="https://img.shields.io/github/stars/decompme/decomp.me?style=social&color=white" alt="decomp.me Stars"/></a> | MIT | Collaborative Matching | Collaborative web platform and assembly-matching scratchpad for reverse-engineering legacy binaries and verifying matching C/C++ decompilations. |
| **[FIFA Street PC Port](https://github.com/samuelit0davila/fifa-street-pc-port)**<br><a href="https://github.com/samuelit0davila/fifa-street-pc-port/stargazers"><img src="https://img.shields.io/github/stars/samuelit0davila/fifa-street-pc-port?style=social&color=white" alt="FIFA Street Stars"/></a> | GPL-3.0 | Native Console-to-PC Port | Open-source native PC port and source-level recreation of EA Sports FIFA Street with widescreen enhancements and direct controller input. |

---

## 🌟 Star History

[![Star History Chart](https://www.star-history.com/svg?repos=ishandutta2007/Awesome-Game-Porting-Reverse-Engineering&type=date&legend=top-left)](https://www.star-history.com/#ishandutta2007/Awesome-Game-Porting-Reverse-Engineering&type=date&legend=top-left)

---

## 🛠️ How to Contribute

Contributions are warmly welcomed! 🤝

1. Fork this repository: `git checkout -b feature/amazing-port-tool`
2. Ensure new additions include factual descriptions, license types, and links.
3. Check that SaaS products include specific pricing and free tier/trial limit details.
4. Open a Pull Request with a clear summary of your additions.

---

## 💖 Support & Sponsorship

If this curated collection helped you in your game preservation, console-to-PC porting, or reverse-engineering work, please consider supporting the project!

- ⭐ **Star this repository** to help others discover it!
- 🍴 **Fork and share** with fellow developers and preservationists.
- ☕ **Buy me a coffee / Sponsor**: If you'd like to back ongoing research and maintenance, please consider sponsoring via the [GitHub Sponsors Dashboard](https://github.com/sponsors/ishandutta2007). Your support is deeply appreciated! 🚀

---

## ⚠️ Disclaimer

All product names, logos, trademarks, and registered trademarks belong to their respective owners. Mention of commercial or open-source projects is strictly for educational, historical preservation, and technical documentation purposes.
