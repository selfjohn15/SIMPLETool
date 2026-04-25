# S.I.M.P.L.E Tool
**(Satisfactory Implementation Management Planning Logistics Executor Tool)**

A web-based interactive planner for designing and managing factory layouts in Satisfactory. 

## Features

### Core Tools
- **Select (S)**: Click to select a building. Drag to move it around the grid.
- **Draw (D)**: Click and drag on the grid to draw a new building of custom dimensions.
- **Erase (E)**: Click on a building to delete it from the canvas.

### Canvas Navigation
- **Zoom**: Use the mouse wheel or the `🔍+` / `🔍-` buttons to zoom in and out.
- **Pan**: Hold `Ctrl` and drag with the mouse to pan across the canvas.

### Building Properties
When a building is selected, you can customize its properties in the right-side panel:
- **Name & Color**: Assign a custom name and choose from a palette of colors.
- **Inputs & Outputs**: Add up to 4 inputs and 4 outputs per building. You can label them and assign them to any side (Top, Right, Bottom, Left).
- **Rotate (R)**: Rotate the selected building, swapping its dimensions and repositioning its ports.

### Presets System
- **Save as Preset**: Save a configured building (including its size, color, name, and ports) for quick reuse.
- **Local Storage**: Presets are automatically saved to your browser's local storage.
- **Import/Export**: Export your presets to a `.json` file and import them to share or back up.
- **Place Preset**: Click "Place on Grid" on any preset to stamp it onto the canvas. You can also rotate (`R`) the preset before placing it.

### Layout Management
- **Save/Load Layout**: Save your entire factory grid as a `.json` file and load it back later.
- **Resize Grid**: Adjust the total number of rows and columns.
- **Clear All**: Quickly wipe the canvas to start fresh.

## Keyboard Shortcuts

| Shortcut                  | Action |
| :---                      | :--- |
| `S`                       | Select Tool |
| `D`                       | Draw Tool |
| `E`                       | Erase Tool |
| `I`                       | Add Input port to selected building |
| `O`                       | Add Output port to selected building |
| `R`                       | Rotate Building / Rotate Preset |
| `Delete` / `Backspace`    | Delete selected building |
| `Esc`                     | Deselect building / Cancel preset placement |
| `Ctrl + Drag`             | Pan canvas |
| `Mouse Wheel`             | Zoom in / out |

*Author: SecretAgentSelf*
