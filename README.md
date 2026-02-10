# Oldgen GTA5 for FiveM

This resource provides oldgen GTA5 visual settings and timecycle modifications for your FiveM server, giving players a classic GTA5 look and feel.

## Features

- Visual settings from oldgen GTA5
- Complete timecycle modifications for all weather types
- Weather-specific timecycle files (clear, rain, snow, fog, etc.)
- Underwater visual settings

## Installation

1. Download or clone this repository
2. Copy the entire `oldgen-gta5-fivem` folder to your FiveM server's `resources` directory
3. Add `ensure oldgen-gta5-fivem` to your `server.cfg`
4. Restart your server

## Structure

```
oldgen-gta5-fivem/
├── fxmanifest.lua          # Resource manifest
├── stream/                 # Streamable files directory
│   └── data/
│       ├── visualsettings.dat
│       └── timecycle/
│           ├── timecycle_mods_*.xml
│           └── w_*.xml (weather-specific files)
└── README.md
```

## What This Does

This resource overrides the default GTA5 visual and timecycle settings with oldgen versions, providing:
- Different lighting and color grading
- Modified weather visual effects
- Classic GTA5 atmosphere
- Consistent look for all connected players

## Credits

Original files from oldgen GTA5