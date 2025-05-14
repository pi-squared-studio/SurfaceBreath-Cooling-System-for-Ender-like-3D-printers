# SurfaceBreath Cooling System (for Ender-like 3D-printers)
_Simple thing to increase quality of yours 3D prints_

## Features

**Description:**	This device is an additional cooler for the printed part to improve product quality. The main purpose is to ensure uniform cooling of the upper layer of the part, against the formation of overhangs bending upwards.

**Designer:**  π²Studio

**Designed for:**	Voxelab Aquila C2

**Compabtility:**	Creality Ender-3 and its clones with 235 mm bed width.

**Mount:**		at backside of X-axis 	


## Overview

In my practice, I have encountered the problem of breaking off a part of a part (or even the entire part) from the bed during the printing process. When I began to study this problem, it turned out that the curved overhangs rising up from the temperature were to blame for everything. This was due to the fact that the part was still heated from the table, and although its temperature was lower than the temperature of the softened plastic, the additional heat radiated from the hotend was enough for this process to take place. Even the cooling of the standard fan, baked at 100%, was not enough to stop this process, which could start a few centimeters away from the cooling stream.
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
A set of the spacers of various thicknesses allows you to fix the duct at almost any acceptable distance from the frame so that they don't touch various other printer mechanisms. In the version with tubes without a lamp, it will be enough for a standard printer to make one spacer with a thickness of 3 mm.

_SurfaceBreath_ can also be used as a fan to quickly cooldown the bed, a fan that will blow over the extruder elements from accidental melting during idle time, or to provide of air microcirculation in the thermoenclouse, if such is used.

## Bill of materials

1. 70X0 axial fan - 1 pc. I used the 7020 quiet model from an old 12-volt computer cooler, but you can use any other suitable 70x70mm size (for example, 7010, 7015 or 7030...) with any power supply voltage. If it is 24V, then it will be possible to power it from a printer's PSU. If you get one with a different voltage, then make a voltage stabilizer for it or take a separate power supply. It's a good idea to use any speed control for this fan.
2. M5 EU#20 profile T-nuts - 2 pcs. For attach the duct to frame.
3. M5 bolts - 2 pcs. Their total length should be 6-8mm out of contact surface + the distance of all used spacers. You may use a set of M5x10x1 washers for compensate extra length of bolts. In other words, the ledge of the bolt deeper into the frame should not exceed 5mm.

4. Self-tapping screw OD 3mm  - 4 pcs (For screwing of the fan). Their total length should be 5-10mm + the thick of the fan.
5. Self-tapping countersunk screw OD 3mm  - 2 pcs (Optional. For mostly screwing thin, near the duct, 3 or 5mm spacer). Their total length should be 6-9mm + the distance of attahed spacer.
6. Any suitable desired LED strip with a width of not more than 12mm, and a length of not more than 230mm, and a thickness of not more than 2.5mm. (For the option with a light). A dimmer is also welcome.

## Print conditions

The duct and spacers are printed from the plastic from which subsequent products will be printed, and this material must withstand the temperature of a heated bed. ABS will be an ideal option for everyday tasks, but you will need to ensure the internal strength of the part so that it does not come off the bed and does not get upset during printing.
0.2 - layer thickness (0.3 if you want quickly), 3-4 wall loops, 10% infill enough - the part does not experience heavy loads. Print without support, but make sure that the overhang bridges print well.  A raft is allowed to increase the strength of the attachment to the bed.

The diffusing glass is printed from transparent PETG. 2 walls. Different density fillings can be applied for various dispersion. I prefer 20% gyroid filling.
