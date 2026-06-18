# PSYCHRONIC_MegaEquipMZ

**RPG Maker MZ Plugin**

Adds Extra Functionality to Equipping in RPG Maker MZ.

## What It Does

PSYCHRONIC_MegaEquipMZ.js.

## Plugin File

- `PSYCHRONIC_MegaEquipMZ.js`
- Target: RPG Maker MZ
- Author: Psychronic
- URL: https://psychronic.itch.io

## Installation

1. Download `PSYCHRONIC_MegaEquipMZ.js`.
2. Place it in your RPG Maker MZ project's `js/plugins/` folder.
3. Enable it from the RPG Maker Plugin Manager.
4. Configure any plugin parameters or commands listed below.

## Full Plugin Help

PSYCHRONIC_MegaEquipMZ.js

### Notetags

You can use the following notetags to change a class's equipment setup.

Class Notetags:
<Equip Slot: x> Example: <Equip Slot: 1, 2, 3, 4, 5, 5, 5, 5>
<Equip Slot: x, x, x>
Changes this class's equipment slots to x. Using repeating numbers makes
it so that equipment type is duplicated and that the class can equip
multiple equipment of that type. To find the Equipment Type ID, go to your
database's Types tab and look for the ID type.

If you don't like the above method for setting equipment slots, you can
use the following notetags instead:

<Equip Slot> Example: <Equip Slot>
string Weapon
string Armor
string Accessory
string Accessory
</Equip Slot> </Equip Slot>
Replace 'string' with the Equipment type's name entry. This is case
sensitive so if the string does not match a name entry perfectly, the slot
will not be granted to the class. Multiple copies of a name entry would
mean the class can equip multiple equipment of that type. Everything works
the same as the previous notetag.

Weapon and Armor Notetags:
<stat: +x>
<stat: -x>
Allows the piece of weapon or armor to gain or lose x amount of stat.
Replace "stat" with "hp", "mp", "atk", "def", "mat", "mdf", "agi", or
"luk" to alter that specific stat. This allows the piece of equipment
to go past the editor's default limitation so long as the maximum value
allows for it. Changes made here are ADDED to the editor's Parameter Changes.

## Source

This standalone repository is generated from the latest PSYCHRONIC plugin source in the RPG Reactor Complex template.

## License

MIT. See `LICENSE`.
