
# jquery-multilineSelectmenu
This is a jQuery UI extension that adds multiline and css styling support to selectmenu options.

# Usage
Create a selectmenu as normal using `<select>` and `<option>`.

Use `|` in the options as a line-break.

Then turn it into a widget by doing `$( selection ).multilineSelectmenu();`.

CSS styling can be applied to the `ui-selectmenu-menu-item-header` and the `ui-selectmenu-menu-item-content` classes.

# Proof It Works
https://jsfiddle.net/mherbold/t85y6o1r/

# Update 7 May 2019
Added destroy method
 `$( selection ).multilineSelectmenu('destroy');`.