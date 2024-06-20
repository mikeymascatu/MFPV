# MFPV (Modular First Person View Drone System)
## Modular Open-Source 3D-Printed Frame System for FPV-based (4"-5") drones
### Designed for the 2024 Technology Student Association (TSA) UAV Challenge and meets all physcial and safety requirements

![image](https://github.com/mikeymascatu/MFPV-delivery/assets/166886630/6c68a1ef-2568-4084-9870-977f66e36d11)

### This system fits standard FPV parts and is relatively easy to work on. It comprises of mostly standard mounting other than the modular connector.

### Additional Info
STLs will be on model sharing sites:

[OnShape](https://cad.onshape.com/documents/be780221657184ef5af6f876/w/e20a2d3bc301348a674d5dc5/e/4542c18d6307ccf997ffdbc9?renderMode=0&uiState=667372c694107d685f381607)

## Features and Specs:
 - Fully 3D-printed (other than hardware) 
 - Support for 5" propellers 
 - No glue required! (other than RX mounting)
 - Modular mounting on the bottom frame
 - Space for most Analog/Digital FPV cameras (Mounting not included, will require a custom designed solution)
 - Cooling for critical components
 - Super easy and quick to print (About 3 hours on “Next-gen" printers. Closer to 6-9hrs on slower printers)
 - Also doesn't require much fine-tuning due to very relaxed tolerances. 
 - Easy to acquire hardware (just any M3 screw and standoff kit will work, round head works best)
 - Easy routing for XT60 wires/most other cables
 - Uses roughly ~70g of filament for the frame (About 200g total for the entire platform)
 - Super easy to make brackets for
 - Can be printed on beds the same as or larger than an i3 (at least 220mm x 175mm)
 - No post processing (assuming your printer has no issues)
 - STL and STEP files for printing and design changes.
## Compatible Parts 
 - Fits 30.5mm x 30.5mm FC Stacks 
   * (Preferably SpeedyBee F4 or F7 line “full size” stacks)
 - Fits 20mm x 20mm Analog VTX
   * Built around the SpeedyBee TX800, but most should work.
 - Fits 16x16mm motors
   * Fits 2207 or larger natively.
   * Could fit smaller motors (2203, 2203.5, 2205) with adapters or changes of the B frame.  
 - Fits SMA adapters 
 - Hole for RX antenna 
 - Fits battery straps 
   * (Designed around 4S Li-Ion packs but will fit most small-medium Li-Po packs) 
## Warnings/Notes

### FOR U.S. MAKERS:
 - This design is **VERY LIKELY**  over the FAA's <249g “no registration” limit so using the FAA's “Remote ID” is likely needed.
   *  (For what I'm doing, I don't need a module so I won't have brackets on my page, but it's super easy to make brackets in CAD)
 - This design makes a drone roughly ~700g so please check your local UAV guidelines before proceeding 

### It is 3D printed plastic at the end of the day so it won't take that many crashes.
**It certainly isn't THAT light so I wouldn't recommend racing or freestyling.**

## Printing 

 - YOU MUST USE AN ADVANCED FILAMENT FOR THE B FRAME. PLA causes MANY ISSUES WITH FLIGHT. Currently testing ABS-CF but PA-CF or PC may be better options. You can use PLA on the other components though.
 - An enclosure is recommended for at least the B and A frame.
 - You can also use this model for CNCing Carbon fiber for best results.
 - This is part of high-school engineering project so this isn't a optimal design at all. 
 - Use the 0.2 strength/structural setting in PrusaSlicer (and its forks) or whatever slicer you're using (>25% infill, 6 walls).
 - This is considered a “All in one” frame so breaking an arm does require an entire reprint and reinstallation of the B frame.
 - This design is built around Metric screws and measurements due to the precise scale of the design.
 - Again, this project is relatively easy to print but I haven't tested outside of Bambu Lab printers so YMMV on your printer. If it can print most large objects just fine, you're probably be okay printing this.
 - The entire bottoms of frame components completely touches the print plate but USE BRIMS IF YOU CAN'T 100% TRUST YOUR PRINTER'S BED ADHESION (Especially if using glass or “hacky methods” like masking or Kapton tape). 
 - It WILL COME OFF the bed if you let it!!
 - The screw hole's first layer  may come off the build during the first layer. (Even on PEI). The rest of the frame should just hold the rest of the screw hole
 ## Important Note (Betaflight)
 - Using a 3D printed frame may cause vibrations that may interfere with your FC's Gyro. This may lead to take-off without throttle. Lower the lowpass filter in RPM filtering settings to counter this. 
 - **USE THIS DESIGN AT YOUR OWN RISK. I'M NOT RESPONSIBLE FOR CRASHES OR PROPERTY DAMAGE CAUSED BY THIS DESIGN.** 
 - **IF YOU DON'T BEILEVE IT'LL FLY, THEN DON'T USE THIS DESIGN.**

## Required Hardware:
### Frame:
 - X12 6mm M3 screws (to hold both frame components together)
   OR X6 6mm M3 AND X6 12mm M3 (if using "blade" landing gears)
 - X4 6mm M3 screws (to secure VTX standoffs)
 - X6 25mm M3 Standoffs (to provide space within frame)
 - X4 12mm  M3 Standoffs (VTX)
### Component Mounting:
 - X4 12mm M3 screws (to secure VTX to VTX standoffs)
 - X16 10mm M3 screws (to secure Motors to frame) 
    * *included with most FPV motors*
 - X4 30mm M3 Screws (FC stack to frame) 
    * *Included with most stacks*
 - Use X4 M3 Nuts or 12mm M3 Standoffs to secure everything
   * This was designed around the SpeedyBee F405 V4 stack.
### If using modular adapter:
 - X2 7-12mm  M3 Screws (mounting MFP modular adapter)
 - X2 6mm M3 Nuts (metal or plastic)

## Included Components:

### Core Frame
- A Frame (DroneFrameA) = The upper frame
- B Frame (DroneFrameB) = The lower frame

### Additional Frame Components
- Prop Guards (bumperv3) = X4
### Landing System


## Assembly:
*I recommend measuring, cutting, and soldering all wires before hand as soldering next to plastics might not be a good idea. Remove all non-soldered connectors before starting.* 

### Standoff Installation
Insert X6 6mm M3 Screws through the sides of the B frame
Use 12mm M3 Screws if using the “Blade” landing gear
If using the Landing gear, Sandwich the gear bracket like: 
Screws, Bracket, B frame, and Standoffs
Catch the end of the screw using the 25mm Standoffs
Insert X4 6mm M3 Screws through the “smaller square section” (Labeled VTX)
Catch the screws using X4 12mm M3 Standoffs
Install Modular Connector
Run battery straps through the side slots on the A frame.
FC/ESC Installation
Ensure rubber spacers are installed on both ends of the stack 
Insert X4 30mm M3 Screws through the “Center square holes”
Catch the screws using the stack. There may be some resistance, this is normal.
Secure the board using the nuts or 12mm standoffs 
The screws should be flush with the 
Install your custom camera brackets on the standoffs
Motor Installation
Align each direction motor with each arm
Insert X4 10mm screws per motor (16 in total)
If using the MFPV Guards, Sandwich the guards like so:
Screws, Guards, B Frame, and Motors
VTX Antenna
Between the 2 holes marked “ANT” on the A frame, use the larger hole to attach your VTX antenna
The threads on the antenna adapter should tap into the plastic with the cable on the opposite side of the text and markings (the side that contacted the build plate during printing)
Secure the cable by using the nut on the other end using a 8mm hex wrench.
 
