A BitGrid cell prototype built from 7400 series TTL chips.

KiCad is used to create the schematic, and other EDA

I'm learning KiCad 8.0 while doing this, so it's going to be slow.

9/24/24 - I'm adding a configuration register to a BitGrid cell, with some additional logic to maximize use of the shift register chain. This will allow the use of the LUT memory as a 16 entry buffer/memory, so that we can put memory blocks whereever they need to be in a bitgrid array without wasting tons of cells.


This allows a virtual line of 16 cells worth of state to be placed anywhere, in any one or the outputs, up to all 4 of them.
So it's Linear memory, and it's isometric.... thus an IsoLinear memory cell ;-)
