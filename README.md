# SNES-SuperFX-adapter
(deprecated) A simple PCB adapter that allows the use of a M29F032, AM29F032/29F016 or MBM29F033 (or other pin compatible) flash memory to make a reproduction of a SNES game that uses the SuperFX (GSU-1 or GSU-2) or CX4 cartridge type. No manual wires or hot glue!


Included is the Gerber files (and a ".brd" file that works for OSH Park) which are needed for a PCB manufacturer to actually make the boards. The PDF instructions on how to assemble are included as well.

# NEW FOR 2025
The complete source for an upgraded design that uses modern and easily obtainable flash memory that you can find from places like Digikey or Mouser, like M29F160 and similar TSOP48 chips, has been added. This is the recommended design to use, as the old one is extremely outdated and uses flash memory that can only be found used, and often at expensive prices. This design is also easier for PCB fabs to produce. This design is intended for up to M29F160 (2MB) ROM sizes, but you can use M29F800 (1MB), or M29F400 (512KB) chips instead if your game is less than 2MB - or just double-up the ROM data with a hex editor and use the M29F160 for any game.

You can use EAGLE CAD or a compatible CAD program to open the source and view or change the design. Or just use the .brd file with your PCB manufacturer, most will accept that instead of gerber files.


These boards require castellation, a PCB manufacturing process that uses "half-vias" on the board edges, to ensure easy soldering to the donor cartridge. Check with your PCB manufacturer to make sure they support this feature (most do, at a slightly higher cost). Recommended PCB thickness is 1.0mm or even 0.8mm for best results.
