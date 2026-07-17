# QuasarZ navigation icons

Custom 128x128 transparent PNG icons for the QuasarZ WindUI sidebar. Version 2 uses bold, full-canvas silhouettes designed for the live 24px navigation frame.

| Category | Color | Icons |
| --- | --- | --- |
| Home | `#38BDF8` | category, Home, Settings |
| Shop | `#FBBF24` | category, Seed, Gear |
| Farming | `#4ADE80` | category, Plant, Event Seeds, Sprinkler, Harvest, Auto-Sell, Auto-Steal |

The runtime loads each PNG directly from:

`https://raw.githubusercontent.com/QuasarZhub/quasarz-obfuscated-loader/main/assets/icons/v2/`

Run `python tools/build_quasarz_icons.py` from the QuasarZ project to regenerate the PNG set, SHA-256 manifest, and preview sheet.
