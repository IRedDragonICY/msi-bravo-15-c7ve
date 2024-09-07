# MSI Bravo 15 C7VE Tweaking Guide

## 🖥️ System Specifications
| Component | Specification |
|-----------|---------------|
| CPU       | AMD Ryzen 7 7735HS with Radeon Graphics |
| GPU       | NVIDIA RTX 4050 |

## 🌟 Rating
| Aspect      | Rating |
|-------------|--------|
| Performance | ★★★★★★★★★☆   | 
| Thermal     | ★★★★★★★☆☆☆ |
| Price       | ★★★★★★★★★★ |

## 🚀 Performance Tweaks
### 🔧 Overclocking
#### Universal x86 Tuning Utility (UXTU)
> 📥 Download UXTU: [JamesCJ60/Universal-x86-Tuning-Utility](https://github.com/JamesCJ60/Universal-x86-Tuning-Utility)

Unlock the full potential of your Intel/AMD based device with this powerful utility.

##### iGPU Frequency (MHz)
| Setting | Value | Notes |
|---------|-------|-------|
| Hard Limit | 2750 | Maximum achievable |
| Potential Crash | 2730-2749 | Use with caution |
| Safe Range | < 2723 | Recommended for stability |
| Stock | 2400 | Default setting |

#### NVIDIA GPU Tuning
| Parameter | Value | Notes |
|-----------|-------|-------|
| Frequency-Adjusted Voltage Limit | 4000 MHz | Default setting |
| GPU Core Clock Offset | 230 MHz | |
| GPU Memory Clock Offset | 1600 MHz | Possible artifacts |
| | 1560 MHz | Safe setting |

### ⚡ AMD Curve Optimiser
#### Global Settings
| Parameter | Value |
|-----------|-------|
| All Core Offset | -50 |
| iGPU Offset | -50 |

#### Per-Core Curve Optimiser (CCD1)
| Core | Offset |
|------|--------|
| 1-8  | -50    |

### ⚙️ Additional Settings
| Setting | Value |
|---------|-------|
| AMD Boost Profile | Performance |
| Windows Power Mode | Best Performance |

## 📝 BIOS Settings
> Coming soon

---

*Note: Always proceed with caution when overclocking. Monitor temperatures and stability closely. Your mileage may vary depending on silicon quality and cooling solution.*
