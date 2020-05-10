PCB Test Swatch
===============

A small (somewhat inexpensive) 0.72 x 0.72 inches (0.52 in^2) sample that shows different layers possible when making a PCB. The numbered layers are as follows:

1. Silkscreen on solder mask on copper
2. Solder mask on copper
3. Solder mask
4. Copper
5. Nothing (bare PCB)

For each layer, the _numbers_ themselves are made with:

1. Hole in silkscreen, showing copper
2. Hole in copper, showing solder mask on PCB
3. Copper, showing solder mask on copper
4. Solder mask, showing solder mask on copper
5. Solder mask, showing solder mask on PCB

And on the back there is a copper pour and a silkscreen fill (which overlap) running vertically so you can test possible translucency with the other side’s layers. Additionally, you should be able to write with permanent marker on the rear silkscreen fill to label where your sample came from if you want.

Notes:

- Depending on the manufacturer and the processes, some layers may not appear different from others on the final product.
- In general, the layers are ordered as follows when manufactured: silkscreen on solder mask on copper on PCB.
- Remember, the solder mask layer in KiCad (and possibly other EDA software) acts as a mask for the solder mask, so wherever you draw on the soldermask layer, no mask substance will appear on the PCB.

This board was designed in Inkscape and converted to KiCad with the [svg2shenzhen](https://github.com/badgeek/svg2shenzhen) extension. I then fiddled with some things in KiCad.

This was designed as a KiCad project, but if you want to fabricate a PCB you don't need KiCad since the gerbers are in the [gerbers folder](gerbers/). And if you just want to order PCBs from OSHPark, [there's an OSHPark project](https://oshpark.com/shared_projects/FQnr9dzM).

## Render from KiCad:

![PCB Test Swatch 3D Render](images/pcb-test-swatch-3d_render-707.png)

