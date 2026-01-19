---
title: "Fresh Powder"
date: 2025-01-18
description: "Dynamic bitcrusher and lo-fi audio effect plugin"
tags: ["bitcrusher", "lo-fi", "dynamics", "saturation"]
weight: 1
cover:
  image: "/images/fresh-powder-screenshot.png"
  alt: "Fresh Powder plugin interface"
demo_url: "https://doctornfx.github.io/fresh_powder-web/"
download_url: "https://github.com/doctornfx/fresh_powder/releases"
github_url: "https://github.com/doctornfx/fresh_powder"
---

## Fresh Powder

**A dynamic bitcrusher and lo-fi audio effect plugin**

Fresh Powder combines classic sample rate reduction (downsampling) and bit depth reduction with split-frequency processing and dynamic envelope modulation. Create everything from subtle lo-fi warmth to extreme digital destruction—with intelligent bass preservation and real-time dynamic control.

### Features

- **Bitcrushing**: Reduce bit depth from 16 bits down to 1 bit
- **Downsampling**: Reduce sample rate from 44.1kHz down to 200Hz
- **Frequency Split Processing**: Keep your bass clean while crushing the highs - helps tame harsher sounds
- **Saturation**: Add harmonic warmth to the crushed signal, or completely blow it out
- **Dynamic Mode**: Envelope follower modulates the effect intensity based on your input signal
- **Real-time Visualization**: See exactly when and how the dynamic processing engages

### Try It

**[Web Demo](https://doctornfx.github.io/fresh_powder-web/)** - Try Fresh Powder in your browser

**[Download Plugin](https://github.com/doctornfx/fresh_powder/releases)** - VST3 and CLAP formats for Windows, macOS, and Linux

**[Source Code](https://github.com/doctornfx/fresh_powder)** - View on GitHub

### Quick Start Presets

#### Subtle Lo-Fi Warmth
- Downsample: 7,000 Hz
- Cutoff: 150 Hz
- Bits: 12
- Drive: 2.0

#### Pumping Drums
- Downsample: 6,000 Hz
- Cutoff: 100 Hz
- Bits: 8
- Drive: 3.0
- Dynamic: On (Fast, Threshold: -24 dB, Strength: 0.6)

#### Extreme Destruction
- Downsample: 1,000 Hz
- Cutoff: 80 Hz
- Bits: 4
- Drive: 8.0
- Dynamic: On (Fast, Threshold: -40 dB, Strength: 1.0)

---

Built with [NIH-plug](https://github.com/robbert-vdh/nih-plug) and [egui](https://github.com/emilk/egui)
