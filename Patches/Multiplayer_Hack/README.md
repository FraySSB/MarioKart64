# Mario Kart 64 Multiplayer ROM Hack
### Fray's Emulator/Netplay Build
This is a fork of abitalive's Mario Kart 64 Multiplayer Hack which adds a couple of small updates to allow for an "improved" multiplayer experience on netplay or with emulators in general

# Changes
## New TITLE MENU Options
### Lag Fix (Default / Enabled)
- This hack prevents the game from slowing down in 4 player matches
- This setting is enabled by default, but is known to break on console, as well as cause issues with the final lap music when combined with 60 FPS

### VS Bomb Karts (Default / Disabled)
- Mini Bomb Karts can now be disabled for VS modes

### Polling Rate (Default / 30Hz)
- This hack forces the input polling rate to remain at 30Hz when the game pacing is set to 60 FPS
- This setting is enabled by default, and can help prevent the game from lagging when using kaillera netplay servers

## Modified TITLE MENU Options
### Game Pacing
- Added a hack which makes the game run at 60 FPS when the 60 FPS pacing option is selected.

### Reorganized Menu Options
- Moved Character Stats and Game Pacing options to the top of the list

### Changed Default Settings
- Character Stats are **no longer** All Yoshi by default
- Game Pacing is now 30 FPS by default
- Trophy Ceremony is now skipped by default
- Multiplayer Music is now enabled by default

# Building (Windows)
- Clone or download the repository
- Put "Mario Kart 64 (U) [!].z64" in the LIB directory
- Download and extract [these files](https://drive.google.com/file/d/0B1g_ALmgbOzxSDdWVVA4TXdwWlk/view?usp=sharing) to the Multiplayer_Hack directory
- Drag and drop mk64_multiplayer_hack.asm onto asm.cmd

# Acknowledgements
- Special thanks to leodexe for compiling the [documentation](https://pastebin.com/D7J2L5yu) I used for this build