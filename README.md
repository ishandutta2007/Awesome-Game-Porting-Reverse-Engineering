# Awesome-Game-Porting-Reverse-Engineering

<p align="center">
  <img src="./assets/banner.svg" alt="Top Game Porting & Reverse Engineering" width="100%" />
</p>

<p align="center">
  <a href="https://github.com"><img src="https://shields.io" alt="Awesome"/></a>
  <a href="https://discord.gg"><img src="https://shields.io" alt="Discord" /></a>
  <a href="https://github.com"><img src="https://shields.io" alt="GitHub stars" /></a>
  <a href="https://github.com"><img src="https://shields.io" alt="GitHub forks" /></a>
  <a href="https://github.com"><img alt="GitHub followers" src="https://shields.io" /></a>
</p>

# 🛠️ Top Game Porting & Reverse Engineering

**Curated List of SaaS/Commercial Platforms & Open-Source GitHub Projects**  
*Focused on Console-to-PC Native Ports, Binary Decompilation & Static Recompilation, Graphics/OS Translation Layers (Wine/DXVK/MoltenVK) & Reverse-Engineering Suites*  
**Last updated: November 2026**

This repository tracks notable **SaaS/Commercial platforms** and **open-source projects** for **Game Porting & Reverse Engineering**. These tools power console-to-PC native game ports (`fifa-street-pc-port`, `Ship of Harkinian`, `Zelda64Recomp`, `UnleashedRecompiled`), static binary recompilation (`N64Recomp`, `XenonRecomp`), decompilation and assembly-matching suites (`Ghidra`, `Radare2`, `Rizin`, `decomp.me`), DirectX-to-Vulkan/Metal graphics translation (`DXVK`, `vkd3d-proton`, `MoltenVK`), and cross-architecture execution (`Wine`, `Proton`, `Box64`) for preservation engineers and reverse-engineering developers.

**Examples** include GeForce NOW (NVIDIA), Boosteroid, Shadow PC (OVHcloud / Octave Klaba), Antstream Arcade, Utomik, LaunchBox / Big Box (Unbroken Software), RetroArch (Libretro Cloud / Store Ecosystem), Playnite (Hosted Addon/Metadata Ecosystem), Batocera.linux (Hosted OS Ecosystem), and Recalbox (Commercial Hardware/Kit Ecosystem) (the category leaders).

**🚀 Open-source emphasis**: This section is heavily expanded with every major active project for community console-to-PC ports (`samuelit0davila/fifa-street-pc-port`, `OpenMW`, `DevilutionX`, `OpenRCT2`, `Ship of Harkinian`), static binary recompilers (`N64Recomp`, `XenonRecomp`), reverse-engineering & decompilation suites (`Ghidra`, `Rizin / Cutter`, `decomp.me`, `ImHex`, `RenderDoc`, `Frida`), and graphics/OS porting layers (`Wine`, `Proton`, `DXVK`, `MoltenVK`, `Box64`) — ideal for preservationists and porting engineers.

