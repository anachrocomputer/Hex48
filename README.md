# Hex48 #

PCB design for a hexagonal prototyping board capable of holding DIL chips with
up to 48 pins.

VERY MUCH A WORK-IN-PROGRESS AND NOT TESTED BY MAKING A PCB YET.

## The Problem ##

Everybody has prototyping PCBs in rectangular form, but what other shapes tesselate well?
How about hexagons, would they work?
And why stop at 40-pin DIL packages when chips like the 68008 come in 48-pin DIL?

## The Solution ##

This PCB design mounts the DIL part on a hexagonal board that can be easily tesselated.
It has mounting holes for M3 PCB standoffs, or it can be fitted with non-slip feet.
In extreme cases, a heavy base can be made out of an insulator such as slate.

## KiCad ##

This design has been created using the Open Source CAD package KiCad, V6.0.

To install it on Ubuntu Linux:

`sudo apt install kicad`

To make the snazzy 3D rendering work, install the additional package:

`sudo apt install kicad-packages3d`

I'm using Ubuntu 22.04 LTS which gives me KiCad V6.0.
As I write this, the latest KiCad is V7.0,
so I expect I'll upgrade when the next LTS release comes out.

