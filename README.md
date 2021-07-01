# Artillery Genius to Switchwire
This is my journey in converting an Artillery Genius to Switchwire.

<!-- <img src="https://user-images.githubusercontent.com/44800440/124162775-21673800-da9f-11eb-9416-9d70eb20ef93.jpg" width="650" height="650"> -->

<p align="center">
  <img width="650" src="https://user-images.githubusercontent.com/44800440/124162775-21673800-da9f-11eb-9416-9d70eb20ef93.jpg">
</p>

## This conversion is based on [Gizzle’s Ender 3 conversion](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/Gizzle/ender-3_(pro)_switchwire "Title")

I reused the following parts:
* motor mounts
* upper blocks assembly
* Z bearing blocks

## Build information
This mod will shorten the X travel by 10mm because of the narrow vertical extrusions but you will gain 20mm of travel in Z. \
**The build volume is 220x230x270** \
Note: _You will need to drill a hole into the metal sheet to pass the afterburner cables._

## Build overview
_Front and Left_
<p align="center">
  <img  width="1850" src="https://user-images.githubusercontent.com/44800440/124168000-d94b1400-daa4-11eb-9fbe-f04007028a12.jpg">
</p>

_Back and Right_
<p align="center">
  <img width="1850" src="https://user-images.githubusercontent.com/44800440/124167592-79546d80-daa4-11eb-8a0e-a14a48bedca4.jpg">
</p>

## Reuse parts
You can reuse a good amount of parts from the Genius:
* MCU (Mks gen L)
* PSU
* Y assembly
* All the stepper motors except the extruder one
* 4020 blower
* 4010 fan
* 2040 vertical extrusions \
**At the moment, the TFT screen is not compatible with Klipper, you won’t be able to use it.**

## BOM (still not complete)
[See the Switchwire BOM for links to products](https://vorondesign.com/sourcing_guide?model=VS)

### Frame
* 2020 extrusion 320mm – 1pcs (top extrusion)
* 2020 extrusion 310mm – 1pcs (bottom extrusion) \
### Motion
* MGN12H linear rail 330mm – 2pcs (z axis)
* MGN12H linear rail 270mm – 1* pcs (x axis)
* GT2 belt – 5 meters
* GT2 20t pulley – 3 pcs
* F695 Bearing – 20 pcs
### Electronics
* Raspberry for running klipper
* SPDT KW10 Limit Micro Switch (for x-axis)
* Omron TL-Q5MC2 - NPN Inductive Probe (if you want bed mesh leveling,I reused the stock endstop for z)
* 20mm NEMA17 for the extruder (NEMA17 Motor 17HS08-1004S)
### Misc
* Loctite Blue Threadlocker (or nail polish)
* Key-Bak (you can use this cheaper alternative (https://it.aliexpress.com/item/1005001273995297.html)

### Cable Management	
* 24 AWG PTFE
* 20 AWG PTFE
* 10x11 Cable Chain
* connectors

### Fasteners
**Still need to count them**

### Extra
* hardware for the Afterburner (check sw bom)

## GCODE buttons mod
To cover the unused usb port I created a keyboard of 4 buttons that call a gcode macro. \
Buttons used: 12x12x4.3 => [aliexpress](https://it.aliexpress.com/item/32807507828.html)

<p align="center">
  <img  width="1850" src="https://user-images.githubusercontent.com/44800440/124180973-351d9900-dab5-11eb-9749-827404ca9a8c.jpg">
</p>

Solder one side of the button to a data pin, the other goes to GND. \
Then close the lid and route the cables through the usb hole.
<p align="center">
  <img  width="550" src="https://user-images.githubusercontent.com/44800440/124181505-dc023500-dab5-11eb-80a6-2b119d3cbf13.jpg">
</p>

Product in action
<p align="center">
  <img  width=450" src="https://user-images.githubusercontent.com/44800440/124181923-75314b80-dab6-11eb-875b-5967de32c5db.jpg">
</p>