🤝 Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## 📑 Table of Contents
- [📊 Sector Overview & Market Dynamics](#-sector-overview--market-dynamics)
- [☁️ SaaS/Hosted & Commercial Platforms](#️-saashosted--commercial-platforms)
- [💻 Open-Source GitHub Projects](#-open-source-github-projects)
- [🛠️ How to Contribute](#️-how-to-contribute)
- [⚠️ Disclaimer](#️-disclaimer)
- [💖 Support & Thank You](#-support--thank-you)

## 📊 Sector Overview & Market Dynamics

The global Cloud Gaming, Game Preservation & Cross-Platform Porting Tools market is valued at approximately **$10.5B–$13.8B+ in 2026**, expanding at a ~20%–26% CAGR driven by Linux/SteamOS handheld adoption, Apple Silicon native/translation gaming, and classic console preservation initiatives. While commercial cloud-streaming delivery exhibits **strong winner-take-most consolidation** around NVIDIA GeForce NOW, Boosteroid, and Shadow PC, the **reverse-engineering, binary decompilation, graphics translation, and native PC porting ecosystems are overwhelmingly open-source led** (`Ghidra`, `Wine/Proton`, `DXVK`, `N64Recomp`, `XenonRecomp`, `RenderDoc`).

## ☁️ SaaS/Hosted & Commercial Platforms

*Sorted descending by company valuation / annual revenue scale.*

| Platform | Description | Company Scale (Valuation / Revenue) | Starting Paid Tier | Free Tier / Trial Limit |
| :--- | :--- | :--- | :--- | :--- |
| **[GeForce NOW (NVIDIA)](https://nvidia.com)** | Cloud RTX GPU game-streaming platform running PC libraries from Steam, Epic, Xbox, and GOG across Windows, macOS, Linux, browsers, and handhelds. | **Part of NVIDIA Corp.** (~$130B+ annual revenue; ~$3T+ market cap) | **$9.99 / month** ($49.99/6 mos Performance) or **$19.99 / month** ($99.99/6 mos Ultimate RTX 4080/5080) | **Forever Free Basic Tier** (Ad-supported **1-hour session limit** with standard queue access and basic cloud rig) |
| **[Shadow PC (OVHcloud / Octave Klaba)](https://shadow.tech)** | Full cloud Windows 11 gaming and reverse-engineering workstation streamed at low latency to macOS, Linux, iOS, and Android. | **Backed by Octave Klaba / OVHcloud** (~€1B+ OVHcloud group revenue) | **$19.99 / month** (Discovery tier) or **$32.99 – $49.99 / month** (Boost / Power RTX GPU tiers) | **No Perpetual Free Tier** (Occasional first-month promo discounts; full Windows cloud VM requires active monthly subscription) |
| **[Boosteroid](https://boosteroid.com)** | Leading European independent cloud gaming platform streaming AAA and classic PC titles at up to 4K/120fps across Linux, macOS, browsers, and TVs. | **~$100M–$200M Est. Valuation** (~$20M–$40M est. ARR; rapid EU/US server expansion) | **€7.49 / month** billed annually (€89.89/yr) or **€9.89 / month** monthly for Ultra 4K | **No Perpetual Free Tier** (Free account enables network latency/bitrate testing prior to purchasing a pass) |
| **[Antstream Arcade](https://antstream.com)** | Official cloud retro-gaming platform streaming 1,300+ licensed arcade, Amiga, Commodore, SNES, and PlayStation classics with cloud saves. | **~$30M–$50M Est. Valuation** (~$5M–$10M est. ARR; $20M+ VC funding) | **$3.99 / month** ($39.99/yr annual subscription) or **$99.99 one-time** Lifetime pass | **Forever Free Ad-Supported Tier** (Free retro game play supported by pre-roll ads and tournament gems) |
| **[Utomik](https://utomik.com)** | Subscription cloud and fast-chunked-download PC/retro gaming platform curating 1,400+ indie, classic, and family titles on PC and smart TVs. | **~$15M–$30M Est. Valuation** (~$5M+ est. ARR; Dutch cloud-gaming company) | **$8.99 / month** for PC plan or **$11.99 / month** for PC + Cloud TV plan | **14-Day Free Trial** (Unlimited access to the 1,400+ game catalog during the 14-day evaluation period; no perpetual free tier) |
| **[LaunchBox / Big Box (Unbroken Software)](https://launchbox-app.com)** | Premier Windows/Android retro-game launcher, metadata scraper, and 10-foot arcade cabinet frontend integrating emulators and native PC ports. | **~$5M–$15M Est. Scale** (Profitable independent US retro-gaming software company) | **$30 / year** (1-year updates) or **$75 one-time** Forever Updates license for Big Box mode | **Forever Free LaunchBox Desktop** (100% free desktop game library organizer, port/emulator launcher, and metadata scraper forever) |
| **[RetroArch (Libretro Cloud / Store Ecosystem)](https://retroarch.com)** | Cross-platform frontend for Libretro cores running hundreds of open-source emulators and native game-engine ports with netplay and CRT shaders. | **Non-Profit / Community Open-Source Project** (Patreon & bounty funded) | **$0 / Free Open-Source** (Optional Patreon tiers for buildbot infrastructure support) | **100% Free Forever** (Available free across Windows, macOS, Linux, iOS/tvOS App Store, Android, Steam, and consoles) |
| **[Playnite (Hosted Addon & Metadata Ecosystem)](https://playnite.link)** | Open-source unified PC and emulated/ported game library manager with hosted plugin/theme repositories and full-screen controller UI. | **Community Open-Source Project** (Maintained by Josef Nemec & contributors) | **$0 / Free Open-Source** (Optional Patreon sponsorship) | **100% Free Forever** (MIT-licensed unified launcher integrating Steam, Epic, GOG, custom PC ports, and 50+ emulators) |
| **[Batocera.linux (Hosted OS & Content Ecosystem)](https://batocera.org)** | Plug-and-play retro-gaming Linux OS distribution with hosted theme/bezel repositories supporting x86_64, Raspberry Pi, and ARM handhelds. | **Community Open-Source Project** (Donation & OpenCollective funded) | **$0 / Free Open-Source** (100% free downloadable bootable OS images) | **100% Free Forever** (Unlimited USB/SD live-boot retro console OS with 150+ pre-configured emulators and native ports) |
| **[Recalbox (Commercial Hardware / RGB Dual Ecosystem)](https://recalbox.com)** | User-friendly open-source retro-gaming OS paired with official Recalbox RGB Dual CRT hardware adapters, pre-flashed kits, and Patreon early builds. | **~$2M–$5M Est. Scale** (French retro-gaming hardware & open-source software organization) | **$0 / Free OS** (Official Recalbox RGB Dual/JAMMA CRT hardware kits from **€39–€89**) | **100% Free Forever OS** (Free downloadable OS images for Raspberry Pi, PC, and handhelds with built-in Kodi and netplay) |

## 💻 Open-Source GitHub Projects

| Project | License / Hosting Cost | Free Tier / Self-Hosted Limit | Description |
| :--- | :--- | :--- | :--- |
