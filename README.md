# SurfaceBreath Cooling System (for Ender-like 3D-printers)
_Simple thing to increase quality of yours 3D prints_

![Compare the cooling 3](https://github.com/pi-squared-studio/SurfaceBreath_Cooling_System/blob/main/media/Compare3.png)

## Features

**Description:**	This device is an additional cooler for the printed part to improve product quality. The main purpose is to ensure uniform cooling of the upper layer of the part, against the formation of overhangs bending upwards.

**Designer:**  π²Studio

**Designed for:**	Voxelab Aquila C2

**Compabtility:**	Creality Ender-3 and its clones with 235 mm bed width

**Mount:**		at backside of X-axis rail. The height of the duct above the bed is 5 mm when using a standard nozzle downgrade.


## Overview

![Overview Front](https://github.com/pi-squared-studio/SurfaceBreath_Cooling_System/blob/main/media/Overview%200000.jpg)

In my practice, I have encountered the problem of breaking off a part of a printing model (or even the entire model) from the bed during the printing process. When I began to study this problem, it turned out that the curved overhangs rising up from the temperature were to blame for everything. This was due to the fact that the part was still heated from the table (although its temperature was lower than the temperature of the softened plastic), and the additional heat radiated from the hotend, which was enough for this process to take place. Even the cooling of the standard fan, baked at 100%, was not enough to stop this process, which could start a few centimeters away from the cooling stream.
The second problem, after I adjusted all the temperature and speedy settings, and the parts no longer came off the bed, was that slightly protruding overhangs could spoil the appearance of the surfaces. This became especially noticeable when using silk PLA in art projects. Defects occurred on both external and internal overhangs. It could either be a non-glossy, furrowed surface, or random "warts" appeared on it.
It was decided to develop an additional cooling system to the existing one in order to remove such defects. This is not a replacement for the standard one, but only serves to optimize the temperature regime at the printing surface. In other words, it "freezes" the topmost layer from accidental additional heating. SurfaceBreath has no additional effect on the main fan flow.

_SurfaceBreath_ creates a very weak laminar flow along the entire print surface, similar to light breathing, and displaces stagnant thermal zones that are not affected by the cooling of the main fan.
Now your printer will not face the problem of the extruder nozzle colliding with the printed part, and its possible separation from the bed!

_SurfaceBreath_ was tested by me for PLA plastics and showed amazing results. According to my estimates, the adhesion of the part itself to the bed has even improved.
There are no definite results with other plastics yet, as I have always had a great experience with PETG.
ABS-like plastics, yes, the small parts like they've started to look a little smoother. I have not tried with large parts made of this plastic, since I do not have a normal thermal case.

In addition, I made another version of the duct with a light. It is convenient to use it to control the printing of the first layer, as it creates contrasting lighting. It can also be used as torch during maintenance.
It uses standard LED strips up to 12 mm wide.

Special set spacers with thicknesses of 3, 5, 10, 20 and 50mm are used for mounting to the X-axis frame.
A set of the spacers of various thicknesses allows you to fix the duct at almost any acceptable distance from the frame so that they don't touch various other printer mechanisms. In the version with the duct without a lamp, it will be enough for a standard printer to make one spacer with 3mm thickness. To raise the duct to a height of 5 or 10 mm, use an appropriate spacer with a thickness of 15 mm.

_SurfaceBreath_ can also be used as a fan to quickly cooldown the bed, a fan that will blow over the extruder elements from accidental melting during idle time, or to provide of air microcirculation in the thermoenclouse, if such is used.

![Overview Front](https://github.com/pi-squared-studio/SurfaceBreath_Cooling_System/blob/main/media/Overview%201.jpg)

## Bill of materials

### Base parts
1. 70X0 axial fan - 1 pc. I used the 7020 quiet model from an old 12-volt computer cooler, but you can use any other suitable 70x70mm size (for example, 7010, 7015 or 7030...) with any power supply voltage. If it is 24V, then it will be possible to power it from a printer's PSU. If you get one with a different voltage, then make a voltage stabilizer for it or take a separate power supply. It's a good idea to use any speed control for this fan.
2. M5 EU#20 profile T-nuts - 2 pcs. For attach the duct to frame.
3. Self-tapping screw OD 3mm - 4 pcs. For screwing of the fan to duct. Their total length should be 5-10mm + the thick of the fan.
4. Self-tapping countersunk screw OD 3mm  - 2 pcs (Optional. For mostly screwing thin, near the duct, 3 or 5mm spacer). Their total length should be 6-9mm + the distance of attahed spacer.
5. Any suitable desired LED strip with a width of not more than 12mm, and a length of not more than 230mm, and a thickness of not more than 2.5mm. (For the option with a light). A dimmer is also welcome.

### Parts for usual variant without rising
6. M5 bolts - 2 pcs. Their total length should be 6-8mm out of contact surface + the distance of all used spacers. You may use a set of M5x10x1 washers for compensate extra length of their bolts. In other words, the ledge of the bolt deeper into the frame should not exceed 5mm.

### Parts for variant with rising
6. M5 bolts - 2 pcs. Their total length should be 13-15mm out of contact surface + the distance of all used spacers before rising part.
7. M5 hex nut - 2pcs.
8. M5x10 bolts - 2 pcs. For attaching a rising part to the frame.

![Assembling Rule](https://github.com/pi-squared-studio/SurfaceBreath_Cooling_System/blob/main/media/Assembling.jpg)


## Print conditions

The duct and spacers are printed from the plastic from which subsequent products will be printed, and this material must withstand the temperature of a heated bed. ABS will be an ideal option for everyday tasks, but you will need to ensure the internal strength of the part so that it does not come off the bed and does not get upset during printing.
0.2 - layer thickness (0.3 if you want quickly print), 3-4 wall loops, 10% infill enough for duct - the part does not experience heavy loads. For spacers need to increase infil upto 50%.
Print without support, but make sure that the overhang bridges print well.  A raft is allowed to increase the strength of the attachment to the bed.

The diffusing glass is printed from transparent PETG. 2 walls. Different density fillings can be applied for various dispersion. I prefer 20% gyroid filling.


## Disclaimers

This model was developed independently by autor and was based on well-known physical principles and phenomena.
Everything described in this article is not a universal case for all such reasons, but is considered only from the perspective that specific experience has been gained.
Any consequences with the use of this device are attributed to the follower who repeated this idea.
The model is in slow development and modification and it may contain some flaws. 
Check all dimensions and mounting options before you print these parts!
Please note that repeated it is possible that the model may be changed or reinterpreted, embodied in a new form.
All new modifications or additional improvements will be posted on this page: https://github.com/pi-squared-studio/SurfaceBreath_Cooling_System
