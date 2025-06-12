# TOUCH-KNOB-EDITOR
An editor in Touch OSC for creating modular-style knobs that you can use in your own Touch OSC projects.

![Touch-Knob-Editor-UI](img/Touch-Knob-Editor.png)

## A What?!

As a continuation of my ![Touch Knobs](https://github.com/neilbaldwin/TOUCH-KNOBS) project and prompted by a fellow Touch OSC obsessive, I created a visual editor in Touch OSC that lets you design custom modular-style knobs easily and quickly. Once you've created a masterpiece you can go back into Edit mode in Touch OSC and copy-and-paste the knob into your own projects. Once created they exist and function as a standalone object. You can also add messages to them (OSC, MIDI, local) like other objects.

## When you say "custom" what can you customise?

* Diameter
* Height
* Pointer diameter
* Pointer length
* Outline (stroke)
* Drop shadow
* Color (hue, saturation and lightness) of knob, pointer and outline
* Shadow brightness
* Control orientation (drag in X axis, Y axis or rotational axis)
* Control response (speed/precision when dragging to change value)
* Left or right-handed UI (editor option)

## How do I get it?

Just download the .tosc file, TOUCH-KNOB-EDITOR.tosc, open it in Touch OSC.

## How do I use it?

Let's look again at the UI.

![Touch-Knob-Editor-UI](img/Touch-Knob-Editor.png)

Starting from the top:

### SHAPE
This section determines the geometry of the knob.

#### `DIAMETER`
This sets the size of the knob. You can set the size anywhere between 5 and 100 pixels.

#### `HEIGHT`
This sets the height of the pseudo-3D aspect of the knob. The maximum height is limited by the Diameter of the knob. When the height is 0 the knob just appears *flat*

#### `POINTER SIZE`
This sets the diamter or width of the knob pointer.

#### `POINTER LENGTH`
You can also extrude the Pointer to make a short line-style pointer. This sets the length. The maximum length is related to the Pointer Size.

#### `OUTLINE`
When on, a thing outline or stroke is drawn around the whole knob.

#### `HOLE`
When on, a black circle is drawn around the base of the knob to give the impression it appears out of a cutout hole.

#### `DROP SHADOW`
When on, a pseudo-shadow is cast from the knob to emphasise the 3D look.

### `CONTROL`