# Awesome Android Native Ports [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of native Android ports of PC and console games: source ports, decompilation-based ports and static recompilations that run on Android without emulation.

A native Android port runs a game's own code, or a faithful reimplementation of its engine, directly on your phone, tablet or handheld, usually drawing with OpenGL ES or Vulkan. That is different from emulating a console, translating a Windows binary at runtime (Wine, Box64, Winlator) or streaming from a PC. The payoff is better performance, touch and gyro controls, widescreen support and mods.

Almost every project below follows the same rule: **no copyrighted game data is included.** You bring your own copy of the game (a disc image, a ROM or the PC game files) and the app imports or converts it on the device.

The list was last checked on 2026-10-21. It currently holds 210 ports.

> Many of these projects are young. Some are experimental, some were built with AI assistance, and a few only run on certain GPUs or handhelds. Read each project's README and status notes before you rely on it.

---

## Contents

- [Source Ports & Engine Reimplementations](#source-ports--engine-reimplementations)
- [Decompilation-Based Ports](#decompilation-based-ports)
- [N64: Recompiled](#n64-recompiled)
- [Wii U, Wii, GameCube, DS & Switch Recompilations](#wii-u-wii-gamecube-ds--switch-recompilations)
- [Xbox 360 Recompilations](#xbox-360-recompilations)
- [Original Xbox, PlayStation, PSP & PC Recompilations](#original-xbox-playstation-psp--pc-recompilations)
- [Handheld & 16-Bit Recompilations](#handheld--16-bit-recompilations)
- [Games on Their Own Runtimes & Launchers](#games-on-their-own-runtimes--launchers)
- [Classic Ports (Low Activity)](#classic-ports-low-activity)
- [Tools & Frameworks](#tools--frameworks)
- [Related Lists](#related-lists)
- [Contributing](#contributing)
- [Disclaimer](#disclaimer)
- [Credits](#credits)

---

## Source Ports & Engine Reimplementations

Open-source engines and source ports that run a game's original data natively on Android. You provide the game files.

| Game | Description | Author |
|------|-------------|--------|
| [Aerofoil (Glider PRO)](https://github.com/elasota/Aerofoil) | Multiplatform port of the classic Macintosh paper-airplane game Glider PRO, with an Android APK in releases. | [elasota](https://github.com/elasota) |
| [Ambermoon](https://github.com/Pyrdacor/Ambermoon.net) | C# rewrite of the Amiga RPG Ambermoon with an Android APK in releases; needs your original game files. | [Pyrdacor](https://github.com/Pyrdacor) |
| [Barony](https://github.com/DifferentNet/barony-android-port) | Beta native Android port of Barony; code-only APK that requires a purchased Barony v5.0.2 installation. | [DifferentNet](https://github.com/DifferentNet) |
| [Black & White](https://github.com/openblack/openblack) | Open-source reimplementation of Black & White (2001) in modern C++ with an Android APK package built by CI. | [openblack](https://github.com/openblack) |
| [Caesar III](https://github.com/bvschaik/julius) | Open-source re-implementation of Caesar III with an Android release on Google Play and APKs on GitHub. | [bvschaik](https://github.com/bvschaik) |
| [Caesar III (Augustus)](https://github.com/Keriew/augustus) | Julius-based Caesar III re-implementation with extra gameplay features and Android APKs in releases. | [Keriew](https://github.com/Keriew) |
| [Carmageddon 2](https://github.com/Link4Electronics/Carpocalypse2) | Decompilation and native port of Carmageddon 2 with armv7 Android APKs; needs the original game data. | [Link4Electronics](https://github.com/Link4Electronics) |
| [Classic adventure games (ScummVM)](https://github.com/scummvm/scummvm) | Engine reimplementation for point-and-click adventures and RPGs with an official Android backend; you supply the game data. | [scummvm](https://github.com/scummvm) |
| [Colin McRae Rally 2.0](https://github.com/pablocpas/OpenCMR2) | Native SDL3 port built from the CMR2Decomp decompilation, running on Android with no game data included. | [pablocpas](https://github.com/pablocpas) |
| [Command & Conquer: Generals - Zero Hour](https://github.com/molotovgit/CnC-Generals-ZeroHour-Android) | Early arm64 Android port built on the GeneralsX engine with SDL3 and DXVK (Direct3D 8 to Vulkan) and touch controls. | [molotovgit](https://github.com/molotovgit) |
| [Command & Conquer: Red Alert](https://github.com/dk8827/ra-port) | Native SDL2 source port of Red Alert for Android, iOS, Linux and macOS, with the Android build produced as a local debug APK. | [dk8827](https://github.com/dk8827) |
| [Command & Conquer: Tiberian Dawn](https://github.com/dk8827/cnc-port) | Unofficial native port of Tiberian Dawn running on iOS, Android and macOS; no game assets included. | [dk8827](https://github.com/dk8827) |
| [Command & Conquer: Tiberian Dawn (Android and Quest)](https://github.com/Cesarus85/Tiberian-Dawn-for-Android-and-Meta-Quest) | Prototype Android and Meta Quest 3 port of Tiberian Dawn with APKs in releases and no game data included. | [Cesarus85](https://github.com/Cesarus85) |
| [Counter-Strike 1.6](https://github.com/Velaron/cs16-client) | Reverse-engineered Counter-Strike 1.6 client for Xash3D FWGS with a continuous Android APK build. | [Velaron](https://github.com/Velaron) |
| [Diablo & Hellfire](https://github.com/diasurgical/DevilutionX) | Port of Diablo and Hellfire with engine improvements and an Android APK attached to every release. | [diasurgical](https://github.com/diasurgical) |
| [DOOM 3, Quake 4, Prey and more (idTech4A++)](https://github.com/glKarin/com.n0n3m4.diii4a) | OpenGL ES port of the idTech 4 games plus Quake 1-3, RTCW, GZDoom, OpenJK and others, with APKs and F-Droid builds. | [glKarin](https://github.com/glKarin) |
| [Doom, Wolfenstein RPG, Quake and more (Mobile RPG Pack)](https://github.com/sandstranger/com.mobilerpgpack.phone) | Collection of unofficial Android ports of classic engines including Doom, the Wolfenstein RPG series, Doom 64 EX+, UZDoom and Red Alert. | [sandstranger](https://github.com/sandstranger) |
| [FTL: Faster Than Light](https://github.com/adamkulik/pocket-wormhole) | Native Android port of Project Wormhole, a reimplementation of the FTL engine. | [adamkulik](https://github.com/adamkulik) |
| [Gothic II](https://github.com/Try/OpenGothic) | Reimplementation of the Gothic 1 and 2 client, compatible with the original game data and mods, with an Android APK build target. | [Try](https://github.com/Try) |
| [Half-Life (Xash3D FWGS)](https://github.com/FWGS/xash3d-fwgs) | Custom GoldSrc-compatible engine that runs Half-Life and its mods, with a continuous Android APK build. | [FWGS](https://github.com/FWGS) |
| [Heroes of Might and Magic II](https://github.com/ihhub/fheroes2) | Recreation of the Heroes II engine with an Android project and Android packages published alongside releases. | [ihhub](https://github.com/ihhub) |
| [Heroes of Might and Magic III](https://github.com/vcmi/vcmi) | Open-source engine for Heroes III with arm64 and armv7 Android APKs in every release. | [vcmi](https://github.com/vcmi) |
| [Jagged Alliance 2](https://github.com/ja2-stracciatella/ja2-stracciatella) | Continuation of the JA2 Stracciatella port, adding stability fixes, a mod platform and an Android APK. | [ja2-stracciatella](https://github.com/ja2-stracciatella) |
| [Jazz Jackrabbit](https://github.com/AlisterT/openjazz) | Free, open-source engine for the classic Jazz Jackrabbit games with continuous Android builds. | [AlisterT](https://github.com/AlisterT) |
| [Jazz Jackrabbit 2](https://github.com/deathkiller/jazz2-native) | Jazz² Resurrection, a native C++ reimplementation of Jazz Jackrabbit 2 with an Android build that needs the original game files. | [deathkiller](https://github.com/deathkiller) |
| [Knytt Stories](https://github.com/youkaicountry/yknytt) | Open-source Godot (C#) implementation of Knytt Stories with an Android APK in releases. | [youkaicountry](https://github.com/youkaicountry) |
| [LEGO Island](https://github.com/isledecomp/isle-portable) | Portable version of LEGO Island (1997) built on the decompilation, with Android builds from CI. | [isledecomp](https://github.com/isledecomp) |
| [Little Big Adventure 2](https://github.com/LBALab/lba2-classic-community) | Community source port of the LBA2 engine with Android and Android TV builds (7.0 and newer). | [LBALab](https://github.com/LBALab) |
| [MDK](https://github.com/nautilusbits/mdk-sdl) | C# and SDL3 port of MDK based on reverse engineering, with Android builds and a Cardboard stereo 3D viewer. | [nautilusbits](https://github.com/nautilusbits) |
| [Micropolis](https://github.com/ds17f/andropolis) | Native Android port of Micropolis built on the MicropolisCore C++ engine via NDK and JNI. | [ds17f](https://github.com/ds17f) |
| [Might and Magic VI-VIII](https://github.com/OpenEnroth/OpenEnroth) | Open reimplementation of the Might and Magic VI, VII and VIII engine with nightly universal Android APKs. | [OpenEnroth](https://github.com/OpenEnroth) |
| [Morrowind (OpenMW)](https://github.com/Andiweli/OpenMW-Android) | OpenMW for Android and ChromeOS, extended with optimizations and new shaders on top of Cavebros' port. | [Andiweli](https://github.com/Andiweli) |
| [Need for Speed II SE](https://github.com/zaps166/NFSIISE) | Cross-platform wrapper for NFS II SE with 3D acceleration and TCP multiplayer, with 32-bit ARM Android builds in releases. | [zaps166](https://github.com/zaps166) |
| [NetHack](https://github.com/gurrhack/NetHack-Android) | Android port of NetHack. | [gurrhack](https://github.com/gurrhack) |
| [PAL (Legend of Sword and Fairy)](https://github.com/sdlpal/sdlpal) | SDL-based reimplementation of the classic Chinese RPG PAL with an Android APK in releases. | [sdlpal](https://github.com/sdlpal) |
| [Prehistorik 2](https://github.com/missingno7/pre2_port) | Python source port reconstructed piece by piece from PRE2.EXE, with an arm64 Android APK in releases. | [missingno7](https://github.com/missingno7) |
| [Quake 4](https://github.com/themuffinator/openQ4) | Open-source engine for Quake 4 with an experimental ARM64 Android APK and source build. | [themuffinator](https://github.com/themuffinator) |
| [Raptor: Call of the Shadows](https://github.com/skynettx/raptor) | Reverse-engineered source port of Raptor with an Android APK in releases. | [skynettx](https://github.com/skynettx) |
| [Richman 4](https://github.com/lhr0909/richman4-remastered) | Native C++20 and SDL3 reimplementation of Richman 4 for macOS, Android and iOS using your own Steam copy. | [lhr0909](https://github.com/lhr0909) |
| [Rise of the Triad](https://github.com/h4mu/rott94) | SDL2 source port of Rise of the Triad for Android and WinRT with touch controls. | [h4mu](https://github.com/h4mu) |
| [RollerCoaster Tycoon 2 (OpenRCT2)](https://github.com/OpenRCT2/OpenRCT2) | Open-source re-implementation of RollerCoaster Tycoon 2 with an Android APK attached to each release. | [OpenRCT2](https://github.com/OpenRCT2) |
| [RPG Maker 2000/2003 (EasyRPG)](https://github.com/EasyRPG/Player) | Interpreter for RPG Maker 2000/2003 games that includes an Android build project. | [EasyRPG](https://github.com/EasyRPG) |
| [The Settlers](https://github.com/Pyrdacor/freeserf.net) | Authentic C# remake of The Settlers I with an Android APK; needs your original game data. | [Pyrdacor](https://github.com/Pyrdacor) |
| [Shortline](https://github.com/konovalov-aleks/reSL) | Reversed source code of the ShortLine railroad game with an Android APK in releases. | [konovalov-aleks](https://github.com/konovalov-aleks) |
| [Sonic 3 & Knuckles (Sonic 3 A.I.R.)](https://github.com/Eukaryot/sonic3air) | Source and Oxygen Engine for the Sonic 3 A.I.R. fan remaster, with Android APKs in releases. | [Eukaryot](https://github.com/Eukaryot) |
| [Sonic Robo Blast 2](https://github.com/thegreatbbd94-ux/SRB2-Android-Port) | Unofficial Android port of SRB2 v2.2.15 with touch controls, online multiplayer and Lua addon support. | [thegreatbbd94-ux](https://github.com/thegreatbbd94-ux) |
| [Spelunky Classic HD](https://github.com/yancharkin/SpelunkyClassicHD) | Modified Spelunky Classic built from the published GameMaker source, with a universal Android APK. | [yancharkin](https://github.com/yancharkin) |
| [Star Trek: Voyager - Elite Force](https://github.com/imjustadudegamer/VoyagerSP-Android) | Android single-player port of Elite Force on idTech 3 and Quake3e with a Vulkan renderer. | [imjustadudegamer](https://github.com/imjustadudegamer) |
| [Star Trek: Voyager - Elite Force Holomatch](https://github.com/imjustadudegamer/VoyagerHM-Android) | Android port of the Elite Force Holomatch multiplayer with a Vulkan renderer, touch controls and gamepad support. | [imjustadudegamer](https://github.com/imjustadudegamer) |
| [System Shock](https://github.com/raposomiguel50/system-shock-android) | Native Android arm64 port of System Shock based on Shockolate, validated on the Retroid Pocket 5. | [raposomiguel50](https://github.com/raposomiguel50) |
| [Tomb Raider I-III (OpenLara)](https://github.com/XProger/OpenLara) | Classic Tomb Raider engine with an Android app project in the tree. | [XProger](https://github.com/XProger) |
| [Tyrian 2000](https://github.com/andyvand/opentyrian2000) | Open-source port of the DOS shoot-em-up Tyrian with an Android zip in releases. | [andyvand](https://github.com/andyvand) |
| [Ultima V](https://github.com/synthwave-pixel/ultima5) | TypeScript engine for Ultima V that plays your own copy, with an Android APK in releases. | [synthwave-pixel](https://github.com/synthwave-pixel) |
| [Ultima VII (Exult)](https://github.com/exult/exult) | Engine recreation that plays Ultima VII with its original data, with Android snapshot APKs. | [exult](https://github.com/exult) |
| [Unreal](https://github.com/Andiweli/Unreal-Android) | Port of Unreal (v200) to Android 8 and newer, 32 and 64-bit, with controller, touch and keyboard support. | [Andiweli](https://github.com/Andiweli) |
| [Unreal Tournament 99](https://github.com/Andiweli/UT99-Android) | Unofficial UT99 (v400) port for Android with 32 and 64-bit builds; no game data included. | [Andiweli](https://github.com/Andiweli) |
| [Whiplash / Fatal Racing](https://github.com/FatalDecomp/ROLLER) | Reverse engineering and partial rewrite of the 1995 racer, with an Android release APK. | [FatalDecomp](https://github.com/FatalDecomp) |
| [Wolfenstein 3D, Keen and Catacomb (ReflectionHLE)](https://github.com/ReflectionHLE/ReflectionHLE) | Source ports of Keen Dreams, the Catacomb games, Wolfenstein 3D and related DOS titles, with an Android APK. | [ReflectionHLE](https://github.com/ReflectionHLE) |
| [Woody Woodpecker: Escape from Buzz Buzzard Park](https://github.com/jjmhalew/WoodyRE) | Engine reimplementation that plays the original game from your own CD, with an Android APK. | [jjmhalew](https://github.com/jjmhalew) |

---

## Decompilation-Based Ports

Ports built on matching or partial decompilations of console and PC games. Most of them publish Android APKs in their GitHub releases.

| Game | Description | Author |
|------|-------------|--------|
| [Animal Crossing (GameCube)](https://github.com/zwaetschge/ACGC-Android-Port) | Android port of the Animal Crossing PC port built on the ac-decomp decompilation; bring your own disc. | [zwaetschge](https://github.com/zwaetschge) |
| [Crash Team Racing (Dual Screen)](https://github.com/igawa6/ctr-native-android) | Android fork of CTR Native adding a second screen, a 64-bit build and graphics and frame-rate options. | [igawa6](https://github.com/igawa6) |
| [Halo: Combat Evolved (Android and AAOS)](https://github.com/Andiweli/HaloCE-Android-AAOS) | Halo CE port for Android phones, handhelds and Android Automotive OS with controller and touch support. | [Andiweli](https://github.com/Andiweli) |
| [Halo: Combat Evolved (Android)](https://github.com/FulGerNet/halo-ce-android) | Halo CE decompilation port with a dedicated Android build and APK releases. | [FulGerNet](https://github.com/FulGerNet) |
| [Halo: Combat Evolved (Chupathingy)](https://github.com/ChupathingyCE/chupathingyce) | Halo CE decompilation port for Windows, macOS, Linux and Android, built for stability and community multiplayer. | [ChupathingyCE](https://github.com/ChupathingyCE) |
| [Halo: Combat Evolved (OpenCE)](https://github.com/OpenCommunityEdition/OpenCE) | Decompilation-based Halo CE port for Windows, Linux, Android and the web, built from an early Xbox development build. | [OpenCommunityEdition](https://github.com/OpenCommunityEdition) |
| [ICO](https://github.com/nathanialf/ico-pc) | Native ICO (PS2) port for PC, Steam Deck, Android and Apple devices built on the decompilation; no game data included. | [nathanialf](https://github.com/nathanialf) |
| [Kingdom Hearts: Chain of Memories](https://github.com/MatyMeatBoy/ReKHCoM) | PC and browser port built on the matching decompilation, with an Android alpha APK. | [MatyMeatBoy](https://github.com/MatyMeatBoy) |
| [The Legend of Zelda: A Link to the Past (moonpearl)](https://github.com/DoutorRaposo/moonpearl) | Native Android port of the zelda3 reimplementation with widescreen, save states, rewind and controller support. | [DoutorRaposo](https://github.com/DoutorRaposo) |
| [The Legend of Zelda: The Minish Cap (Project Picori)](https://github.com/999sian/tmc) | Native port built on the zeldaret decompilation, with Android APKs in releases. | [999sian](https://github.com/999sian) |
| [The Legend of Zelda: Twilight Princess (Dusklight dual screen)](https://github.com/igawa6/dusklight) | Dusklight Android fork with a second-screen layout for dual-screen handhelds such as the AYN Thor. | [igawa6](https://github.com/igawa6) |
| [The Legend of Zelda: Twilight Princess (Dusklight)](https://github.com/TwilitRealm/dusklight) | Reverse-engineered Twilight Princess reimplementation with official Android arm64 APKs in releases. | [TwilitRealm](https://github.com/TwilitRealm) |
| [Majora's Mask (2 Ship 2 Harkinian, linkzenic fork)](https://github.com/linkzenic/2ship2harkinian-Android) | Unofficial Android fork of 2 Ship 2 Harkinian with recent releases. | [linkzenic](https://github.com/linkzenic) |
| [Mario Kart 64 (SpaghettiKart)](https://github.com/izzy2lost/SpaghettiKart) | Android port of SpaghettiKart with APK releases; bring your own ROM. | [izzy2lost](https://github.com/izzy2lost) |
| [Mario Party 4](https://github.com/mariopartyrd/partyboard) | Work-in-progress Party Board port of Mario Party 4 with an Android arm64 alpha. | [mariopartyrd](https://github.com/mariopartyrd) |
| [Mario Party 4 (phone and Quest)](https://github.com/zeranemesis/Marioparty4) | Party Board port of Mario Party 4 with phone and Quest APKs and online play for up to four players. | [zeranemesis](https://github.com/zeranemesis) |
| [Mario Party 6](https://github.com/iirg4x/mp6-native-port) | Native Windows and Android port of Mario Party 6 built on the byte-accurate GameCube decompilation. | [iirg4x](https://github.com/iirg4x) |
| [Metroid Prime](https://github.com/Odrannnn/MetroidPrimePort) | Native port built from the PrimeDecomp decompilation for Linux, Windows and Android; no game assets included. | [Odrannnn](https://github.com/Odrannnn) |
| [Ocarina of Time (Ship of Harkinian, linkzenic fork)](https://github.com/linkzenic/Shipwright-Android) | Actively updated Android fork of Ship of Harkinian. | [linkzenic](https://github.com/linkzenic) |
| [Oracle of Ages and Oracle of Seasons](https://github.com/kirby-letsgo/oracles-decomp) | Native macOS, Windows, Linux and Android versions of both Oracle games rebuilt from their own code in C. | [kirby-letsgo](https://github.com/kirby-letsgo) |
| [Oracle of Ages and Oracle of Seasons (The Oracles Project)](https://github.com/thibautbus/top) | Faithful, moddable port of both Oracle games for PC, macOS and Android that runs your own ROM. | [thibautbus](https://github.com/thibautbus) |
| [Perfect Dark](https://github.com/izzy2lost/perfect_dark) | Android port of the work-in-progress Perfect Dark PC port with arm64, armv7 and x86 builds. | [izzy2lost](https://github.com/izzy2lost) |
| [Pikmin and Pikmin 2 (Open Nectar)](https://github.com/SSunnKing/Open-Nectar---Pikmin-Native-PC-Mobile-Port) | Native ports of both GameCube Pikmin games for Linux, Windows and Android, playable start to finish. | [SSunnKing](https://github.com/SSunnKing) |
| [Silent Hill](https://github.com/SlickAmogus/silent-hill-decomp) | Feature-rich beta port of Silent Hill 1 based on the PSX decompilation, with Android APKs in releases. | [SlickAmogus](https://github.com/SlickAmogus) |
| [Sonic CD (Retro Engine v3)](https://github.com/RSDKModding/RSDKv3-Decompilation) | Complete decompilation of Sonic CD and Retro Engine v3 with Android builds in releases. | [RSDKModding](https://github.com/RSDKModding) |
| [Sonic Mania (Retro Engine v5)](https://github.com/RSDKModding/RSDKv5-Decompilation) | Decompilation of Retro Engine v5, the engine behind Sonic Mania, with an Android project and builds in releases. | [RSDKModding](https://github.com/RSDKModding) |
| [Sonic R](https://github.com/ZinexDa/sonic-r-android) | Android port of the Sonic R decompilation with a GLES2 renderer, touch controls and SAF asset installation. | [ZinexDa](https://github.com/ZinexDa) |
| [Sonic the Hedgehog 1 and 2 (Retro Engine v4)](https://github.com/RSDKModding/RSDKv4-Decompilation) | Complete decompilation of the 2013 Sonic 1 and 2 releases and Retro Engine v4 with Android builds. | [RSDKModding](https://github.com/RSDKModding) |
| [Space Rangers HD: A War Apart](https://github.com/pakompom/SpaceRangersHD_FPC) | Experimental Free Pascal port based on the recovered Delphi source, with an Android arm64 APK. | [pakompom](https://github.com/pakompom) |
| [Star Fox 64 (Starship)](https://github.com/izzy2lost/Starship) | Android port of the Starship Star Fox 64 PC port with APK releases. | [izzy2lost](https://github.com/izzy2lost) |
| [Super Mario 64 (Ghostship)](https://github.com/HarbourMasters/Ghostship) | Super Mario 64 PC port whose releases include Android alpha builds that extract your ROM on the device. | [HarbourMasters](https://github.com/HarbourMasters) |
| [Super Mario Galaxy](https://github.com/OpenPort-Labs/Galaxy-Android) | Native arm64 Android port with OpenGL ES 3.2, AAudio, ultrawide support and touch controls. | [OpenPort-Labs](https://github.com/OpenPort-Labs) |
| [Super Smash Bros. (N64)](https://github.com/JRickey/BattleShip) | PC port of Super Smash Bros. for N64 built on the ssb-decomp-re decompilation, with an armv7 Android APK. | [JRickey](https://github.com/JRickey) |
| [Super Smash Bros. Melee](https://github.com/999sian/melee-pc) | Beta native port built from doldecomp/melee with an Android arm64 APK; bring your own disc. | [999sian](https://github.com/999sian) |
| [Touhou 6: The Embodiment of Scarlet Devil](https://github.com/CNTianQi233/th06-sdl2) | SDL2 and OpenGL port of the community decompilation with Android builds that use a Vulkan renderer. | [CNTianQi233](https://github.com/CNTianQi233) |

---

## N64: Recompiled

Projects built with [N64: Recompiled](https://github.com/N64Recomp/N64Recomp), [N64ModernRuntime](https://github.com/N64Recomp/N64ModernRuntime) and [RT64](https://github.com/rt64/rt64), which statically recompile Nintendo 64 games into native programs.

| Game | Description | Author |
|------|-------------|--------|
| [AeroGauge](https://github.com/alondero/aerogauge-recomp) | Recompiled PC version of the N64 racer with an Android arm64 APK in releases. | [alondero](https://github.com/alondero) |
| [Automobili Lamborghini](https://github.com/alondero/automobililamborghini-recomp) | In-development native port of the North American N64 game with an Android arm64 APK. | [alondero](https://github.com/alondero) |
| [Banjo-Kazooie](https://github.com/AurelioB/BanjoRecomp-Android) | Experimental Android port of Banjo: Recompiled with APKs in releases. | [AurelioB](https://github.com/AurelioB) |
| [BattleTanx: Global Assault](https://github.com/wootbeer/btgarecomp) | Recompilation and port of the 1999 N64 game with an Android APK in releases. | [wootbeer](https://github.com/wootbeer) |
| [Conker's Bad Fur Day](https://github.com/codepdbh/CBFD-Recompiled-Android-Evolved) | Native Android port of Conker's Bad Fur Day Recompiled with touch controls and mod support. | [codepdbh](https://github.com/codepdbh) |
| [Diddy Kong Racing](https://github.com/ThatGuyMcd/DKR-R) | Diddy Kong Racing recompiled for Windows, Linux and Android with mod support. | [ThatGuyMcd](https://github.com/ThatGuyMcd) |
| [Donkey Kong 64](https://github.com/deivid22srk/dk64-recomp-android) | Android NDK port of Donkey Kong 64: Recompiled using RT64, Vulkan and SDL2. | [deivid22srk](https://github.com/deivid22srk) |
| [Harvest Moon 64](https://github.com/igawa6/HarvestMoon64Recomp) | Android port of Harvest Moon 64: Recompiled with touch controls, a launcher and a file picker. | [igawa6](https://github.com/igawa6) |
| [Majora's Mask](https://github.com/linkzenic/Zelda64Recomp-Android) | Android port of Zelda64 Recompiled with APK releases. | [linkzenic](https://github.com/linkzenic) |
| [Mystical Ninja Starring Goemon](https://github.com/ogdanimal/Goemon64Recomp-Android) | Android port of the Goemon recompilation with RT64 Vulkan rendering; bring your own ROM. | [ogdanimal](https://github.com/ogdanimal) |
| [Rocket: Robot on Wheels](https://github.com/ThatGuyMcd/Rocket-R) | Recompiled version for Windows, Linux and Android with higher resolutions and smoother frame rates. | [ThatGuyMcd](https://github.com/ThatGuyMcd) |
| [Star Wars: Rogue Squadron](https://github.com/MikeSemicolonD/RogueSquadron64Recomp) | AI-assisted recompilation for Windows, Linux and Android with touch controls and optional gyro steering. | [MikeSemicolonD](https://github.com/MikeSemicolonD) |
| [StarCraft 64](https://github.com/n0madic/StarCraft64-recomp) | Native desktop and Android port playable with mouse, keyboard, gamepad or touch screen. | [n0madic](https://github.com/n0madic) |
| [Super Robot Wars 64](https://github.com/dyzz/srw64-recomp) | Experimental recompilation (Marchwind 64) for Windows, macOS, Linux, Steam Deck and Android with English and Chinese text. | [dyzz](https://github.com/dyzz) |

---

## Wii U, Wii, GameCube, DS & Switch Recompilations

Static recompilations of Nintendo console games that run natively on Android. Several are built on [WiiCompiled](https://github.com/patchzyy/Wiicompiled).

| Game | Description | Author |
|------|-------------|--------|
| [Echoes of Wisdom](https://github.com/Nycolazs/EoWRecomp) | Alpha static recompilation of the Switch game with an Android arm64 APK and no game files included. | [Nycolazs](https://github.com/Nycolazs) |
| [The Legend of Zelda: The Wind Waker](https://github.com/chrissotraidis/bluewake) | GameCube Wind Waker recompilation for Apple platforms, Windows, Linux and an experimental build-your-own Android APK. | [chrissotraidis](https://github.com/chrissotraidis) |
| [The Legend of Zelda: The Wind Waker HD](https://github.com/ZeldaWWHDRecomp/ZeldaWWHDRecomp) | Wii U Wind Waker HD static recompilation with Android arm64 and x86_64 APKs in releases. | [ZeldaWWHDRecomp](https://github.com/ZeldaWWHDRecomp) |
| [The Legend of Zelda: The Wind Waker HD (Enhanced)](https://github.com/SSunnKing/ZeldaWWHDRecompAndroid---ENHANCED) | Enhanced Android fork with native widescreen, fixed shadows and a pinch-to-zoom camera. | [SSunnKing](https://github.com/SSunnKing) |
| [The Legend of Zelda: The Wind Waker HD (GreenNaugahyde)](https://github.com/GreenNaugahyde/ZeldaWWHDRecompAndroid) | Earlier Android fork of the Wind Waker HD recompilation with APK releases. | [GreenNaugahyde](https://github.com/GreenNaugahyde) |
| [The Legend of Zelda: The Wind Waker HD (Plus)](https://github.com/Nycolazs/WindWakerHD-Android-Plus) | Android build of the Wind Waker HD recompilation with a Portuguese translation and a HUD editor. | [Nycolazs](https://github.com/Nycolazs) |
| [Link's Awakening (Switch)](https://github.com/Nycolazs/LASRecomp-Android-Plus) | Native Android port of LAS Recomp with touch controls and 60 fps frame generation, set up from your own game on the phone. | [Nycolazs](https://github.com/Nycolazs) |
| [Mario Kart Wii (DriftDroid)](https://github.com/dorPXP/driftdroid) | Native Android port of Mario Kart Wii and Retro Rewind. | [dorPXP](https://github.com/dorPXP) |
| [Mario Kart Wii (KartPad)](https://github.com/chrissotraidis/kartpad) | Mario Kart Wii and Retro Rewind on Android and Apple platforms through the WiiCompiled static recompilation. | [chrissotraidis](https://github.com/chrissotraidis) |
| [Metroid Prime Hunters](https://github.com/aabrole/HuntersRecomp) | Native dual-screen Android port of the Hunters recompilation for the AYN Thor with twin-stick controls. | [aabrole](https://github.com/aabrole) |
| [New Super Mario Bros. Wii](https://github.com/WitherBlitz/NSMB-Wii-Multiplayer-Recompilation) | Static recompilation built on WiiCompiled that runs natively on Android and Windows; bring your own game. | [WitherBlitz](https://github.com/WitherBlitz) |
| [Pokémon SoulSilver](https://github.com/ClickingMaster/ssrecomp) | Native single-screen recomp of Pokémon SoulSilver with an experimental Android build produced by the setup program. | [ClickingMaster](https://github.com/ClickingMaster) |
| [Skies of Arcadia Legends](https://github.com/ogdanimal/SkiesOfArcadiaLegends-Recomp) | Beta native port for Windows, Linux, macOS and Android; bring your own disc. | [ogdanimal](https://github.com/ogdanimal) |
| [Super Mario Bros. Wonder](https://github.com/BelmanteGu/SuperMarioWonderRecomp) | Static recompilation of the Switch game with an Android arm64 build tested on a Galaxy S23; build from source. | [BelmanteGu](https://github.com/BelmanteGu) |

---

## Xbox 360 Recompilations

Xbox 360 recompilations that ship Android builds, mostly made with the [ReXGlue SDK](https://github.com/rexglue/rexglue-sdk) or [XenonRecomp](https://github.com/hedge-dev/XenonRecomp). See [awesome-x360-recomps](https://github.com/abduznik/awesome-x360-recomps) for the full, desktop-focused list.

| Game | Description | Author |
|------|-------------|--------|
| [Asura's Wrath](https://github.com/PauloUbirajara/asuras-wrath-recomp) | Work-in-progress ReXGlue recompilation with an Android APK in releases. | [PauloUbirajara](https://github.com/PauloUbirajara) |
| [Burnout Revenge](https://github.com/shipa-2/Xerenge) | Recompilation with a standalone Vulkan renderer and an Android arm64 APK in releases. | [shipa-2](https://github.com/shipa-2) |
| [Call of Duty: Modern Warfare 2](https://github.com/OpenPort-Labs/mw2-android) | Experimental Android arm64, Linux and Windows port with Vulkan rendering, touch and controller input. | [OpenPort-Labs](https://github.com/OpenPort-Labs) |
| [Dragon Ball Z: Burst Limit](https://github.com/dfdx047/Dragon-Burst) | Experimental native Android port of the ReXGlue Burst Limit recompilation. | [dfdx047](https://github.com/dfdx047) |
| [Eternal Sonata](https://github.com/birabittoh/EternalSonataReprise) | Static recompilation with Android arm64 APKs and troubleshooting notes for older Adreno drivers. | [birabittoh](https://github.com/birabittoh) |
| [Forza Horizon](https://github.com/arcanite24/pinyon-shift) | Playable Pinyon Shift preview for desktop and Steam Deck with an Android alpha for Snapdragon handhelds. | [arcanite24](https://github.com/arcanite24) |
| [Forza Horizon 2](https://github.com/Gabrick75/fh2-recompiled) | Unofficial static recompilation for Android, with APK releases. | [Gabrick75](https://github.com/Gabrick75) |
| [Lost Odyssey](https://github.com/freefrank/LostOdysseyRecomp) | Experimental native port with Android arm64 APKs in releases; no game assets included. | [freefrank](https://github.com/freefrank) |
| [Naruto Shippuden: Ultimate Ninja Storm 3 Full Burst](https://github.com/Masterllgod/naruto-storm-3-full-burst-port-nativo) | Static recompilation for Android arm64 and Windows with APK releases. | [Masterllgod](https://github.com/Masterllgod) |
| [Naruto Shippuden: Ultimate Ninja Storm Generations](https://github.com/Masterllgod/naruto-storm-generations-port-nativo) | Static recompilation running natively on Android arm64 and Windows with no CPU emulator. | [Masterllgod](https://github.com/Masterllgod) |
| [Naruto: Rise of a Ninja](https://github.com/Masterllgod/naruto-rise-of-a-ninja-port-nativo) | Native Android arm64 port with Vulkan rendering and 360p to 4K output. | [Masterllgod](https://github.com/Masterllgod) |
| [Need for Speed: Carbon](https://github.com/codepdbh/NFS-CARBON-360-ANDROID-RECOMP) | Experimental ReXGlue recompilation for Android arm64 and Windows with APK releases. | [codepdbh](https://github.com/codepdbh) |
| [Need for Speed: Carbon (Sampreeth004)](https://github.com/Sampreeth004/nfs-carbon-recomp) | Static recompilation of the Xbox 360 game via ReXGlue with debug Android APKs. | [Sampreeth004](https://github.com/Sampreeth004) |
| [Need for Speed: Most Wanted (2005, Xbox 360)](https://github.com/madelrandel-blip/NFSMW-Recompiled) | Native recompilation of the Xbox 360 version on ReXGlue with an Android release APK. | [madelrandel-blip](https://github.com/madelrandel-blip) |
| [Real Steel](https://github.com/tokeneffortports/ReCompiledSteel) | Native port for Windows, Linux and Android with a Vulkan renderer, online play and mods. | [tokeneffortports](https://github.com/tokeneffortports) |
| [Skate 3](https://github.com/Buku313/Skate3-Mobile) | Native ARM64 recompilation with Vulkan rendering; install one APK and select your own ISO. | [Buku313](https://github.com/Buku313) |
| [Skate 3 (Android shell)](https://github.com/andrewnakas/skate3-android) | App shell around the Skate 3 recompilation with APK releases; bring your own disc image. | [andrewnakas](https://github.com/andrewnakas) |
| [Sonic Free Riders](https://github.com/YuutaTsubasa/Free-Riders-Recompiled) | Static recompilation for Windows, Linux and Android with controller and keyboard support and custom VRM avatars. | [YuutaTsubasa](https://github.com/YuutaTsubasa) |
| [Sonic Unleashed](https://github.com/SansNope/UnleashedRecomp-Android) | Unofficial Android port of Unleashed Recompiled with APK releases. | [SansNope](https://github.com/SansNope) |
| [WWE SmackDown vs. Raw 2011](https://github.com/KaikoClanworth1/wwe-svr2011-pc) | Native port with an Android APK that has rearrangeable on-screen controls. | [KaikoClanworth1](https://github.com/KaikoClanworth1) |

---

## Original Xbox, PlayStation, PSP & PC Recompilations

Static recompilations of original Xbox, PlayStation, PSP and x86 PC games.

| Game | Description | Author |
|------|-------------|--------|
| [Black (Xbox)](https://github.com/RanggaCasper/Black-Android) | Native Android port of the Xbox game with touch controls, gyroscope aiming and controller support. | [RanggaCasper](https://github.com/RanggaCasper) |
| [Buffy the Vampire Slayer: Chaos Bleeds](https://github.com/KaikoClanworth1/buffy-chaos-bleeds-pc) | Native port of the Xbox game for Windows with an Android APK; bring your own disc. | [KaikoClanworth1](https://github.com/KaikoClanworth1) |
| [Burnout 3: Takedown](https://github.com/xenophobentx/takedawn) | Static recompilation for desktop, Steam Deck and Android handhelds with touch controls. | [xenophobentx](https://github.com/xenophobentx) |
| [Call of Duty 1.5](https://github.com/Dr3amyBerry/callofrecomp) | Experimental static recompilation of the PC game for Android; bring your own original files. | [Dr3amyBerry](https://github.com/Dr3amyBerry) |
| [Crash Bandicoot](https://github.com/Matteo842/CrashBandicoot-Launcher) | Static recompilation of the 1996 PS1 original with widescreen, high frame rates and a native Android build; no game assets included. | [Matteo842](https://github.com/Matteo842) |
| [God of War: Ghost of Sparta](https://github.com/arnaldolima1/gow-ghost-of-sparta-pc) | PSP static recompilation on PortableKit with Vulkan and an Android arm64 APK. | [arnaldolima1](https://github.com/arnaldolima1) |
| [GTA: Liberty City Stories](https://github.com/codepdbh/PSPRecomp-LCS-Android) | Beta native Android port based on PSPRecomp static recompilation; no game data included. | [codepdbh](https://github.com/codepdbh) |
| [GTA: Vice City Stories](https://github.com/codepdbh/PSPRecomp-VCS-Android) | Experimental Android arm64 port with Vulkan rendering, widescreen and a low-end 30 FPS mode. | [codepdbh](https://github.com/codepdbh) |
| [Jet Set Radio Future](https://github.com/JuMatt/JetSetRadioFuture-Unleashed) | Statically recompiled Jet Set Radio Future for desktop, Android and Apple devices. | [JuMatt](https://github.com/JuMatt) |
| [Monster Hunter Portable 3rd HD Ver.](https://github.com/TeamGDB/Yakumo) | Static recompilation of the PSP game running on a reimplementation of the PSP system software, with Android APKs. | [TeamGDB](https://github.com/TeamGDB) |
| [Mortal Kombat: Shaolin Monks](https://github.com/RanggaCasper/ShaolinMonks-Android) | Unofficial Android arm64 port of the Xbox game via XboxXBERecomp with Vulkan rendering. | [RanggaCasper](https://github.com/RanggaCasper) |
| [Need for Speed III: Hot Pursuit](https://github.com/ZloiKILLER/nfs3recompiled-android) | Recompiled PC port of the 1998 game running natively on 64-bit ARM Android phones. | [ZloiKILLER](https://github.com/ZloiKILLER) |
| [Need for Speed III: Hot Pursuit (Android Evolved)](https://github.com/codepdbh/NFS3-HP-AndroidEvolved) | Native arm64 community port based on motor-dev/nfs-recompiled. | [codepdbh](https://github.com/codepdbh) |
| [Need for Speed: Most Wanted (2005, PC recomp)](https://github.com/codepdbh/nfsmwpc-recompiled) | Static recompilation of the PC version for Windows and Android arm64 and armv7. | [codepdbh](https://github.com/codepdbh) |
| [Need for Speed: Most Wanted (2005, PC)](https://github.com/codepdbh/nfsmw-android) | Need for Speed: Most Wanted (2005) for Android ARM64 with APK releases. | [codepdbh](https://github.com/codepdbh) |
| [Need for Speed: Underground](https://github.com/codepdbh/nfsu1-recompiled) | Static recompilation for Windows and Android; requires your own copy of the game. | [codepdbh](https://github.com/codepdbh) |
| [Need for Speed: Underground 2](https://github.com/codepdbh/nfsu2-recompiled) | Static recompilation of SPEED2.EXE with Android arm64 and armv7 APKs. | [codepdbh](https://github.com/codepdbh) |
| [Prince of Persia: The Sands of Time (Xbox)](https://github.com/FulGerNet/rePOP) | Static recompilation of the Xbox builds to Windows and an Android app, with device validation in progress. | [FulGerNet](https://github.com/FulGerNet) |
| [Road Trip (Choro Q HG 2)](https://github.com/silentsudin/RoadTripAdventure-recomp) | PS2 static recompilation for Windows, macOS and Android with HD texture packs and a second-screen map. | [silentsudin](https://github.com/silentsudin) |
| [WHITE ALBUM2](https://github.com/dorakyuraduang/whitealbum2-Android) | Shared static recompilation project for Windows x64 and Android ARM64. | [dorakyuraduang](https://github.com/dorakyuraduang) |

---

## Handheld & 16-Bit Recompilations

Recompilations, recreations and ports of Game Boy, Game Boy Advance, SNES and other handheld or 16-bit games.

| Game | Description | Author |
|------|-------------|--------|
| [Apotris](https://github.com/SanGraphic/Apotris-Android) | Unofficial native Android port of the GBA-style block game, built from the arm64 Linux version. | [SanGraphic](https://github.com/SanGraphic) |
| [Final Fantasy Tactics Advance](https://github.com/Jorge262007/FFTARecomp) | Recompilation from your own ROM with an Android arm64 APK in releases. | [Jorge262007](https://github.com/Jorge262007) |
| [Final Fantasy Tactics Advance (gbarecomp)](https://github.com/james2doyle/ffta-recomp) | Static recompilation on the gbarecomp framework for Linux, Windows, Android and Steam Deck. | [james2doyle](https://github.com/james2doyle) |
| [Fire Emblem: The Sacred Stones](https://github.com/Lordingard/SacredStonesRecomp) | Playable Windows and Android arm64 recompilation. | [Lordingard](https://github.com/Lordingard) |
| [International Superstar Soccer Deluxe](https://github.com/sergiomanzur/issd-native) | Beta native recompilation of the SNES game with an Android APK. | [sergiomanzur](https://github.com/sergiomanzur) |
| [Knuckles' Chaotix](https://github.com/YuutaTsubasa/ChaotixRecompiled) | Static recompilation of the 32X game for Windows, Linux, macOS and Android with true widescreen. | [YuutaTsubasa](https://github.com/YuutaTsubasa) |
| [The Legend of Zelda II](https://github.com/troyedwardsjr/z2rs) | Clean-room reconstruction in Rust, checked frame by frame against the ROM, running on desktop, browser and Android. | [troyedwardsjr](https://github.com/troyedwardsjr) |
| [The Legend of Zelda: Oracle of Ages (Godot)](https://github.com/SHOEGAZEssb/ooa-godot) | In-progress Godot and C# reconstruction based on the disassembly with an Android arm64 APK. | [SHOEGAZEssb](https://github.com/SHOEGAZEssb) |
| [MOTHER 3](https://github.com/josiahg2502-glitch/Mother3Recomp) | Recompilation for Windows, Linux and Android with fan translation patch support. | [josiahg2502-glitch](https://github.com/josiahg2502-glitch) |
| [Pokémon Emerald](https://github.com/mstan/EmeraldRecomp) | Static recompilation on gbarecomp with an Android arm64 APK in releases. | [mstan](https://github.com/mstan) |
| [Pokémon Gold, Silver and Crystal (Gen2Recomped)](https://github.com/UNDERdecoded/Gen2Recomped) | Gen 2 recreation forked from Gen1Recomp with dual-screen support and Android APKs. | [UNDERdecoded](https://github.com/UNDERdecoded) |
| [Pokémon Red, Blue, Yellow, Gold, Silver, Crystal and more](https://github.com/bryanthaboi/gen1recomp) | Lua and LOVE2D recreation of Generations 1 to 3 built from a ROM you supply, with Android APKs in releases. | [bryanthaboi](https://github.com/bryanthaboi) |
| [Resident Evil Gaiden](https://github.com/sergiomanzur/regaiden-recomp) | Native recompilation of the Game Boy Color game with widescreen, dynamic lighting and an Android APK. | [sergiomanzur](https://github.com/sergiomanzur) |
| [Super Mario Advance 3: Yoshi's Island](https://github.com/Edwin2929/sma3-recomp-android.) | Experimental gbarecomp-based recompilation for Android ARM64 with an APK in releases. | [Edwin2929](https://github.com/Edwin2929) |
| [Super Mario Land 2: 6 Golden Coins](https://github.com/mstan/SuperMarioLand2Recomp) | Static recompilation with adaptive widescreen and an Android arm64 APK. | [mstan](https://github.com/mstan) |
| [Tiny Toon Adventures: Buster Busts Loose!](https://github.com/Darhkfox/BusterBustsLoose) | Port of the SNES game with true widescreen and an Android APK. | [Darhkfox](https://github.com/Darhkfox) |
| [Wario Land: Super Mario Land 3](https://github.com/GABRIELNNK/Bigodao) | Static recompilation study with native widescreen and an arm64 Android APK. | [GABRIELNNK](https://github.com/GABRIELNNK) |
| [WarioWare: Twisted!](https://github.com/mstan/WarioWareTwistedRecomp) | Static recompilation with Windows and Android gyro support. | [mstan](https://github.com/mstan) |

---

## Games on Their Own Runtimes & Launchers

Ports that wrap a game's own runtime (Unity, FNA, GameMaker, Godot) or ship a launcher that imports your legally owned PC files.

| Game | Description | Author |
|------|-------------|--------|
| [AM2R: Another Metroid 2 Remake](https://github.com/am2r-android/AM2R-Autopatcher-Android) | Android app that patches your AM2R 1.1 zip into a native Android build. | [am2r-android](https://github.com/am2r-android) |
| [The Binding of Isaac](https://github.com/whylurking/IsaacRecomp) | Native C++ recompilation of the Flash-era game with an Android APK; requires the original game from Steam. | [whylurking](https://github.com/whylurking) |
| [Celeste](https://github.com/BelmanteGu/CelesteAndroid) | Native Android port of Celeste that runs your own PC copy on .NET, FNA, SDL3, Vulkan and FMOD. | [BelmanteGu](https://github.com/BelmanteGu) |
| [GameMaker games (Butterscotch)](https://github.com/ButterscotchRunner/Butterscotch) | Open-source re-implementation of the GameMaker: Studio runner with Android builds from CI. | [ButterscotchRunner](https://github.com/ButterscotchRunner) |
| [Hollow Knight](https://github.com/igawa6/dualsouls) | Native Android port of Hollow Knight for the AYN Thor dual-screen handheld, provisioned from your own copy. | [igawa6](https://github.com/igawa6) |
| [Hollow Knight: Silksong](https://github.com/jakobkhansen/SilksongAndroid) | Dual-screen Android port with optional Steam integration for game files and cloud saves. | [jakobkhansen](https://github.com/jakobkhansen) |
| [Plants vs. Zombies](https://github.com/wszqkzqk/PvZ-Portable) | Cross-platform reimplementation of the GOTY edition with an Android arm64 APK. | [wszqkzqk](https://github.com/wszqkzqk) |
| [Slay the Spire 2 (Mobile Launcher)](https://github.com/ModinMobileSTS/Sts2MobileLauncher) | Experimental Android launcher that imports your own PC files, with mod support and mobile controls. | [ModinMobileSTS](https://github.com/ModinMobileSTS) |
| [Slay the Spire 2 (StS2-Launcher)](https://github.com/Ekyso/StS2-Launcher) | Unofficial Android launcher built on a custom Godot 4.5.1 .NET engine. | [Ekyso](https://github.com/Ekyso) |
| [Starbound (OpenStarbound Mobile)](https://github.com/RohanBhattacharyya/oSBM) | OpenStarbound port to mobile devices; you must own Starbound. | [RohanBhattacharyya](https://github.com/RohanBhattacharyya) |
| [Stardew Valley](https://github.com/Ekyso/Cinderbox) | Native launcher that runs Desktop Stardew Valley on Android. | [Ekyso](https://github.com/Ekyso) |
| [Visual novels (CPyMO)](https://github.com/Strrationalism/CPyMO) | C implementation of the PyMO AVG engine for running owned visual novels, with an Android build. | [Strrationalism](https://github.com/Strrationalism) |
| [Zuma Deluxe](https://github.com/abduznik/ZumaPortable) | Open-source SDL2 port of Zuma Deluxe for Android, Windows and Linux. | [abduznik](https://github.com/abduznik) |

---

## Classic Ports (Low Activity)

Older ports that still work but have not been updated for over a year. They are kept because many of them are still the only native Android option.

| Game | Description | Author |
|------|-------------|--------|
| [Brogue](https://github.com/bilgincoskun/brogue-android-port) | Brogue Android port. | [bilgincoskun](https://github.com/bilgincoskun) |
| [Fallout](https://github.com/alexbatalov/fallout1-ce) | Fully working re-implementation of Fallout with engine bug fixes and an Android APK in releases. | [alexbatalov](https://github.com/alexbatalov) |
| [Fallout 2](https://github.com/alexbatalov/fallout2-ce) | Fully working re-implementation of Fallout 2 with engine bug fixes and an Android APK in releases. | [alexbatalov](https://github.com/alexbatalov) |
| [Gish](https://github.com/EXL/Gish) | Port of Gish using SDL2, OpenAL, Ogg Vorbis and GL4ES. | [EXL](https://github.com/EXL) |
| [Ken's Labyrinth](https://github.com/EXL/KenLab3d) | Port of Ken's Labyrinth using SDL2. | [EXL](https://github.com/EXL) |
| [The Legend of Zelda: A Link to the Past (zelda3 Android)](https://github.com/Waterdish/zelda3-android) | Android port of the zelda3 reimplementation with APK releases. | [Waterdish](https://github.com/Waterdish) |
| [Majora's Mask (2 Ship 2 Harkinian)](https://github.com/Waterdish/2ship2harkinian-Android) | Android port of 2 Ship 2 Harkinian with APK releases. | [Waterdish](https://github.com/Waterdish) |
| [Marathon](https://github.com/daniele-rapagnani/alephone-android) | Port of the Aleph One Marathon engine to Android. | [daniele-rapagnani](https://github.com/daniele-rapagnani) |
| [Ocarina of Time (Ship of Harkinian)](https://github.com/Waterdish/Shipwright-Android) | Android port of Ship of Harkinian with APK releases; bring your own ROM. | [Waterdish](https://github.com/Waterdish) |
| [OpenTTD](https://github.com/pelya/openttd-android) | OpenTTD for Android. | [pelya](https://github.com/pelya) |
| [OpenXcom](https://github.com/sfalexrog/openxcom-android) | Android Studio project for compiling OpenXcom. | [sfalexrog](https://github.com/sfalexrog) |
| [Serious Sam: The Second Encounter](https://github.com/aarcangeli/Serious-Sam-Android) | Port of Serious Sam Classic: The Second Encounter to Android. | [aarcangeli](https://github.com/aarcangeli) |
| [Space Cadet Pinball](https://github.com/iscle/SpaceCadetPinball) | Android port of 3D Pinball for Windows - Space Cadet. | [iscle](https://github.com/iscle) |
| [Spout](https://github.com/EXL/Spout) | Port of Spout using OpenGL ES. | [EXL](https://github.com/EXL) |
| [Super Mario 64](https://github.com/VDavid003/sm64-port-android-base) | Base project for building the sm64-port for Android. | [VDavid003](https://github.com/VDavid003) |
| [Theme Hospital](https://github.com/alanwoolley/CorsixTH-Android) | Port of CorsixTH to Android. | [alanwoolley](https://github.com/alanwoolley) |
| [Warcraft II](https://github.com/blairisme/warcraft) | Warcraft II port for Android, Windows and macOS. | [blairisme](https://github.com/blairisme) |

---

## Tools & Frameworks

Frameworks, runtimes and launchers that port authors and players use.

| Project | Description | Author |
|------|-------------|--------|
| [Commander Genius (SDL for Android)](https://github.com/pelya/commandergenius) | Port of the SDL library and several games to Android, used as a base by many older Android game ports. | [pelya](https://github.com/pelya) |
| [GBARecomp](https://github.com/mstan/gbarecomp) | Game Boy Advance static recompiler used by several Android recomp ports. | [mstan](https://github.com/mstan) |
| [gl4es](https://github.com/ptitSeb/gl4es) | OpenGL 2.1 and 1.5 to OpenGL ES translation library that supports Android. | [ptitSeb](https://github.com/ptitSeb) |
| [N64: Recompiled](https://github.com/N64Recomp/N64Recomp) | Tool to statically recompile N64 games into native executables. | [N64Recomp](https://github.com/N64Recomp) |
| [N64ModernRuntime](https://github.com/N64Recomp/N64ModernRuntime) | Runtime for traditional ports and recompilations of N64 games. | [N64Recomp](https://github.com/N64Recomp) |
| [Obtainium Android Recomps](https://github.com/heyalmoo/Obtainium-Android-Recomps) | Obtainium import pack for native Android ports and recompilations with automatic updates. | [heyalmoo](https://github.com/heyalmoo) |
| [Ports Launcher](https://github.com/Nyaldee/Ports-Launcher) | Library manager and installer for unofficial native game ports and recomps on Windows, Linux and Android. | [Nyaldee](https://github.com/Nyaldee) |
| [ReXGlue SDK](https://github.com/rexglue/rexglue-sdk) | Xbox 360 recompilation runtime and toolkit behind many Android builds listed here. | [rexglue](https://github.com/rexglue) |
| [RT64](https://github.com/rt64/rt64) | N64 renderer for emulators and native ports, used by the N64 recompilations. | [rt64](https://github.com/rt64) |
| [SDL](https://github.com/libsdl-org/SDL) | Cross-platform library with official Android support that many of the ports here build on. | [libsdl-org](https://github.com/libsdl-org) |
| [WiiCompiled](https://github.com/patchzyy/Wiicompiled) | Wii static recompilation project behind several Mario Kart Wii and Wii ports. | [patchzyy](https://github.com/patchzyy) |
| [XboxXBERecomp](https://github.com/TGP482/XboxXBERecomp) | Tool for statically recompiling original Xbox games into native executables. | [TGP482](https://github.com/TGP482) |
| [XenonRecomp](https://github.com/hedge-dev/XenonRecomp) | Tool for recompiling Xbox 360 games to native executables. | [hedge-dev](https://github.com/hedge-dev) |

---

## Related Lists

Other lists that are worth a look.

| List | Description | Author |
|------|-------------|--------|
| [awesome-android-games](https://github.com/quantavil/awesome-android-games) | Directory of open-source Android games, engines and codebases. | [quantavil](https://github.com/quantavil) |
| [awesome-decomp-games](https://github.com/SubmitGame/awesome-decomp-games) | Rated, auto-refreshed list of decompiled, recompiled and reverse-engineered games. | [SubmitGame](https://github.com/SubmitGame) |
| [awesome-unofficial-pc-ports](https://github.com/Sebastrion/awesome-unofficial-pc-ports) | Curated list of unofficial PC ports. | [Sebastrion](https://github.com/Sebastrion) |
| [awesome-x360-recomps](https://github.com/abduznik/awesome-x360-recomps) | Curated list of Xbox 360 game recompilation projects. | [abduznik](https://github.com/abduznik) |
| [openportsgames](https://github.com/Kymie131/openportsgames) | Catalog of native PC and Android ports of classic games. | [Kymie131](https://github.com/Kymie131) |

---

## Contributing

Contributions welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

---

## Disclaimer

This list only links to community projects. It does not host or distribute games, game data, BIOS files or binaries, and it is not affiliated with any publisher or developer. Make sure you own the games you play and follow the laws and licenses that apply to you. Install APKs only from the repositories linked here, because third-party mirrors of these projects are a common way to spread malware.

---

## Credits

Thanks to everyone who ports games to Android and shares the source. Please support their work: star the repos, report bugs and spread the word!

- [elasota](https://github.com/elasota)
- [Pyrdacor](https://github.com/Pyrdacor)
- [DifferentNet](https://github.com/DifferentNet)
- [openblack](https://github.com/openblack)
- [bvschaik](https://github.com/bvschaik)
- [Keriew](https://github.com/Keriew)
- [Link4Electronics](https://github.com/Link4Electronics)
- [scummvm](https://github.com/scummvm)
- [pablocpas](https://github.com/pablocpas)
- [molotovgit](https://github.com/molotovgit)
- [dk8827](https://github.com/dk8827)
- [Cesarus85](https://github.com/Cesarus85)
- [Velaron](https://github.com/Velaron)
- [diasurgical](https://github.com/diasurgical)
- [glKarin](https://github.com/glKarin)
- [sandstranger](https://github.com/sandstranger)
- [adamkulik](https://github.com/adamkulik)
- [Try](https://github.com/Try)
- [FWGS](https://github.com/FWGS)
- [ihhub](https://github.com/ihhub)
- [vcmi](https://github.com/vcmi)
- [ja2-stracciatella](https://github.com/ja2-stracciatella)
- [AlisterT](https://github.com/AlisterT)
- [deathkiller](https://github.com/deathkiller)
- [youkaicountry](https://github.com/youkaicountry)
- [isledecomp](https://github.com/isledecomp)
- [LBALab](https://github.com/LBALab)
- [nautilusbits](https://github.com/nautilusbits)
- [ds17f](https://github.com/ds17f)
- [OpenEnroth](https://github.com/OpenEnroth)
- [Andiweli](https://github.com/Andiweli)
- [zaps166](https://github.com/zaps166)
- [gurrhack](https://github.com/gurrhack)
- [sdlpal](https://github.com/sdlpal)
- [missingno7](https://github.com/missingno7)
- [themuffinator](https://github.com/themuffinator)
- [skynettx](https://github.com/skynettx)
- [lhr0909](https://github.com/lhr0909)
- [h4mu](https://github.com/h4mu)
- [OpenRCT2](https://github.com/OpenRCT2)
- [EasyRPG](https://github.com/EasyRPG)
- [konovalov-aleks](https://github.com/konovalov-aleks)
- [Eukaryot](https://github.com/Eukaryot)
- [thegreatbbd94-ux](https://github.com/thegreatbbd94-ux)
- [yancharkin](https://github.com/yancharkin)
- [imjustadudegamer](https://github.com/imjustadudegamer)
- [raposomiguel50](https://github.com/raposomiguel50)
- [XProger](https://github.com/XProger)
- [andyvand](https://github.com/andyvand)
- [synthwave-pixel](https://github.com/synthwave-pixel)
- [exult](https://github.com/exult)
- [FatalDecomp](https://github.com/FatalDecomp)
- [ReflectionHLE](https://github.com/ReflectionHLE)
- [jjmhalew](https://github.com/jjmhalew)
- [zwaetschge](https://github.com/zwaetschge)
- [igawa6](https://github.com/igawa6)
- [FulGerNet](https://github.com/FulGerNet)
- [ChupathingyCE](https://github.com/ChupathingyCE)
- [OpenCommunityEdition](https://github.com/OpenCommunityEdition)
- [nathanialf](https://github.com/nathanialf)
- [MatyMeatBoy](https://github.com/MatyMeatBoy)
- [DoutorRaposo](https://github.com/DoutorRaposo)
- [999sian](https://github.com/999sian)
- [TwilitRealm](https://github.com/TwilitRealm)
- [linkzenic](https://github.com/linkzenic)
- [izzy2lost](https://github.com/izzy2lost)
- [mariopartyrd](https://github.com/mariopartyrd)
- [zeranemesis](https://github.com/zeranemesis)
- [iirg4x](https://github.com/iirg4x)
- [Odrannnn](https://github.com/Odrannnn)
- [kirby-letsgo](https://github.com/kirby-letsgo)
- [thibautbus](https://github.com/thibautbus)
- [SSunnKing](https://github.com/SSunnKing)
- [SlickAmogus](https://github.com/SlickAmogus)
- [RSDKModding](https://github.com/RSDKModding)
- [ZinexDa](https://github.com/ZinexDa)
- [pakompom](https://github.com/pakompom)
- [HarbourMasters](https://github.com/HarbourMasters)
- [OpenPort-Labs](https://github.com/OpenPort-Labs)
- [JRickey](https://github.com/JRickey)
- [CNTianQi233](https://github.com/CNTianQi233)
- [alondero](https://github.com/alondero)
- [AurelioB](https://github.com/AurelioB)
- [wootbeer](https://github.com/wootbeer)
- [codepdbh](https://github.com/codepdbh)
- [ThatGuyMcd](https://github.com/ThatGuyMcd)
- [deivid22srk](https://github.com/deivid22srk)
- [ogdanimal](https://github.com/ogdanimal)
- [MikeSemicolonD](https://github.com/MikeSemicolonD)
- [n0madic](https://github.com/n0madic)
- [dyzz](https://github.com/dyzz)
- [Nycolazs](https://github.com/Nycolazs)
- [chrissotraidis](https://github.com/chrissotraidis)
- [ZeldaWWHDRecomp](https://github.com/ZeldaWWHDRecomp)
- [GreenNaugahyde](https://github.com/GreenNaugahyde)
- [dorPXP](https://github.com/dorPXP)
- [aabrole](https://github.com/aabrole)
- [WitherBlitz](https://github.com/WitherBlitz)
- [ClickingMaster](https://github.com/ClickingMaster)
- [BelmanteGu](https://github.com/BelmanteGu)
- [PauloUbirajara](https://github.com/PauloUbirajara)
- [shipa-2](https://github.com/shipa-2)
- [dfdx047](https://github.com/dfdx047)
- [birabittoh](https://github.com/birabittoh)
- [arcanite24](https://github.com/arcanite24)
- [Gabrick75](https://github.com/Gabrick75)
- [freefrank](https://github.com/freefrank)
- [Masterllgod](https://github.com/Masterllgod)
- [Sampreeth004](https://github.com/Sampreeth004)
- [madelrandel-blip](https://github.com/madelrandel-blip)
- [tokeneffortports](https://github.com/tokeneffortports)
- [Buku313](https://github.com/Buku313)
- [andrewnakas](https://github.com/andrewnakas)
- [YuutaTsubasa](https://github.com/YuutaTsubasa)
- [SansNope](https://github.com/SansNope)
- [KaikoClanworth1](https://github.com/KaikoClanworth1)
- [RanggaCasper](https://github.com/RanggaCasper)
- [xenophobentx](https://github.com/xenophobentx)
- [Dr3amyBerry](https://github.com/Dr3amyBerry)
- [Matteo842](https://github.com/Matteo842)
- [arnaldolima1](https://github.com/arnaldolima1)
- [JuMatt](https://github.com/JuMatt)
- [TeamGDB](https://github.com/TeamGDB)
- [ZloiKILLER](https://github.com/ZloiKILLER)
- [silentsudin](https://github.com/silentsudin)
- [dorakyuraduang](https://github.com/dorakyuraduang)
- [SanGraphic](https://github.com/SanGraphic)
- [Jorge262007](https://github.com/Jorge262007)
- [james2doyle](https://github.com/james2doyle)
- [Lordingard](https://github.com/Lordingard)
- [sergiomanzur](https://github.com/sergiomanzur)
- [troyedwardsjr](https://github.com/troyedwardsjr)
- [SHOEGAZEssb](https://github.com/SHOEGAZEssb)
- [josiahg2502-glitch](https://github.com/josiahg2502-glitch)
- [mstan](https://github.com/mstan)
- [UNDERdecoded](https://github.com/UNDERdecoded)
- [bryanthaboi](https://github.com/bryanthaboi)
- [Edwin2929](https://github.com/Edwin2929)
- [Darhkfox](https://github.com/Darhkfox)
- [GABRIELNNK](https://github.com/GABRIELNNK)
- [am2r-android](https://github.com/am2r-android)
- [whylurking](https://github.com/whylurking)
- [ButterscotchRunner](https://github.com/ButterscotchRunner)
- [jakobkhansen](https://github.com/jakobkhansen)
- [wszqkzqk](https://github.com/wszqkzqk)
- [ModinMobileSTS](https://github.com/ModinMobileSTS)
- [Ekyso](https://github.com/Ekyso)
- [RohanBhattacharyya](https://github.com/RohanBhattacharyya)
- [Strrationalism](https://github.com/Strrationalism)
- [abduznik](https://github.com/abduznik)
- [bilgincoskun](https://github.com/bilgincoskun)
- [alexbatalov](https://github.com/alexbatalov)
- [EXL](https://github.com/EXL)
- [Waterdish](https://github.com/Waterdish)
- [daniele-rapagnani](https://github.com/daniele-rapagnani)
- [pelya](https://github.com/pelya)
- [sfalexrog](https://github.com/sfalexrog)
- [aarcangeli](https://github.com/aarcangeli)
- [iscle](https://github.com/iscle)
- [VDavid003](https://github.com/VDavid003)
- [alanwoolley](https://github.com/alanwoolley)
- [blairisme](https://github.com/blairisme)
- [ptitSeb](https://github.com/ptitSeb)
- [N64Recomp](https://github.com/N64Recomp)
- [heyalmoo](https://github.com/heyalmoo)
- [Nyaldee](https://github.com/Nyaldee)
- [rexglue](https://github.com/rexglue)
- [rt64](https://github.com/rt64)
- [libsdl-org](https://github.com/libsdl-org)
- [patchzyy](https://github.com/patchzyy)
- [TGP482](https://github.com/TGP482)
- [hedge-dev](https://github.com/hedge-dev)
- [quantavil](https://github.com/quantavil)
- [SubmitGame](https://github.com/SubmitGame)
- [Sebastrion](https://github.com/Sebastrion)
- [Kymie131](https://github.com/Kymie131)
