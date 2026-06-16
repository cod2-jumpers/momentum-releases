[![](https://utfs.io/f/nGnSqDveMsqxjGkT5ogVBUsFo4CyOfkcQiLY73XZznRTW1eH)](https://www.youtube.com/watch?v=qTgGRWU7M9I)

<p align="center">
  <img src="https://img.shields.io/github/downloads/cod2-jumpers/momentum-releases/total">
  <img src="https://img.shields.io/github/v/release/cod2-jumpers/momentum-releases">
  <img src="https://img.shields.io/github/release-date/cod2-jumpers/momentum-releases">
  <img src="https://img.shields.io/badge/VirusTotal-14%2F75-brightgreen?logo=virustotal">
</p>

# Momentum – Ingame CoDJumper HUD

Momentum is an advanced in-game training and analysis overlay for **Call of Duty 2** and **Call of Duty 4**, built for jumpers & speedrunners.

Created by **blaadje** & **duck**, Momentum focuses on:

- movement mastery
- jump consistency
- route planning
- replay analysis
- mapper utilities
- fully customizable HUD workflows

Designed to stay readable during gameplay, every tool is configurable, lightweight, and built around fast iteration while practicing or routing maps.

---

<p align="center">
  If you enjoy Momentum HUD, support future features, tools and updates ☕
</p>

<p align="center">
  <a href="https://www.buymeacoffee.com/momentumblaadje">
    <img
      src="https://cdn.buymeacoffee.com/buttons/v2/default-blue.png"
      width="220"
      alt="Buy Me A Coffee"
    />
  </a>
</p>

---

# Features

## Movement & Training

- Real-time velocity, position, FPS and frametime monitoring
- Angle Helper with live strafe feedback
- FPSWheel visualization
- Directional acceleration helpers
- Compass lines and movement orientation tools
- Max FPS tracking
- Training-focused HUD presets

## Jump Analysis

- Detailed jump metrics
- Golden jump comparison
- Speed loss & slowdown analysis
- Airtime and takeoff tracking
- Jump history & statistics
- CoD2 slowdown timer

## Replay & Review

- Instant jump review
- Replay timeline with movement data
- Ghost replay support
- Frame-by-frame comparison
- Replay bookmarks & route checkpoints

## Markers & Route Planning

- Place and organize markers in-game
- Build complete routes and practice paths
- Per-map persistent storage
- Route editing & quick actions
- Marker categories and path visualization
- Segment practice workflows

## Measure & Mapper Utilities

- 3D distance measurement
- Axis and slope helpers
- Texture & surface inspection
- Clip / brush overlays
- Surface flag visualization
- Measurement-to-marker workflow

## HUD & Customization

- Fully draggable UI
- Persistent layouts
- Custom colors & tooltips
- In-game keybind editor
- Multiple interaction modes
- Streamlined options UI
- Import/export-ready configuration system

## Stability & Tooling

- Crash reporting support
- Config persistence
- Fast in-game workflow
- Lightweight overlay rendering
- CoD2 and CoD4 specific feature handling

---

## Supported Games

- Call of Duty 2
- Call of Duty 4

---

## Optional Tools

### LAA Patcher

Enables the **LARGEADDRESSAWARE** flag on `iw3mp.exe` so the 32-bit
CoD2 / CoD4 client can address up to **4 GB** of memory instead of the
default 2 GB, reducing out-of-memory crashes on large maps.

- **[Download laa_patcher.exe](https://github.com/cod2-jumpers/laa-patcher/releases/latest/download/laa_patcher.exe)**
- Source & usage: [cod2-jumpers/laa-patcher](https://github.com/cod2-jumpers/laa-patcher)

**Drag your `iw3mp.exe` onto `laa_patcher.exe`** (or run
`laa_patcher.exe <path-to-iw3mp.exe>` from a terminal), then choose
**1 - Patch**. Double-clicking with no file just prints usage and exits.
Back up the exe first.

