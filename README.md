<div style="display: flex; flex-direction: column; align-items: center; text-align: center ">
  <a  href="https://github.com/lordchunder/rustsignpainter-app">
     <img src="https://repository-images.githubusercontent.com/1240215351/565c142f-d291-435d-83e0-03bb88e1852f" alt="Logo" width="428" height="214">
  </a>

<h1 style="font-family: monospace; margin: 0">RUST SIGN PAINTER</h1>
  <p>
    Professional automation tool for painting signs in the survival game Rust. 
   <br/> 
    Load any image → smart color quantization → optimized brush strokes → fully automatic high-quality painting.
    <br />
    <br />
    <a href="https://github.com/lordchunder/rustsignpainter-app"><strong>Documentation</strong></a> • <a href="https://github.com/AwaitedDevelopments/rustsignpainter-app/releases">Download for Free</a>
    <br />
    <a href="https://github.com/AwaitedDevelopments/rustsignpainter-app/issues/new?template=bug_report.md">Report a Bug</a> • <a href="https://github.com/AwaitedDevelopments/rustsignpainter-app/issues/new?template=feature_request.md">Request a Feature</a> • <a href="https://github.com/AwaitedDevelopments/rustsignpainter-app/issues">Discussion</a>  •  <a href="https://www.awaiteddevelopments.com/contact">Support</a>
    <br/>
    <br/>
    <a href="https://www.awaiteddevelopments.com/rustsignpainter">awaiteddevelopments.com/rustsignpainter</a>
</p>

[<img alt="GitHub Version" src="https://img.shields.io/github/v/release/AwaitedDevelopments/rustsignpainter-app?display_name=release"/>](https://github.com/AwaitedDevelopments/rustsignpainter-app/releases)
[<img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/AwaitedDevelopments/rustsignpainter-app"/>](https://github.com/AwaitedDevelopments/rustsignpainter-app/releases)
[<img alt="GitHub Downloads" src="https://img.shields.io/github/downloads/AwaitedDevelopments/rustsignpainter-app/total"/>](https://github.com/AwaitedDevelopments/rustsignpainter-app/releases)
[<img alt="GitHub Issues" src="https://img.shields.io/github/issues/AwaitedDevelopments/rustsignpainter-app"/>](https://github.com/AwaitedDevelopments/rustsignpainter-app/issues)
[<img alt="GitHub Issues" src="https://img.shields.io/github/size/awaiteddevelopments/rustsignpainter-app/rsp.exe"/>](https://github.com/AwaitedDevelopments/rustsignpainter-app/releases)


</div>

---

<p align="center">
  <img src="assets/demo_animation.gif" alt="Animated demo (coming soon)" height="256" />
</p>


## Features

- **Broad Image Support**: PNG, JPG, JPEG, BMP, GIF, WebP, TIFF
- **Fast Quantization**: High-quality median-cut algorithm
- **Optional Dithering**: Floyd-Steinberg for smooth gradients
- **Advanced Path Optimization**: Run-length merging + boustrophedon scanning
- **Brush-Aware Painting**: Background-first logic with separate detail passes
- **Smart Rust Integration**: Automatic hex input and brush size control
- **Easy Screen Setup**: Drag-to-select canvas + click-to-pick fields with overlay
- **Live Progress HUD**: Real-time painting status
- **Keybinds**: CTRL-1 pause/resume, hold CTRL-2 emergency stop, top-left failsafe stop (move mouse)
- **Persistent Configuration**: Automatically saves all screen positions


## Download & Installation

1. Navigate to the [Releases](https://github.com/LordChunder/rustsignpainter-app/releases) tab on the right side of this
   GitHub page.
2. Under the **Latest** release, download the `rsp.exe` file.
3. Run the `.exe` (No installation required).

*Note: Windows Defender or other antivirus software may flag the file because it uses mouse/keyboard automation. This is
normal behavior for macro tools.*


## Screenshots

<div style="display:flex; gap:12px; flex-wrap:wrap; justify-content:center; align-items:flex-start">
  <a href="assets/screenshot_1.webp"><img src="assets/screenshot_1.webp" alt="Screenshot: Load & Preview" width="256"/></a>
  <a href="assets/screenshot_2.webp"><img src="assets/screenshot_2.webp" alt="Screenshot: Configuration & Palette" width="256"/></a>
  <a href="assets/screenshot_3.webp"><img src="assets/screenshot_3.webp" alt="Screenshot: Painting HUD & Progress" width="256"/></a>
</div>


## Rust Sign Painter Pro

Rust Sign Painter is fully functional in the free tier. An optional Pro tier is available for power users who need
additional capabilities (more colors, lower delays, priority updates). Pro is not required to use the app.

| Feature            | Free Tier      | Pro Tier             |
|:-------------------|:---------------|:---------------------|
| **Max Colors**     | Up to 8 Colors | **Up to 64 Colors**  |
| **Hardware Delay** | Capped at 50ms | **Unlimited (0ms)**  |
| **Color Delay**    | Capped at 0.5s | **Unlimited (0.0s)** |
| **Updates**        | Basic          | **Priority**         |

### How to activate Pro 

1. Purchase a lifetime license key at **[awaiteddevelopments.com/rustsignpainter](https://www.awaiteddevelopments.com/rustsignpainter)**.
2. Open the application.
3. Click **Options → 🔑 Activate License...** in the top menu bar.
4. Enter your email and license key to unlock Pro features.

*Note: Licenses are limited to one active device per user and can be transferred. Multiple devices simultaneously
require separate licenses.*


## Quick Start

### 1. Load & Preview

- Click the preview area to load your image
- Select your sign type/size
- Choose your desired number of colors
- Enable dithering if needed
- Click **Preview Quantization**

### 2. Configure Positions

Open Rust’s sign editor, then:

- **Capture Canvas** → drag over the painting area
- **Capture Hex Field** → click the hex color input
- **Capture Brush Field** → click the brush radius input
- Save configuration

### 3. Paint

- Adjust Detail Step and Background Step (higher = faster)
- Click **Generate Plan**
- Click **Start Painting** and switch to Rust during the countdown



## Controls

| Action          | Hotkey / Button               |
|-----------------|-------------------------------|
| Pause / Resume  | **CTRL-1**                    |
| Emergency Stop  | **CTRL-2** (hold)             |
| Global Failsafe | Move mouse to top-left corner |



## Important Notice

This software is **not open source**. The repository is public for distribution and updates only.  
All rights reserved. Unauthorized copying, modification, or redistribution is prohibited.



## Disclaimer & Safety

This tool uses mouse and keyboard automation **only after you explicitly start painting**.  
Always test on low-value signs first. Facepunch has commented that sign painting tools will not result in anti-cheat
bans, though you use this at your own risk.



  <a  href="https://github.com/lordchunder/rustsignpainter-app">
     <img src="assets/icon.png" alt="Logo" width="128" height="128">
  </a>
  
  **Built for the Rust community** ❤️

Awaited Developments
