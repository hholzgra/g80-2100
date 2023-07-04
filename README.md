# g80-2100
Cherry G80-2100 repurposing using an Arduino to handle its custom function keys

I've got an old [Cherry G80-2100](https://deskthority.net/wiki/Cherry_G80-2100) keyboard with some 20+ extra programmable keys, but the battery backed up RAM chip (yes, a DIL RAM chip with a battery built right into it) that the keyboard firmware used to store custom key sequences in has of course long died. 

Also this keyboard still came with the good old large 5pin DIN plug, so to use it on a contemporary PC it needs a DIN-to-PS/2 adapter, and then a PS/2-to-USB converter.

So the idea is to convert it into a "true" programmable USB keyboard by having a small Arduino board with USB HUD capabilities hidden inside the case converting the PS/2 signals into USB keystrokes internally, and also taking care of the extra function key to programmable keypress macro conversion.
