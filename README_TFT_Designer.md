# STM32 TFT Designer V1.40

**A visual UI design tool for SPI TFT color displays on STM32 microcontrollers — designed in STM32CubeIDE projects.**

by Carlos Barberis | © 2026 Carlos Barberis. All rights reserved.

---

## What It Does

STM32 TFT Designer lets you build multi-screen graphical user interfaces for color TFT displays visually — dragging and placing widgets on a canvas — then exports ready-to-compile C code that drops directly into your STM32CubeIDE project. No hand-coding pixel coordinates. No repetitive draw calls. Just design, export, and flash.

It is built specifically for **STM32 microcontrollers + STM32CubeIDE**. The generated code targets the accompanying `tft_gfx` / `tft_widgets` / `tft_graph` driver layer written for STM32 HAL. This is not a general-purpose UI tool for other platforms.

---

## Supported Displays

| Controller | Resolutions |
|---|---|
| ILI9341 | 320×240 |
| ST7796 | 480×320 |
| ST7789 | 240×240 / 240×320 / 240×280 |
| ST7735 | 128×160 / 160×128 / 160×80 |

**Touch drivers:** XPT2046 (resistive) · FT6336U (capacitive)

---

## Widget Types

Buttons · Momentary Buttons · Checkboxes · Radio Buttons · Text Labels · Dynamic Text (live value display) · Progress Bars · Sliders · Plot/Graph (scrolling strip chart) · Rectangle · Circle/Ellipse · Image/Logo Import (RGB565 embedded bitmap)

---

## Key Features

- **Visual canvas** — drag, resize, copy, paste, duplicate widgets with full keyboard shortcut support
- **Multi-screen projects** — design as many screens as your project needs (Pro)
- **Live property panel** — every widget property editable in real time with instant canvas preview
- **Alignment tools** — align, distribute, center, AutoFit, Fit All, off-screen widget detection
- **Image import** — JPEG/BMP/PNG converted to RGB565 pixel arrays embedded in generated source
- **C code export** — `ui_screens.c/.h`, `ui_images.c/.h`, `ui_display_config.h` ready to drop into `Core/Src` and `Core/Inc`
- **Generated file headers** — auto-stamped with designer version and generation timestamp
- **Runs on Windows and macOS** (including Apple Silicon)
- **One-time purchase** — no subscription, no annual renewal

---

## Lite vs. Pro

| | Lite (Free) | Pro |
|---|---|---|
| All widget types | ✅ | ✅ |
| All display presets | ✅ | ✅ |
| All layout & alignment tools | ✅ | ✅ |
| Edit menu (copy/paste/duplicate) | ✅ | ✅ |
| C code export | ✅ | ✅ |
| Number of project screens | 1 | Unlimited |
| **Price** | **Free** | **$49.00** |

The Lite version is a fully functional tool for single-screen projects and evaluation — no time limit, no feature restrictions other than screen count.

---

## Screenshots

### Designer Canvas — STM32 TFT Designer V1.40

The designer running on macOS showing the 480×320 project canvas with the Edit menu visible. The right-hand Properties / Code panel shows all widget properties and a live C code preview.

### Running on Real Hardware

The same project exported and running on an STM32F446RE driving a 2.4" ST7796 480×320 capacitive touch display.

---

## Getting Started

1. **Download** the installer for your platform from the link below
2. **Install** — Windows: run the Inno Setup installer · macOS: open the .dmg and drag to Applications
3. **Try Lite** — the application starts in Lite mode immediately, no registration required
4. **Design** — add widgets, configure properties, arrange screens
5. **Export** — File → Export ui_screens.c/.h
6. **Integrate** — copy the generated files and the driver layer into your STM32CubeIDE project

See the full **[User Manual](STM32_TFT_Designer_User_Manual_V1_40.pdf)** for complete integration instructions, the main.c usage example, and troubleshooting.

---

## Download

**[➜ Download on Gumroad](https://gumroad.com/bartektechnologies)**  
*(Lite: free · Pro: $49.00 · Bundle with OLED Designer: $75.00)*

---

## Upgrading to Pro

Purchase a Pro license key at the link above. Once you have your key:

1. Open the application → **License → Enter License Key...**
2. Enter your registered email and license key
3. Click OK — Pro mode activates immediately, no restart needed

---

## Also Available

**[STM32 OLED Designer 128×64](https://github.com/bartektechnologies/STM32-OLED-Designer)** — the companion tool for SSD1306 / SSD1309 / SH1106 monochrome I²C OLED displays. ($35.00 · Bundle both for $75.00)

---

## Contact

Questions, license purchases, or support: **carlos@bartek.com**

---

*STM32 TFT Designer is not affiliated with or endorsed by STMicroelectronics. STM32 and STM32CubeIDE are trademarks of STMicroelectronics.*
