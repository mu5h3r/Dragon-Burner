# Dragon Burner v7 BETA

This is the BETA release for the next iteration of the Dragon Burner toolhead.

Assembly is much the same as for the v6, so you can follow the instructions for that version.

NOTE: This is a BETA version. Parts and their assembly can change and may require the reprinting of the whole toolhead. CAD will not be available until release. If you only have a single printer, please be sure to keep your old toolhead in case of issues with this one.

![](images/front.png)

![](images/back.png)

## Changes:

- New aesthetic for the toolhead

- Hotend moved back by 2mm to be closer to the stock toolhead position

- All new fan ducts. Size increase by 60% and tuned with CFD to improve part cooling

- Bambu Labs X1 hotend support

- Phaetus Taichi hotend support

- LED mounts separated from cowl to reduce number of cowls required and improve ease of installation and removal of the LEDs

- 3010 hotend fan placed inside of the cowl

- 3010 hotend fan position raise to better target cooling and improve support for volcano height hotends such as the Rapido HF and the Dragon + volcano heat block (without extender). This replaced the support for those hotends from the Rapid Burner

- Right hand cable channel reduced in width to allow support for the Bambu Labs X1 hotend. This means that bundles of wire, e.g. LED wires, should be routed through the left hand channel

- Improved Bowden mount that uses ECAS 4mm PTFE retainer and improved strain relief

- To provide more space for cables snip off the screw lugs at the top rear of the 4010 fans as shown in the second picture above

- Removed the 4010 retainer lug on the cowl and lengthened to retaining guides to hole those fans in place

- Removed unnecessary self tapping screw holes from the cowls

- Updated the KlickyNG cowl orientation

- Modified the ZeroClick cowl to have an integrated mount and include replacement shorter Z rail stops

## Changes 2023-07-07

- Modified SlideSwipe cowl to have matching ducts

- Added fan air redirection fins to all cowls to help with hotend cooling

- Added E3D V6 hotend support

- Added Orbiter v1.5 2.85mm filament support for E3D V6 hotend

- Added shortened rail stops for ZeroClick cowl

- Improved printability of the neopixel mount

- Improved retention of the LED mounts

- Modified LED mounts to allow more room for hotends

- Modified Bambu and Taichi hotend mounts to cater for the cowling fins

- Shifted the 3010 hotend fan up a little more

## Notes:

- Moving the hotend back 2mm means that you should redefine your X and Y limits to account for the new position. It will also mean that any toolhead PCB mounts that utilise the additional connections on the rear of the v0.2 X carriage will need to be altered to account for those 2mm

- The new support for two hotends are mostly untested and may need tweaking

- This toolhead is approximately 1.5mm in depth compared to the miniSB which means it may come in contact with a v0 door at extreme Y. If this does cause problems, you may need to reduce your Y axis limit by 1-2mm

- The new nozzle LED mounts contain removable supports that help printability and should be removed

- It is simpler to load the 4010 fans before adding the hotend + mount to the toolhead. Conversely, remove the 4010 fans before removing the hotend + mount

- Take care when handling the new cowl. There are thin sections that can be easily broken without care. The toolhead will become much more rigid once the fans are mounted

- Rapid Burner v7 BETA will be released when I'm finished with it

**Please contact me on Discord to provide feedback (@chirpy__) good or bad. I can't promise to make suggested changes but will try and accommodate what I believe will improve the toolhead**
