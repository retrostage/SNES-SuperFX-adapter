# SNES-SuperFX-adapter
(deprecated) A simple PCB adapter that allows the use of a M29F032, AM29F032/29F016 or MBM29F033 (or other pin compatible) flash memory to make a reproduction of a SNES game that uses the SuperFX (GSU-1 or GSU-2) or CX4 cartridge type. No manual wires or hot glue!


Included is the Gerber files (and a ".brd" file that works for OSH Park) which are needed for a PCB manufacturer to actually make the boards. The PDF instructions on how to assemble are included as well.

# NEW FOR 2025
The complete source for an upgraded design that uses modern and easily obtainable flash memory that you can find from places like Digikey or Mouser, like M29F160 and similar TSOP48 chips, has been added. This is the recommended design to use, as the old one is extremely outdated and uses flash memory that can only be found used, and often at expensive prices. This design is also easier for PCB fabs to produce.


These boards require castellation, a PCB manufacturing process that uses "half-vias" on the board edges, to ensure easy soldering to the donor cartridge. Check with your PCB manufacturer to make sure they support this feature (most do, at a slightly higher cost). Recommended PCB thickness is 1.0mm or even 0.8mm for best results.
