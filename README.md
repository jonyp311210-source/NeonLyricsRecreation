# NeonLyrics Recreation — Fabric 1.21.11

Client-only Fabric mod for **Minecraft Java Edition 1.21.11**.

## Features
- Neon “Now Playing” HUD card (bottom-left)
- Animated visualizer bars
- Demo song + lyrics line + album placeholder
- **Right Shift** opens settings
- Toggle HUD / lyrics / glow / visualizer
- Cycle accent colours (cyan → pink → green)

## Versions used
| Component        | Version              |
|------------------|----------------------|
| Minecraft        | 1.21.11              |
| Yarn             | 1.21.11+build.6      |
| Fabric Loader    | 0.20.1               |
| Fabric API       | 0.141.6+1.21.11      |
| Loom             | 1.14.10              |
| Java             | 21                   |

## Build
Requires **JDK 21** and several GB of RAM for the first run.

```bash
# from this folder
gradle wrapper --gradle-version 9.2.0   # once
./gradlew build
```

Jar output: `build/libs/neonlyrics-recreation-0.1.0.jar`

Install into `.minecraft/mods` together with Fabric Loader + Fabric API for 1.21.11.

## License
MIT
