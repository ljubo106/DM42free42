
Slightly changed Free42 code to make the custom menu the system base menu. For DM42 that behavior makes sense
as DM42 has dedicated custom keys - for me this change greatly increases usability of the DM42.

The new behavior:

* Custom menu is the base menu - custom commands are always directly accessible
* Shift is temporary switching to the "upper" custom menu - those commands are just an additional click away
* Shift-CUSTOM activates default DM42 F-Button functionality
* In the Prgm mode Exit will exit custom menu - makes easy to access up and down arrows
* Entering other menus will of course exit Custom menu


Patch files and the binary pgm file are derived from
    https://github.com/swissmicros/DM42PGM
    https://github.com/swissmicros/free42 

See LICENSE and COPYING files.

See https://www.swissmicros.com for firmware update instructions.

-Ljubo