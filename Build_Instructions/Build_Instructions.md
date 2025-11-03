---
layout: default
title: Build Instructions 
has_children: true
nav_order: 3
---

# Build Instructions

The SCANS gripper is comprised of three SCANS fingers, the lasercut baseplate, and the wiring and pneumatic harness to handle the electrical and air lines to the fingers. This guide will walk you through the fabrication and assembly of each component. 

## 3D Printing

### Rigid Components

To begin, 3D-print all of the components in the [Bill of Materials]({{ '/Build_Instructions/Bill_of_Materials/' | relative_url }}), and have the PCB's fabricated. All of the rigid parts were printed on a Markforged X7 with a 0.4mm nozzle and a 0.1mm layer height at the default settings for Onyx (Carbon-Fiber Nylon). The printing orientation of the parts should be evident from their design, and a sample buildplate has been provided below.

All of the files are located in the [CAD](https://github.com/PARSES-Lab/scans/tree/main/CAD){:target="_blank"} directory in the SCANS repo. Both STL and STEP files have been provided, and additional STEP files have been provided for each major composite part to help visualize the completed assembly.

The printing orientation of the parts should be evident from their design, and a sample has been provided below. Support material shouldn't be necessary for any of the rigid components, but we used support material for the just the ribs of the TPU exoskeleton.

### TPU Components

The printer we used was a Voron 2.4 with a textured PEI build plate. The choice of printer shouldn't matter so much, as long as you have good control over the slicer. Additionally, you will need to embed components, and having easy access to the build plate from multiple angles makes this easier. Additional slicing and printing instructions are detailed in the [Embedding]({{ '/Build_Instructions/Finger/Embedding/' | relative_url }}) page.


### Acrylic Baseplate

The baseplate was made out of lasercut acrylic, with mounting holes for installation on a UR3 arm. To accommodate other mounting styles, a blank STEP file with no mounting holes has been provided [here](https://github.com/PARSES-Lab/scans/blob/main/CAD/Gripper/STEP/Baseplate_Blank.STEP){:target="_blank"}.


