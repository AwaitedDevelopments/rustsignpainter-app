# Rust Sign Painter

**Professional automation tool for painting signs in the survival game Rust.**

Load any image → smart color quantization → optimized brush strokes → fully automatic high-quality painting.

---

## Features

- **Broad Image Support**: PNG, JPG, JPEG, BMP, GIF, WebP, TIFF
- **Fast Quantization**: High-quality median-cut algorithm (up to 64 colors)
- **Optional Dithering**: Floyd-Steinberg for smooth gradients
- **Advanced Path Optimization**: Run-length merging + boustrophedon scanning
- **Brush-Aware Painting**: Background-first logic with separate detail passes
- **Smart Rust Integration**: Automatic hex input and brush size control
- **Easy Screen Setup**: Drag-to-select canvas + click-to-pick fields with overlay
- **Live Progress HUD**: Real-time painting status
- **Keybinds**: CTRL-1 pause/resume, hold CTRL-2 emergency stop, top-left failsafe stop (move mouse)
- **Persistent Configuration**: Automatically saves all screen positions

---

## Quick Start

### 1. Load & Preview
- Click the preview area to load your image
- Select your sign type/size
- Choose a number of colors (8–16 recommended)
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

**Pro Tip**: Brush radius 5–6 with step 5 offers the best speed/quality balance.

---

## Controls

| Action              | Hotkey / Button               |
|---------------------|-------------------------------|
| Pause / Resume      | **CTRL-1**                    |
| Emergency Stop      | **CTRL-2** (hold)             |
| Global Failsafe     | Move mouse to top-left corner |

---

## Important Notice

This software is **not open source**. The repository is public for distribution and updates only.  
All rights reserved. Unauthorized copying, modification, or redistribution is prohibited.

---

## Disclaimer & Safety

This tool uses mouse and keyboard automation **only after you explicitly start painting**.  
Always test on low-value signs first. Antivirus software may flag automation tools — this is normal behavior.
Facepunch has commented that sign painting tools will not result in anti-cheat bans, though use at your own risk. 
---

**Built for the Rust community** ❤️  

Awaited Developments
