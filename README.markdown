PCB Test Swatch
===============

A small (somewhat inexpensive) 0.72 x 0.72 inches (0.52 in^2) sample that shows different layers possible when making a PCB. The numbered layers are as follows:

1. Silkscreen on copper
2. Copper
3. Bare PCB
4. Solder mask on copper
5. Solder mask on bare PCB

And on the back there is a copper pour and a silkscreen fill (which overlap) running vertically so you can test possible translucency with the other side’s layers. Additionally, you should be able to write with permanent marker on the rear silkscreen fill to label where your sample came from.

(Depending on the manufacturer and the processes, some layers may not appear different from others on the final product.)

This board was designed in Inkscape and converted to KiCad with the [svg2shenzhen](https://github.com/badgeek/svg2shenzhen) extension. I then fiddled with some things in KiCad.

This was designed as a KiCad project, but if you want to fabricate a PCB you don't need KiCad since the gerbers are in the [gerbers folder](gerbers/). And if you just want to order PCBs from OSHPark, [there's an OSHPark project](https://oshpark.com/shared_projects/lX2JyWTE).

## Render from KiCad:

![PCB Test Swatch 3D Render](images/pcb-test-swatch-3d_render-707.png)

