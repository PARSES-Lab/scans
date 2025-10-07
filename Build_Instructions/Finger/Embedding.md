---
layout: default
title: Embedding
parent: Finger
nav_order: 5
---

# TPU Exoskeleton Printing and Fiber Embedding

Printed parts:
- Finger fiber trimming jig

Materials:
- Loctite [number]
- Ziro 95A TPU
- 1.5mm PMMA fiber


Equipment:
- FDM 3D printer (with 0.4mm nozzle)

## Printer Setup 

### Slicer Settings

Insert a pause print on layer line [] and layer line []. Ensure that the pause happens before these lines start and not after. 

The important slicer settings we used are:

- insert settings

### A Note on Printing

The printer we used was a Voron 2.4 with a textured PEI build plate. The choice of printer shouldn't matter so much, as long as you have control over the slicer and machine GCODE. Keep in mind that you will need to embed components, and having easy access to the build plate from multiple angles makes this easier. 

## Printing

### Preliminary Steps:

Cut a roughly [mm] long section of 1.5mm PMMA fiber. Also ensure you have two cladded fiber-and-prism composite parts, one shorter and one longer. 

### Step 1: 

Prior to printing the exoskeleton, print 6 TPU prisms. These will sit in the cavity above the prism when embedding the two cladded spectral fibers.

### Step 2:

Once the print pauses for the first time, inspect the track for the U-shaped waveguide. Ensure that there are no blobs of filament stuck in the track, and remove them if they are. Once verified, deposit 5-6 small dots of Loctite along the waveguide track, and then lay in the 1.5mm PMMA fiber. Ensure that the fiber is not sticking up past the paused layer. Allow the Loctite to set for a few minutes, then resume the print.

### Step 3:

Once the print pauses again, deposit 4-5 small dots of Loctite along each spectral fiber track, and lay the spectral fibers in. Take extra care around the prism cavity, and gently press the prism into place. Once laid in, put a TPU prism on top of each prism, and resume the print.

### Step 4: 

Once the print is finished, remove it from the printer, and remove all support material. If there is excessive stringing and blobbing, then use a heat gun/solder reflow gun on a medium-low heat. Next, using the fiber trimming jig and a razor blade, trim all fibers. Finally, using a razor or X-acto knife, trim away the exposed cladding of the spectral fibers so only the PMMA extends past the TPU exoskeleton.


## Troubleshooting

Common points of failure:
- TPU not bridging well
- TPU getting stuck during embedding
- support material not releasing cleanly
- other TPU print issues
