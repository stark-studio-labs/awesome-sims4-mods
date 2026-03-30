<div align="center">

<!-- Banner will be added once generated -->
<img src="assets/banner.png" alt="awesome-sims4-mods banner" width="100%">

# 🎮 awesome-sims4-mods

**The definitive Sims 4 mod directory — curated, reviewed, and compatibility-tracked.**

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
![Last Updated](https://img.shields.io/badge/updated-March_2026-brightgreen)
![Mods Listed](https://img.shields.io/badge/mods-25+-blue)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

*Maintained by [Stark Studio Labs](https://github.com/stark-studio-labs)*

---

</div>

## 🌐 Stark Labs Ecosystem

> Everything we build for The Sims 4 modding community — open source, interconnected, and community-driven.

| Repo | What It Does | Status |
|------|-------------|--------|
| 📚 **[awesome-sims4-mods](https://github.com/stark-studio-labs/awesome-sims4-mods)** | Curated mod directory with compatibility tracking | ![Active](https://img.shields.io/badge/-active-brightgreen) |
| 🧱 **[sims4-stark-framework](https://github.com/stark-studio-labs/sims4-stark-framework)** | Modern typed modding framework (replaces S4CL patterns) | ![Active](https://img.shields.io/badge/-active-brightgreen) |
| 🔧 **[sims4-stark-devkit](https://github.com/stark-studio-labs/sims4-stark-devkit)** | CLI toolkit — decompile, package, scaffold, test | ![Active](https://img.shields.io/badge/-active-brightgreen) |
| 📦 **[sims4-mod-manager](https://github.com/stark-studio-labs/sims4-mod-manager)** | Scan, organize, and detect conflicts in your mod collection | ![Alpha](https://img.shields.io/badge/-alpha-orange) |
| 🎨 **[sims4-mod-builder](https://github.com/stark-studio-labs/sims4-mod-builder)** | Visual mod creation tool — no XML knowledge needed | ![In Dev](https://img.shields.io/badge/-in%20dev-yellow) |
| 🔬 **[sims4-mod-revival](https://github.com/stark-studio-labs/sims4-mod-revival)** | Decompile and revive abandoned community mods | ![Active](https://img.shields.io/badge/-active-brightgreen) |
| 💰 **[sims4-economy-sim](https://github.com/stark-studio-labs/sims4-economy-sim)** | Banking, bills, jobs, and stock market overhaul mod | ![Pre-Alpha](https://img.shields.io/badge/-pre--alpha-red) |

---

## 🔥 Stark Labs Originals

> Coming Soon — Original mods built by Stark Studio Labs. Stay tuned.

---

## 📖 Table of Contents

- [🌐 Stark Labs Ecosystem](#-stark-labs-ecosystem)
- [🚀 Getting Started — New to Mods?](#-getting-started--new-to-mods)
- [🔥 Stark Labs Originals](#-stark-labs-originals)
- [🏆 Essential Mods](#-essential-mods)
- [🎮 Gameplay Overhauls](#-gameplay-overhauls)
- [🏥 Realism Suite](#-realism-suite)
- [💀 Drama & Storytelling](#-drama--storytelling)
- [⚡ Quality of Life](#-quality-of-life)
- [🌟 Rising Stars](#-rising-stars)
- [🔧 Modding Tools & Frameworks](#-modding-tools--frameworks)
- [📊 Compatibility Tracker](#-compatibility-tracker)
- [🤝 Contributing](#-contributing)

---

## 🚀 Getting Started — New to Mods?

Never modded The Sims 4 before? You're in the right place. This section covers everything from zero.

---

### What Is a Mod?

A **mod** (short for modification) is a file made by the community that changes or adds to the game. Mods can:

- Fix bugs EA hasn't patched
- Add new gameplay systems (careers, emotions, relationships)
- Change how existing mechanics work
- Add new objects, hairstyles, and clothing (called **CC** — Custom Content)
- Improve the game's UI and performance

Mods come as `.package` files or `.ts4script` files. Both go in the same folder.

---

### Step 1: Find Your Mods Folder

The Mods folder is where all your mod files live. Navigate to:

**Windows:**
```
Documents\Electronic Arts\The Sims 4\Mods\
```

**Mac:**
```
Documents/Electronic Arts/The Sims 4/Mods/
```

> **Note:** If you've never opened the game, this folder may not exist yet. Launch the game once, then close it — the folder will be created automatically.

You can organize mods into **subfolders** inside `Mods/`. The game reads up to **5 folder levels deep**, so feel free to create folders like `Mods/Gameplay/` or `Mods/CC/Clothing/`.

---

### Step 2: Download and Install a Mod

1. Download the mod file from the creator's page (usually a `.zip` or `.rar` archive)
2. Extract the archive — you'll find one or more `.package` and/or `.ts4script` files inside
3. Move those files into your `Mods/` folder (or a subfolder inside it)
4. Done — no installation wizard needed

> **Never put `.zip` files directly into the Mods folder.** The game can't read compressed archives. Always extract first.

---

### Step 3: Enable Mods in Game Settings

Mods are **disabled by default**. You must turn them on once:

1. Launch The Sims 4
2. Go to **Game Options** (the `...` menu in the top right) → **Other**
3. Check **"Enable Custom Content and Mods"**
4. Check **"Enable Script Mods and Custom Content"** *(required for `.ts4script` files)*
5. Click **Apply Changes** — the game will restart

You only need to do this once. After a major game patch, sometimes these settings get reset — if your mods stop working after an update, check here first.

---

### Step 4: Verify Mods Are Loaded

After re-launching:

1. Go to **Game Options → Other**
2. Click **"Show Mod List"** — this lists every mod the game has detected
3. If a mod isn't showing, it either failed to load or isn't in the right folder

---

### Troubleshooting

**My game crashes on startup**

A mod is incompatible with the current game version — usually after an EA patch. Use this process:
1. Move all mods out of the folder temporarily
2. If the game launches, move mods back in batches of 10-20
3. The batch that causes the crash contains the broken mod
4. Use **Better Exceptions** (in the QoL list below) to identify exactly which file is broken

**A mod isn't working**

- Confirm the `.package` or `.ts4script` file is directly in `Mods/` or a subfolder (not still inside a `.zip`)
- Confirm script mods are enabled in Game Options
- Check if the mod requires another mod to work (called a **dependency** — usually XML Injector or a community library)
- Verify the mod is updated for the current game version

**Mods stopped working after an update**

EA patches frequently break mods. Creators usually update their mods within days of a patch. Check:
- The mod's original download page for an updated version
- [SimsVIP Broken/Updated Mods](https://simsvip.com/category/the-sims-4/broken-updated-mods/) for patch-by-patch status

**The game is running slowly**

- Too many mods (especially script mods) increases load time and can affect performance
- Remove mods you don't use
- Check that you're not accidentally running duplicate versions of the same mod

**How many mods is too many?**

There's no hard limit, but most players cap around 300-500 mods for stable performance. Script mods (`.ts4script`) have a larger performance impact than `.package` files — keep those to what you actually use.

---

> **Tip for beginners:** Start with 5-10 mods, get comfortable with the install process, then expand from there. The mods in the [Essential](#-essential-mods) section below are the best starting point.

---

## 🏆 Essential Mods

The mods every Sims 4 player should know about. These are the foundation.

| # | Mod | Creator | Description | Links |
|---|-----|---------|-------------|-------|
| 1 | **MC Command Center** | Deaderpool | Story progression, population control, money management, and deep game control. The most essential mod. | [Download](https://deaderpool-mccc.com/) |
| 2 | **Wicked Whims** | TURBODRIVER | Enhanced romance mechanics, attraction system, and adult content. Massive feature set. | [Download](https://turbodriver.itch.io/wickedwhims) |
| 3 | **Basemental Mods** | Basemental | Functional casinos, gambling, and vice-related content. Deep gameplay expansion. | [Download](https://basementalmods.com/) |
| 4 | **UI Cheats Extension** | Weerbesu | Click directly on UI elements to edit needs, skills, money, and more. Essential QoL. | [Download](https://weerbesu.tumblr.com/) |
| 5 | **More Columns in CAS** | Weerbesu | Adds extra columns to Create-a-Sim for easier browsing of CC and items. | [Download](https://weerbesu.tumblr.com/) |

## 🎮 Gameplay Overhauls

Mods that fundamentally change how the game plays.

| # | Mod | Creator | Description | Links |
|---|-----|---------|-------------|-------|
| 6 | **Slice of Life** | KawaiiStacie | Health module, beauty system, Myers-Briggs personalities, alcohol features, and more. | [Download](https://www.kawaii-stacie.com/) |
| 7 | **Meaningful Stories** | roBurky | Replaces random moodlets with emotionally coherent narratives based on traits and history. | [Download](https://roburky.itch.io/) |
| 8 | **Education Bundle** | KawaiiStacie | Expands school and education systems with new interactions and activities. | [Download](https://www.kawaii-stacie.com/) |
| 9 | **Simstagram** | KawaiiStacie | Social media platform — gain followers, build influence, post content. | [Download](https://www.kawaii-stacie.com/) |
| 10 | **Growing Pains** | Various | Preschool, parenting classes, youth centers, family traditions. Family-focused expansion. | [Download](https://modthesims.info/) |

## 🏥 Realism Suite

For players who want their Sims world to feel real.

| # | Mod | Creator | Description | Links |
|---|-----|---------|-------------|-------|
| 11 | **Private Practice** | SimRealist & roBurky | Full healthcare system — run private medical practices, diagnose patients, manage staff. | [Download](https://simrealist.itch.io/) |
| 12 | **SimFinancial** | adeepindigo | Complete banking — credit unions, loans, investments, credit cards, insurance, credit scores. | [Download](https://adeepindigomods.itch.io/) |
| 13 | **SNB Bills** | SimRealist | Realistic utilities: water, electricity, internet, property taxes, welfare, child support. 1.2M+ downloads. | [Download](https://www.curseforge.com/sims4/mods/snb-bills) |
| 14 | **Dental Care** | adeepindigo | Dental care system with appointments and hygiene tracking. | [Download](https://adeepindigomods.itch.io/) |
| 15 | **Realistic Childbirth** | PandaSama | Medical-accurate birth: natural delivery, cesarean sections, postpartum effects. | [Download](https://modthesims.info/) |

## 💀 Drama & Storytelling

For players who want chaos, narrative, and consequences.

| # | Mod | Creator | Description | Links |
|---|-----|---------|-------------|-------|
| 16 | **Life Tragedies** | Sacrificial Mods | Fatal illnesses, kidnapping, robberies, car accidents, bullying. Adjustable frequency. | [Download](https://www.sacrificialmods.com/) |
| 17 | **Road to Fame** | Sacrificial Mods | 5 fame tracks: Simstagram, Modeling, Acting, Singing, Dancing. Fans, paparazzi, offers. | [Download](https://www.sacrificialmods.com/) |
| 18 | **First Impressions** | Lumpinou | Realistic first-meeting opinions that affect friendships, rivalries, and romance. | [Download](https://lumpinou.tumblr.com/) |

## ⚡ Quality of Life

The mods that fix what EA didn't.

| # | Mod | Creator | Description | Links |
|---|-----|---------|-------------|-------|
| 19 | **XML Injector** | Scumbumbo / Triplis | Library mod required by many other mods. Enables simple XML-based modifications. | [Download](https://scumbumbomods.com/) |
| 20 | **Better Exceptions** | TwistedMexi | Error reporting and debugging. Shows exactly which mod caused a problem. | [Download](https://www.patreon.com/TwistedMexi) |
| 21 | **TOOL Mod** | TwistedMexi | Complete object positioning control — rotate, scale, and move ANY object anywhere. | [Download](https://www.patreon.com/TwistedMexi) |
| 22 | **Better BuildBuy** | TwistedMexi | Debug item access, color filtering, lighting editor. Essential for builders. | [Download](https://www.patreon.com/TwistedMexi) |
| 23 | **Simulation Lag Fix** | SrsLySims | Optimizes game timing, reduces AI idle behavior. 387K+ downloads. | [Download](https://www.curseforge.com/sims4/mods/simulation-lag-fix) |

## 🌟 Rising Stars

| # | Mod | Creator | Description | Links |
|---|-----|---------|-------------|-------|
| 24 | **More Career Opportunities** | KiaraSims4Mods | New careers: dentist, pet groomer, news anchor, ice cream manager, and more. | [Download](https://modthesims.info/) |
| 25 | **Personality Please** | Kuttoe | Personality trait overhaul — makes traits matter more in daily life and interactions. | [Download](https://kuttoe.itch.io/) |

---

## 🔧 Modding Tools & Frameworks

Want to create your own mods? Here's what you need.

| Tool | Language | Purpose | Link |
|------|----------|---------|------|
| **Sims 4 Studio (S4S)** | Desktop App | Primary editor for tuning, CAS, build/buy items | [Download](https://sims4studio.com/) |
| **S4TK (Sims 4 Toolkit)** | Node.js | Package file creation, reading, and editing | [GitHub](https://github.com/sims4toolkit) |
| **Sims4CommunityLibrary** | Python | API framework for mod developers | [GitHub](https://github.com/ColonolNutty/Sims4CommunityLibrary) |
| **s4pe (Package Editor)** | C# | Low-level .package file manipulation | [GitHub](https://github.com/s4ptacle/Sims4Tools) |
| **XML Injector** | XML | Simple tuning mods without scripting | [Download](https://scumbumbomods.com/) |
| **Blender + S4 Plugins** | 3D | Mesh modeling and CAS item creation | [Blender](https://www.blender.org/) |
| **MorphMaker** | Desktop App | Custom morphs for CAS items | [Download](https://sims4studio.com/) |
| **Stark Framework** | Python | Modern typed modding framework | [GitHub](https://github.com/stark-studio-labs/sims4-stark-framework) |
| **Stark DevKit** | Python CLI | Decompile, package, scaffold, test | [GitHub](https://github.com/stark-studio-labs/sims4-stark-devkit) |
| **Stark Mod Builder** | Electron + React | Visual mod creation (coming soon) | [GitHub](https://github.com/stark-studio-labs/sims4-mod-builder) |

### Development Approaches

- **XML Tuning** — Modify game data via XML files. Most common, no compilation needed.
- **Python Scripting** — Full scripts compiled to `.ts4script`. Python 3.7. Decompilers available for reverse-engineering.
- **3D Modeling** — Blender for meshes, Sims 4 Studio for recolors and retextures.
- **Package Editing** — Direct `.package` file manipulation for advanced modders.

---

## 📊 Compatibility Tracker

Mods can break after EA patches. Check these resources for the latest compatibility status:

| Resource | Description | Link |
|----------|-------------|------|
| **SimsVIP Broken/Updated Mods** | Updated after each patch with mod status | [Visit](https://simsvip.com/category/the-sims-4/broken-updated-mods/) |
| **Scarlet's Realm Mod List** | Daily updated compatibility tracker | [Visit](https://scarletsrealm.com/the-mod-list/) |
| **EA Forums** | Official broken mod threads | [Visit](https://forums.ea.com/) |

---

## 🤝 Contributing

Found a mod that should be on this list? Want to report a broken link?

1. Open an [issue](https://github.com/stark-studio-labs/awesome-sims4-mods/issues)
2. Or submit a pull request with your addition

Please follow the existing format and include: mod name, creator, description, and download link.

---

## 📜 License

[MIT](LICENSE) — Feel free to share and remix.

---

<div align="center">

**Built with 💚 by [Stark Studio Labs](https://github.com/stark-studio-labs)**

*Star this repo if you found it useful!*

</div>
