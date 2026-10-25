# Changelog

## [0.7.0] - 2026-10-25

Share your liveries with other drivers, so they see them on your car when you race online, and put a whole race's
liveries in one pack.

### New
- **Share with other drivers** (the new icon next to each livery in **Manage liveries**): saves a zip to send to
  other drivers. They install it with the app, or with **INSTALLA.bat** inside the zip if they do not have it.
- **Install a shared livery…** (File menu, **Install from zip…** in **Manage liveries**, or drop the zip on the
  window): **See it on <author>'s car when you race online** installs it as it is (the game downloads no one's
  liveries: everyone needs them); **Use it on my car** links a copy to a car of your garage, or to a new one added
  to the garage when you have none of that trim.
- **Make a race pack…** (File menu): the organiser joins the drivers' zips into one; each driver installs it once and
  sees every livery on its driver's car. No car is added to the garage, and a driver's own livery is skipped.
- **Manage liveries** shows the liveries installed from others as "by <author>: you see it on their car online".

### Fixed
- The **Width** of an image or text shows at most one decimal.

## [0.6.0] - 2026-10-19

Carbon fibre, SVG logos, and images you resize and turn right on the car.

### New
- **Carbon fibre** brush (and the **Carbon** tip): paints a woven carbon fibre in the brush's colour (dark grey for
  classic carbon); **Grain** sets the width of a strand. With the Carbon tip, **Fill with the brush colour** fills
  the layer with carbon: with the **Parts** tool, a carbon bonnet takes two clicks.
- **SVG** files for **+ Image**, **+ Texture** and the brush stamps (**Load…**): logos stay sharp at any size, and
  projects keep the SVG itself.
- **Place** tool: **Shift** + drag on the car resizes the selected image or text, **Ctrl** + drag turns it (press
  Shift too for steps of 15°). Each is one step of **Undo**.

### Changed
- While the cars are being prepared from the game (**Prepare the cars from the game**), a spinning wheel and the
  hourglass pointer show that the work is going on.

### Fixed
- Where a small piece (a licence plate, for example) shares the texture with a panel, the brush, the eraser and the
  gradient now paint the panel instead of missing it.
- The hint under the **Place** tool called it by another name.

## [0.5.0] - 2026-10-18

Bent text, a brush you can see, and no more lost work.

### New
- Text can be bent as in Illustrator: in a text layer, **Warp** (**Arc**, **Arch**, **Bulge**, **Flag**) and **Bend**,
  from -100% to 100% (negative bends the other way).
- The brush and the eraser show a circle under the pointer, as wide as the **Radius** (two with **Left/right
  symmetry**); over the car it takes the place of the mouse pointer.
- **Unsaved changes**: before closing the window, starting a **New** project, opening another one or changing car,
  the app asks whether to **Save** them.

### Changed
- The hint about the mouse and the views shows with the **View** tool only; the **Shift + click** straight-line hint
  is now under the brush settings.

### Fixed
- Moving a slider (for example **Radius**) no longer makes its value wrap and shift the whole panel.

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
