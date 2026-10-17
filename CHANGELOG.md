# Changelog

## [0.4.0] - 2026-10-17

Straight lines and gradients.

### New
- **Gradient** tool (G): drag on the car from where it starts to where it ends, and the selected paint layer fills
  from the **From** colour to the **To** colour, or **To transparent**. **Linear** or **Radial**, with its own
  **Opacity** and **Left/right symmetry**; it shows on the car while you drag. Painting the layer's mask, it makes
  the layer fade out.
- Straight lines: with the brush or the eraser, **Shift + click** draws a straight line from the end of the last
  stroke; hold the button to see the line while you move it.

## [0.3.0] - 2026-10-17

Ready-made brushes, drawing tablets, and a tidier screen.

### New
- **Brush** menu with ten ready-made brushes, each with a preview: hard round, soft round, spray, chalk, bristles,
  marker, calligraphy nib, spatter, stipple, stars. They set the tip and its variations; colour, radius and opacity
  stay as they are. The last one chosen is remembered.
- New **Chalk** tip, and the **Bristles**, **Marker** and **Nib** stamps.
- Drawing tablets: the radius follows the pen's pressure (**Radius follows pen pressure**, **Minimum radius**). These
  settings appear after the first touch of the pen; the mouse always paints at the full radius.
- **View** menu: **UV view** (U key) and the **Front**, **Side** and **Top** views.

### Changed
- **Body** / **Windows** and **Export to the game…** are now in the top bar.
- Painting is much faster on laptops with two graphics cards: the app now uses the dedicated one.
- Dense brushes (spray, stipple, stars) paint as fast as the others.
- New icon.

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
