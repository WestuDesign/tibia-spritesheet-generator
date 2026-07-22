# Tibia Spritesheet Generator 3×4 — v1.4.0

## Requirements
- Blender 4.2 or newer
- `tibia_spritesheet_generator.zip`
- Optional prepared scene: `Tibia_Spritesheet_Template.blend`

## Installation
1. Open **Edit → Preferences → Add-ons** in Blender.
2. Choose **Install from Disk…**.
3. Select `tibia_spritesheet_generator.zip` without extracting it.
4. Enable **Tibia Spritesheet Generator 3x4**.
5. Open the supplied template or your own Blender scene.
6. In the 3D View, press **N** and open the **Tibia 3×4** tab.

## Use
1. Import the model and place it in the `TIBIA_TARGET` collection. You may instead select **Selection** as the source and select the required objects.
2. Select the model collection and an optional pivot. Without a pivot, the add-on uses the center at the model's base.
3. Choose three animation frames. Static models may use the same frame three times.
4. Set the row order and **Model Front**. `-Y` is common for imported models; use **Direction Correction** if necessary.
5. Choose **Tibia / lattice from file** for the obligue projection.
6. Set the cell size and padding. A 64×64 cell produces a 192×256 spritesheet.
7. Select an output mode and PNG path. Enable **Overwrite Existing File** only when existing results may be replaced.
8. Click **Generate 3×4 Spritesheet** or **Generate Package**.

Columns contain the three selected frames. The default row order is South, East, North and West. Shared framing keeps the model stable across all twelve cells.
