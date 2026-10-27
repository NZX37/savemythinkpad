# SaveMyThinkpad
<img width="1241" height="510" alt="image" src="https://github.com/user-attachments/assets/de23fe40-6837-45d3-a3cc-86e7917faa88" />

A two-piece printed frame for a Lenovo ThinkPad L13 2-in-1 Gen 5, with a V-slot style rail on the rear and removable accessory mounts. This is a prototype; check fit and clearances on your own laptop before printing it.

## Files

`SaveMyThinkpad.step` is the CAD assembly. The `STLs/` folder contains these printable parts:

| File | Qty | Purpose |
| --- | ---: | --- |
| `BackFrameLEFT.stl` | 1 | Rear frame with the integrated rail |
| `BackFrameRIGHT.stl` | 1 | Rear frame with the integrated rail |
| `FrontFrame.stl` | 1 | Front frame half |
| `Vpositive.stl` | As needed | Standard rail mount / attachment interface |
| `VpositiveWideBase.stl` | As needed | Wide-base rail mount variant |
| `USB Holder.stl` | As needed | USB holder |
| `Pen Holder.stl` | As needed | Pen holder |
| `Mic holder.stl` | As needed | Microphone holder |
| `Spacer.stl` | As needed | Fills a gap along the rail |
| `Hold-Open(2x).stl` | 2 | Hold-open clips |

## Bill of materials

Costs below are in SGD. The bolt purchase is recorded as one pack, but the pack quantity and the number of bolts used in the assembly were not logged. The project's journal mentions M3 nut-and-bolt attachments; exact sizes and counts for those and the frame fasteners still need to be confirmed.

| Item | Qty | Supplier / basis | Cost (SGD) | Notes |
| --- | ---: | --- | ---: | --- |
| M3 x 8 mm stainless steel hex-socket bolts | 1 pack purchased; assembly qty TBD | [Amazon.sg](https://www.amazon.sg/gp/product/B002A5TN4W/ref=ox_sc_act_title_2?smid=A78PUD8UBC03E&psc=1) | 14.08 | Recorded purchase; pack contents not recorded. Confirm which frame joints use these. |
| M3 nuts to suit the attachment bolts | TBD | To be sourced | TBD | Use for rail attachments. |
| 3D-printing filament | Slicer estimate | Filament or print-service quote | TBD | |
| Shipping | 1 recorded estimate | Recorded shipping | 8.73 | |

## V-rail source and design changes

The starting V-slot profile was the [20 mm x 20 mm linear rail model on GrabCAD](https://grabcad.com/library/v-slot-20mm-x-20mm-linear-rail-aluminum-profile-1). The STEP model was meshed and converted before it was used.

The rail profile is incorporated into the rear frame. I added screw holes and joining features for the front and back frame, standard and wide-base rail mounts, and USB, pen, microphone, spacer, and hold-open attachments.

## Printing

- Material: PLA is suitable for an initial fit check. PETG is an option if more temperature tolerance is needed; test the material and fit because the laptop can get warm.
- Nozzle: 0.4 mm; layer height: 0.20 mm.
- Walls: 3-4; top and bottom: 4-5 layers; infill: 20-30%.
- Place each frame half on its broad face where the slicer orientation allows. Add supports only where the slicer preview shows they are needed, and check the rail profile and clip openings in the preview.
- Slice the parts you plan to use and record the total filament mass to calculate material cost.
<img width="635" height="502" alt="image" src="https://github.com/user-attachments/assets/f037c4c0-ef66-441f-ba83-ba1c0d9d5075" />
Recommended orientation
## Assembly

1. Check the frame halves against the laptop before installing them. Do not force them into place; make sure the vents, ports, hinges, and screen movement remain clear.
2. Align the front and back frame halves and join their matching holes with the M3 x 8 mm bolts and nuts that fit the modeled features. The exact count is not recorded, so check the CAD and test the fit before tightening.
3. Slide the `Vpositive` or `VpositiveWideBase` mount into the rear rail. Add a spacer if you want to fill a gap in the rail.
4. Fasten an accessory, such as the USB, pen, or microphone holder, to its rail mount using the nut-and-bolt arrangement modeled for that attachment. Confirm the fastener size and orientation against the CAD; those details are not in the project notes.
5. Fit the two hold-open clips in their intended positions and check that the laptop can still close. The journal records a redesign specifically to avoid blocking closure.
