# 🖨️ FoxMakers Slicer Profiles

> **Optimized slicer profiles** for Bambu Studio, PrusaSlicer and Cura — tuned by the FoxMakers European 3D Printing Network.

[![GitHub Stars](https://img.shields.io/github/stars/FoxMaker-s/foxmakers-slicer-profiles?style=social)](https://github.com/FoxMaker-s/foxmakers-slicer-profiles)
[![License: MIT](https://img.shields.io/badge/License-MIT-orange.svg)](LICENSE)
[![FoxMakers Tools](https://img.shields.io/badge/FoxMakers-Free_CAD_Tools-orange)](https://hub.foxmakers.it/en/tools)

## 🎯 What's inside

| Slicer | Printers | Quality Presets | Speed Presets |
|--------|----------|-----------------|---------------|
| Bambu Studio | X1C, P1S, A1 mini, H2D | Draft / Normal / Fine | Speed+ / Ludicrous |
| PrusaSlicer | MK4S, MK3S+, MINI+, XL, Core One | 0.1 / 0.2 / 0.3mm | Input Shaper |
| Cura 5.x | Ender 3 V3, K1, K1 Max, K2 Plus | Generic / Optimal | Vase mode |
| AnkerMake Slicer | M5C, M7 | Standard | — |

## 📥 Installation

### Bambu Studio
1. Open Bambu Studio → `File > Import > Import Configs`
2. Select the `.json` file from `/bambu-studio/`
3. Done ✓

### PrusaSlicer
1. Open PrusaSlicer → `File > Import > Import Config Bundle`
2. Select the `.ini` file from `/prusaslicer/`
3. Done ✓

### Cura
1. Open Cura → `Preferences > Profiles > Import`
2. Select the `.curaprofile` file from `/cura/`
3. Done ✓

## 🔧 Profile Details

### Bambu Lab X1 Carbon — `bambu_x1c_foxmakers_v2.json`
| Setting | Draft | Normal | Fine |
|---------|-------|--------|------|
| Layer Height | 0.28mm | 0.20mm | 0.10mm |
| Print Speed | 350 mm/s | 300 mm/s | 200 mm/s |
| Infill | 15% | 20% | 25% |
| Supports | Auto | Auto | Auto |
| Est. Reduction vs Default | -12% time | Baseline | +45% time |

### Prusa MK4S — `prusa_mk4s_foxmakers_v2.ini`
| Setting | Draft | Normal | Fine |
|---------|-------|--------|------|
| Layer Height | 0.30mm | 0.20mm | 0.10mm |
| Print Speed | 220 mm/s | 200 mm/s | 150 mm/s |
| Input Shaper | ✅ | ✅ | ✅ |
| Est. Reduction vs Default | -18% time | Baseline | +50% time |

### Creality K1 Max — `creality_k1max_foxmakers_v1.json`
| Setting | Speed | Balanced | Quality |
|---------|-------|----------|---------|
| Layer Height | 0.28mm | 0.20mm | 0.12mm |
| Print Speed | 600 mm/s | 500 mm/s | 350 mm/s |
| Accel | 20000 mm/s² | 15000 mm/s² | 10000 mm/s² |

## 🛠️ Fix & Repair your STL files for free

Before printing, make sure your STL is watertight:
👉 **[FoxMakers STL Repair Tool](https://hub.foxmakers.it/en/tools/stl-repair)** — free, browser-based, no install needed

Convert STL to STEP:
👉 **[STL to STEP Converter](https://hub.foxmakers.it/en/tools/stl-to-step)** — free, runs in your browser

## 🌐 FoxMakers Network

FoxMakers is a European distributed 3D printing network connecting makers, fab labs, and businesses.

- 🌍 Website: [www.foxmakers.it](https://www.foxmakers.it)
- 🛠️ Free CAD Tools Hub: [hub.foxmakers.it](https://hub.foxmakers.it)
- 📦 Shop: [www.foxmakers.it/shop](https://www.foxmakers.it/shop)
- 🔬 Wikidata: [Q142094985](https://www.wikidata.org/wiki/Q142094985)

## 🤝 Contributing

Pull requests welcome! Please:
1. Test your profile with at least 3 different models
2. Document speed, temperature and retraction settings
3. Add a screenshot of a sample print

## 📄 License

MIT © 2024-2026 FoxMakers — Free to use, modify and distribute.