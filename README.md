# AMPi4
Amiga Inspired pi4 Wedge Case

Blog post with more details: https://hobbytronics.home.blog/2023/01/10/ampi4-custom-amiga-inspired-pi4-case-with-mechanical-keyboard/

![1pi4](https://user-images.githubusercontent.com/43157075/212522759-57734242-aa9b-488d-8c24-4ea1b6958a62.jpg)

The stl files for the four parts of the case are included.  

I have also included the stl files for the Badge I created.  The badge is printed in 4 parts, but without removing them from the print bed.  The intention is to slice the print at .2mm layer height and have ZHop Enabled at .41mm.  The first three files are .4mm thick, meaning 2 layers at .2mm layer height.  The Z Hop needs to be higher than the .4mm and should be ZHop everywhere, if that is not set when the print nozzle passes over an eariler part of the print it will damage the eariler print, and is likely to knock it loose as well wasting the whole print.  Print BadgeLayer1a in one color on the printer.  Keep the printer bed warm to keep the print stuck to the bed properly, and swap the filament quickly purge it for the next color.  I remove the Purge line and skirt from the first print so my next print doesn't go through it.  Then print BadgeLayer1b in the second color.  Keep the bed warm, switch the filament color and purge it.  Remove the prior Purge line and skirt and start the next print job BadgeLayer1c in the third color.  Finally keep the bed warm and switch to your last color and print the badge frame.  If you have layer adheasion issues it is very unlikely the print will succede. 