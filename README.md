A browser-based map viewer for exploring Bloxd world generation from a seed. Load a seed to inspect the generated map, locate structures, examine chest loot, and mark places you want to revisit.

## Features

- **Seed loading** — enter a world seed and select **LOAD** to generate its map.
- **World and chunk navigation** — use the world/chunk teleport controls to jump to a location.
- **Structure overlay** — view generated structures on the map.
- **Chest loot inspection** — select a chest marker to inspect its loot. Chest markers are outlined by tier:
  - **T1:** white
  - **T2:** green
  - **T3:** blue
  - **T4:** purple
  - **T5:** yellow
- **Item search** — search for an item in chests to help find where it appears.
- **Waypoints** — mark and manage locations of interest.
- **Map tools** — use chunk and stone overlays, search, and the measurement tool.
- **Share and export** — copy a link to the current map or save the map view as a PNG.

## Getting Started

1. Download and extract the ZIP file.
2. Keep `index.html`, `game_worker.js`, and `textures.js` together in the same folder.
3. Open `index.html` in a modern browser such as Chrome, Edge, or Firefox.
4. Enter a seed and click **LOAD**.
5. Use the map controls and sidebar to explore the generated world.

If the page does not work when opened directly, try serving the folder with a local static web server and open the local address in your browser.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | Main user interface and map viewer |
| `game_worker.js` | World-generation worker used by the map |
| `textures.js` | Texture assets used by the interface |

## Tips

- Zoom in to distinguish individual chest markers.
- Click a chest marker to see its loot details.
- Use the item search when you are looking for a particular chest item.
- Use waypoints or copy-link features to keep track of useful locations.

## Notes

This project uses files supplied with the project archive. The world-generation and texture files may be subject to the original game's terms and intellectual-property rights. Before publishing or redistributing the project, make sure you have permission to share all included code and assets.

## Troubleshooting

- **Blank or failed map:** refresh the page and try a modern browser.
- **Controls or assets missing:** verify that all three project files are in the same folder and were extracted correctly.
- **Slow loading:** try a smaller seed/map workload if the interface provides that option, and close other resource-heavy tabs.

---
**Project:** Bloxd Seed Map
"""
