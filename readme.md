# Capture

A dedicated **Rocknix** app that captures still screenshots or creates recordings as animated PNGs.

## Installation

1. Choose your console:
   - `rg34xx` (640w)
   - `rg10x` (720w)

2. Copy the entire `capture` directory to the `roms/ports/` folder.

3. Final directory structure:
   ```text
   /roms/ports/
   ├─ capture/
   │  ├─ captureui
   │  ├─ conf
   │  ├─ libs
   └─ capture.sh


## How to Use

1. Select an option:
   ├─ Still screenshot (will be saved to roms/screenshots)
   ├─ Select Recording duration 5s (24 frames) /10s (48 frames) / 30s (72 frames) (Saved to roms/recordings)
   ├─ Disable Hotkey (will close the daemon running in background)
3. Press Start to exit
4. While Daemon is running in Background Press Select + R1 (rg34xx) OR Right Thumber plus button (rgb10x)
5. After all shots were taken auto it'll keep the folder full of screenshots and Animated PNG! 

**Components:**
- `main.lua` - Change UI to your liking using Font sizes & Color palette

## Important Disclaimer

This tool is designed for downloading legally obtained files only. Users are solely responsible for ensuring they have the legal right to download and possess any files obtained through this software.

## License

Free to use for personal retro gaming purposes. Use at your own risk and in compliance with applicable laws.
