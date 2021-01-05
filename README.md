# Inventory Plus
An attempt to fix Minecraft's Inventory Problem with a Vanilla compatible mod.

This mod will aim to be 100% compatible with Vanilla servers. It doesn't aim to increase storage space, or make the ender chest always available anywhere. Rather, it hopes to implement a few core Quality of Life improvements to the current system. **This mod is still in very early development, and probably will not be complete for a while.** Below is a list of planned features.

## Planned Features
Exclusive slots: Slots can be configured to hold only one type of item, and reject any others. The item it is configured to will prefer that slot when it is picked up. 
Eg. Slot 1 in the hotbar can be set as exclusive to a diamond pickaxe. If the player was to die, then retrieve all their items, the diamond pickaxe would automatically end up in Slot 1, rather than the first item picked up filling that slot.

Saved layouts: The layout of the "Exclusive slots" can be saved, and loaded again later. Upon loading a layout, it will also attempt to rearrange the inventory such that the items would end up in their "Exclusive slot".

Inventory row cycling: Using a certain keyboard shortcut, rows of the inventory will cycle up/down. For example, cycling down, items in the hotbar will move to the top row, and the items in the row that was above the hotbar move into the hotbar. This will allow players to set up their inventory to have multiple "hotbars", useful for building projects etc.

Quick cleanup: An option to quickly arrange the inventory, ignoring the hotbar. Sorts by name, type, or value.

Inventory blacklist: A customisable list of items that the player will not pick up. Useful if you are sick of randomly recieving some seeds, a flower, and two rotten flesh everytime you leave base.

Low priority disposal: If the inventory is full, items on a customisable low priority list are automatically ejected to make room for better items.

Auto Tool: Optionally, a setting can be turned on to enable Auto Tool, where trying to mine a block will automatically equip the correct tool. 

Tool Protection: Tools can be marked as protected. These tools are swapped out before they break, either for a fresh tool, or for the hand. As well, a dialogue asks the player before the item is thrown, to make sure it is safe.

Offhand Improvement: Pressing ctrl when right clicking uses blocks from the off-hand, rather than the mainhand.

Precise Item amounts: Using a keybind, whilst hovering over an item, a numerical amount (between 1 - 64) can be specified to pick up exactly the specified amount.
