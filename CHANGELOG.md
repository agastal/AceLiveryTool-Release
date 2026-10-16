# Changelog

## [0.2.0] - 2026-10-16

Paint one part of the car at a time: the hood, a door, a bumper, with a click.

### New
- **Parts** tool (P): click a part of the car and the selected layer shows only there (the first click gives the
  layer a mask); Shift+click hides a part again. **Whole part** takes the whole door, hood or bumper as the game
  moves it; **The other side too** takes the matching part on the other side. The status line names the part under
  the pointer. Then fill, paint, images and texts of that layer stay inside.
- The cars are prepared again by themselves, once, when a new version of the app needs more from them (this one
  reads the car's parts): about a minute at the first start after the update.

### Changed
- The tool buttons (View, Brush, Eraser, Place, Parts) are icons; their names and keys are in the tooltips.

## [0.1.0] - 2026-10-16

The first public version: a 3D livery editor for every car of Assetto Corsa EVO.

### New
- All 71 cars of the game, prepared from your own installation on first start (about a minute), with their
  wheels and the UV layout as a guide layer.
- Layers with masks, blend modes and their own roughness, metallic and clear coat.
- Brushes that paint in 3D, across panels without seams: round, spray and stamps, with left/right symmetry.
- Images and text placed on the car, also mirrored to the other side.
- Undo and redo; project files (`.acelivery`).
- Views along the car's axes, as in Blender: 1, 3, 7 for front, right side and top (with Ctrl the opposite
  ones), or Alt + drag on the car.
- Export to the game as an External Livery, linked to a car of your garage: the app lists your saved cars with
  their trim, warns about trims that do not take external liveries and about a car already linked to another
  livery.
- *File → Manage liveries…*: every External Livery with a preview, its car and whether the game ever applied
  it; open its folder, turn it off and on again, move it to the Recycle Bin, or **Edit** it: any External Livery, also one not made with
  the app, opens on its car as a layer with its colours and materials, ready to be painted over and exported again.
- Italian, English, French, German and Spanish.
