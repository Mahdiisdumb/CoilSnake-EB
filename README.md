# CoilSnake-EB

CoilSnake bundled with an EarthBound decompilation project and ROM for educational purposes.

This repository provides a complete working setup for exploring how EarthBound is structured internally using CoilSnake. It is intended strictly for educational, research, and reverse-engineering study.

---

## Purpose

This project exists to:

- Demonstrate how EarthBound’s data is structured
- Explore ROM decompilation workflows
- Study SNES-era game architecture
- Experiment with scripting, assets, and data editing

This is not affiliated with the original CoilSnake developers.

---

## Included

- `CoilSnake-4.2.exe` (Windows build)
- EarthBound ROM
- Fully decompiled EarthBound project
- **CCScript (CCS) files already decompiled**
- Project configuration data

The CCS files are already extracted and readable, so you can directly edit dialogue and in-game text without having to manually extract or decode them yourself.

Everything required to decompile, modify, edit dialogue, and recompile is included in this repository.

---

## Editing Dialogue (CCS)

The game's CCScript files are already decompiled into editable format.

To modify dialogue:

1. Navigate to the script/CCS folder.
2. Open the relevant script file.
3. Edit dialogue text directly.
4. Save the file.
5. Recompile using CoilSnake.

Invalid syntax or formatting errors will cause compilation to fail, so edit carefully.

---

## How It Works

### Decompile

1. Run `CoilSnake-4.2.exe`
2. Select **Decompile**
3. Choose the included ROM
4. Select an output directory
5. Start the process

---

### Recompile

1. Open `CoilSnake-4.2.exe`
2. Select **Compile`
3. Choose the project folder
4. Select an output ROM name
5. Compile

If the project files are valid, a modified ROM will be generated.

---

## Educational Notice

This repository is provided for:

- Technical study
- Reverse engineering practice
- Learning about ROM hacking workflows

It is not intended for commercial use.

---

## Disclaimer

This project is provided as-is. Use responsibly.
