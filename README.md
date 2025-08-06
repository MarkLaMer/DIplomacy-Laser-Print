# Diplomacy-Laser-Print
.svg and .pdf files for laser printing the Diplomacy board game

## File Overview

### SVG Master File
- `diplomacy_master_board.svg`: Contains all design layers, editable in vector software (e.g., Affinity Designer, Adobe Illustrator).

### PDF Print Layers
Each side of the board is divided into two print layers:

- `top_board_layer1.pdf`: Land zones (top side)
- `top_board_layer2.pdf`: Sea zones (top side)
- `bottom_board_layer1.pdf`: Land zones (bottom side)
- `bottom_board_layer2.pdf`: Sea zones (bottom side)

## Print Instructions

### Using PDF Files (Recommended)

1. Load the appropriate PDF file into your laser cutter software.
2. Align the material and print the following layers:

   - Top side:
     - `top_board_layer1.pdf`
     - `top_board_layer2.pdf`

   - Bottom side:
     - `bottom_board_layer1.pdf`
     - `bottom_board_layer2.pdf`

3. Ensure correct order and alignment between layer 1 (land) and layer 2 (sea).

### Cut and Engrave Settings

- **Cut Lines**: The continent outline is marked in **pure red** (`RGB 225, 0, 0`). This line should be set to **Cut**.
- **Engrave Lines**: All other paths (including zone boundaries, coastlines, text, and features) should be set to **Engrave**.

## Notes

- DPI is set to 300
- Scale of master board is set 24" x 24".
- For best results, use vector-compatible laser software that distinguishes between color-coded operations.
- If using the SVG file instead of PDFs, manually separate and group the layers as indicated.
