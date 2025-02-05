# Vrilya's Ocarina of Time Image Extractor/Injector

## Overview
Vrilya's Ocarina of Time Image Extractor/Injector is a tool designed for extracting and injecting image textures from The Legend of Zelda: Ocarina of Time ROM files. This tool allows users to extract textures, modify them, and re-insert them into the game, making it useful for modding and custom texture replacements.

## Features
- **Extract Images**: Extract textures from the game ROM.
- **Inject Images**: Replace existing textures in the ROM with custom images.
- **Automatic Format Detection**: Reads settings from a configuration file to extract images correctly.
- **Batch Processing**: Extract and inject multiple images automatically based on predefined settings.
- **GUI Interface**: A user-friendly graphical interface for selecting ROMs, settings, and output folders.

## How to Use
### Extracting Images
1. **Run the program**: Open `VOoTIE.exe`.
2. **Select a ROM version file**: Choose a `.txt` file that defines image locations and formats.
3. **Choose a ROM file**: Select an Ocarina of Time `.z64` ROM.
4. **Select an output folder**: Specify where extracted images should be saved.
5. **Start extraction**: Click "Extract Images" to start extracting.

### Injecting Images
1. **Modify extracted images**: Edit the `.png` files as needed.
2. **Start injection**: Click "Inject Images" to inject the modified images back into the ROM.

### Testing in an Emulator
- Click "Start Emulator" to launch the emulator with the modified ROM.

## ROM Version File Format
The settings file defines image extraction and injection parameters.

Example:
```
Set TexS 32x32  # Sets texture size
Exp IA8 0x12345678 my_texture  # Exports texture at given address
```

## Notes
- Always create a backup of your ROM before making modifications.

