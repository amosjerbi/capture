# Capture

A dedicated Rocknix app that capture still screenshots or create a recording in an animated PNG!

### Installation
1. Choose your console rg34xx(640w) or rg10x(720w)
2. Copy the entire `capture` directory to roms/ports/ folder:
3. /roms/ports/
    ├─ capture/
    │   ├─ captureui
    │   ├─ conf
    │   ├─ libs
    └─ capture.sh
4. Go to Tools and run once Portmaster
5. Press Start > Game Settings > Update Gamelists > Yes
6. Go to Ports > Press Capture

## How to Use

1. Select an option:
   ├─ Still screenshot (will be saved to roms/screenshots)
   ├─ Select Recording duration 5s (24 frames) /10s (48 frames) / 30s (72 frames)
   ├─ Disable Hotkey
3. Copy capture folder and capture.sh
4. If a directory doesn't exist it'll be created

**Features:**
- Multi-platform file downloading from various sources
- Search files using LÖVE2D-based user interface with on-screen keyboard (press X for search)
- Quickly browse by pressing L1/R1 or press and hold down

**Components:**
- `fetcher.py` - Main file fetching engine with platform support
- `downloaderui/` - LÖVE2D-based graphical interface
- `fetcher.sh` - PortMaster launcher script
- `download.py` & `downloader.py` - Download management modules
- `main.lua` - Change UI to your liking using Font sizes & Color palette

**Troubleshooting:**
- Don't see your list? run this in terminal to clear cache:
  ```
  sshpass -p "rocknix" ssh -o StrictHostKeyChecking=no root@192.168.0.0 "rm -rf /tmp/file_cache /tmp/platforms.json /tmp/file_list.json"
  ```

### Pico-8 Game
A simple Pico-8 game created to showcase Fetcher.

**Location:** `pico-8/`
- `romnix.p8.png` - Pico-8 cartridge file
- `romnix.p8.png.zip` - Compressed cartridge

## Important Disclaimer

This tool is designed for downloading legally obtained files only. Users are solely responsible for ensuring they have the legal right to download and possess any files obtained through this software.

## License

Free to use for personal retro gaming purposes. Use at your own risk and in compliance with applicable laws.
