# LiteAC

A AI-based client-side Minecraft Anticheat

---

##  Installation

1. Install [Fabric](https://fabricmc.net/) and the loader
2. put the mod (`.jar`) in the `mods` folder.
3. Make sure [**Python 3.x**](https://www.python.org/downloads/) is installed.

---

## Minimum System Requirements



| Component   | Minimum Recommended                          |
|-------------|----------------------------------------------|
| **CPU**     | Quad-core modern processor (Intel i5 / Ryzen 5 or equivalent) |
| **RAM**     | 8 GB (12 GB recommended) |
| **GPU**     | Dedicated graphics card with at least 2 GB VRAM |
| **Storage** | 500 MB free disk space (logs, AI model, cache, etc.) |
| **OS**      | Windows 10+, Linux (64-bit), or macOS 11+     |
| **Java**    | Java 21 or higher (required by Fabric for MC 1.21+) |
| **Python**  | Python 3.x installed locally                 |
| **Network** | Stable internet connection (for client-server communication) |

>  **NVIDIA GPUs with CUDA** are recommended if the AI model supports GPU acceleration.  
> If not available, the mod will fall back to CPU inference (slower, but compatible with AMD/Intel).

##  Multi-loader Compatibility (Fabric, Forge, NeoForge)

- Separate builds exist for Fabric, Forge, and NeoForge loaders due to API differences.
- AI backend and model logic remain consistent across builds.
- Network packet handling is adapted per loader’s API.
- Test on all supported loaders to ensure compatibility.

---

## Warnings

> This mod is designed to detect and block cheaters.  
> Attempts to modify, fake, or tamper with the mod or packets may result in bans or legal action.
> see ['license.md'](./LICENSE.MD) for more.







