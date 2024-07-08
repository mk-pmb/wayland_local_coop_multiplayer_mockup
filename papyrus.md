
This is my draft for a mockup video about how xfce on wayland can deal with
inputs from four autonomous actors working on a random plot excuse task:
Generic scientists annotate a papyrus scroll.

Feel free to invent an actual plot with actual characters and maybe even dialog.


The video starts with an Xfce desktop in 21:9 aspect ratio.
The background image is split half horizontally and half vertically,
yielding four areas, one for each actor.
Their background area is themed around their icon animal and main color.

| Screen area   | Actor   | Icon animal | Main color  |
|-------------- |-------- |------------ |------------ |
| top left      | Dan     | Mule        | grey        |
| top right     | Liv     | Frog        | turquoise   |
| bottom left   | Ben     | Bunny       | light brown |
| bottom right  | Tara    | Spider      | dark purple |

There is a top panel and a bottom panel. Both are full width.
The panels are split 45% / 10% / 45%, the outer parts assigned to the
actors' screen areas and the center part neutral.

In each screen corner, on the panel, there is an xfce main menu button.
Next to each main menu button is a pager applet, currently empty,
thus potentially invisible.
At the end of each actor's panel, bordering the center area, is a
workspace switcher applet.

The center of the top panel has a clock applet showing "Fr 04, 09:30".
The center of the bottom panel has status indicators for
bluetooth (not connected), network (cable ethernet) and power (wall outlet).

Dan, Liv and Ben each have a pointer device arrow,
decorated with their icon animal,
sitting in the center of their screen area.
Ben also has a pointer device crosshair, decorated with his icon animal,
near his main menu button.


Coming up:

:TODO: Invent a realistic workflow around these plot points.
:TODO: Break down the exact input events and describe the UI implications.

* Dan opens a Firefox and browses their project website.
* Colored beads in window title bar show keyboard input foci.
* Ben opens an annotation program, browses a file open dialog for an image.
  Meanwhile Tara grabs two opposite window corners of the annotation program
  and moves them to fill the entire bottom half of the screen.
  Tara then clicks an icon in the tool bar to summon another file open dialog.
  Ben finds the image he wanted, opens it, and a scan of a papyrus appears.
  Tara finds an annotations file, opens it, and colorful rectangles appear on
  the papyrus.
* Ben starts typing a description "Found on Jan 8, 2023 near a tomb in ",
  then midway duplicates his keyboard input focus into the layer name field
  to type a place name into both.
  Liv uses her pointer to create a text cursor behind the place name in the
  description and move her keyboard input focus onto that
  Ben defocusses the layer name field to continue the description with who
  found it, while Liv types a space, an opening bracket, some hieroglyphs
  and a closing bracket.
* Ben creates a new rectangle, which forms with one corner at his pointer
  arrow and the opposite corner at his pointer crosshair.
  Liv's pointer arrow clicks the corner where Ben's pointer arrow is
  and this corner now follows Liv's pointer arrow.
  She positions her snatched corner while Ben's crosshair guides its corner.
* Dan holds some key and quickly drags accross the rectangle towards
  the top right. A semi-transparent clone of that rectangle flies towards
  Liv's screen area, where she catches and holds it. She presses a key and
  now the thumbnail gallery in the website in her browser has an insert preview
  cursor that follows the top-left corner of the rectangle she is dragging.
  Dan throws another rectangle copy towards his screen area.
  Liv releases the drag and a thumbnail of the rectangle is inserted.
  Dan's rectangle copy collides with the top panel, which cancels the upward
  movement. The sideways movement continues until it collides with the edge
  of the screen. Dan grabs the rectangle and drags it onto a graphics program.
* The graphics program in Dan's screen area shows two layers: A part from the
  scanned papyrus is on the bottom layer, and a vector image is on the top
  layer. Liv rotates and bends the scan to fit a shape on the papyrus to the
  outer shape of the vector image, while Dan moves some of the inner vector
  shapes to match some of the symbols on the scan.
* Amazing reveal that no-one(!) could predict from names and icons:
  Toast popups in Tara's screen area show a USB hub has been connected with
  3 mice (&rarr; arrows) and 2 styluses (&rarr; crosshairs).



















