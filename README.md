# MFPV (Modular First Person View Drone System)
## Modular Open-Source 3D-Printed Frame System for FPV-based (4"-5") drones
### Designed for the 2024 Technology Student Association (TSA) UAV Challenge and Hack Club Arcade and meets all physcial and safety requirements for TSA (not airport security).

![image](https://github.com/mikeymascatu/MFPV-delivery/assets/166886630/6c68a1ef-2568-4084-9870-977f66e36d11)

### This system fits standard FPV parts and is relatively easy to work on. It comprises of mostly standard mounting other than the modular connector.

### Additional Info
STLs will be on model sharing sites:

Printables and MakerWorld Links coming soon!

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
- Landing blades

## Assembly:
*I recommend measuring, cutting, and soldering all wires before hand as soldering next to plastics might not be a good idea. Remove all non-soldered connectors before starting.* 

**Use the OnShape Link as a refernce to assemble**

### Standoff Installation
 1. Insert X6 6mm M3 Screws through the sides of the B frame
    - ![image](https://github.com/mikeymascatu/MFPV/assets/166886630/785f3c7b-c602-4cbd-be68-b017ad40d562)
 2. Use 12mm M3 Screws if using the “Blade” landing gear
     - Build the Landing Gear System using the Folding Landing System (FLS) wiki before installing
 3. If using the Landing gear, Sandwich the gear bracket like: 
     - Screws, Bracket, B frame, and Standoffs
 4. Catch the end of the screw using the 25mm Standoffs
     
 5. Insert X4 6mm M3 Screws through the “smaller square section” (Bottom to Top)
     - ![image](https://github.com/mikeymascatu/MFPV/assets/166886630/fb3fbb42-0b28-48e3-aaa0-a01b3f9f30b3)
 6. Catch the screws using X4 12mm M3 Standoffs
 7. Install Modular Connector (Optional) 
      - ![image](https://github.com/mikeymascatu/MFPV/assets/166886630/01982acb-d9ea-4604-aea2-32ab8f33383e)
      - Install X2 M3 12mm Screws through the center holes of the B frame. (Top to bottom).
      - Insert the modular connector and secure with M3 Hex nuts
 8. Run battery straps through the side slots on the A frame.
### FC/ESC Installation
 1. Ensure rubber spacers are installed on both ends of the stack 
 2. Insert X4 30mm M3 Screws through the “Center square holes” (Bottom to Top)
    - ![image](https://github.com/mikeymascatu/MFPV/assets/166886630/6be4bc16-3098-4a39-afab-bb524ae3ccb6)
 3. Catch the screws using the stack. There may be some resistance, this is normal.
 4. Secure the board using the nuts or 12mm standoffs 
     - The screws should be flush with the standoffs
 5. Install your custom camera brackets on the standoffs
     - Don't follow this step if you're using the LandCam Expansion (LCE). Follow the Wiki.
     - Install your camera at this point if going custom.
### Motor Installation
1. Align each direction motor with each arm
2. Insert X4 10mm screws per motor (16 in total) (Bottom to Top)
   - ![image](https://github.com/mikeymascatu/MFPV/assets/166886630/652a0be0-3ee4-429f-9aaa-3231b1a2c0a7)
   - If using the MFPV Guards, Sandwich the guards like so:
      * Screws, Guards, B Frame, and Motors
3. Tightly Secure Screws
### VTX Antenna
1. Between the 2 holes marked “ANT” on the A frame, use the larger hole to attach your VTX antenna cable
   - ![image](https://github.com/mikeymascatu/MFPV/assets/166886630/9330ed72-a63a-4be9-8d09-1510374b010a)
2 The threads on the antenna adapter should tap into the plastic with the cable on the opposite side of the text and markings 
   - (the cable should be perpendicular the side that contacted the build plate during printing)
3. Secure the cable by using the nut on the other end using a 8mm hex wrench.
4. Screw on the VTX antenna.

### VTX
1. Run the battery cables under the VTX area
   - ![image](https://github.com/mikeymascatu/MFPV/assets/166886630/70772937-e08c-4c17-a9ee-dcda683b71b8)
2. Lay the VTX (heatsink up) on top the 12mm standoffs.
3. Secure the VTX with 12mm Screws
4. Connect the VTX antenna cable to the VTX and the VTX cable to the FC

### Recievers

Follow the Wiki for more information

### Final Frame Assembly

1. Route the XT60 cable through the large hole of the A frame
   - ![Screenshot 2024-06-20 120815](https://github.com/mikeymascatu/MFPV/assets/166886630/cd05ce85-0651-4e7d-a24d-f02defc8fea9)
2. Press the A frame on the drone.
- ![image](https://github.com/mikeymascatu/MFPV/assets/166886630/05808535-7d0e-41a4-b893-54553bd9d2f1)
- The A frame will bend around the FC stack, this is normal and allows for a secure fit.
3. Secure the A frame with 6mm screws.
4. Secure the battery with battery straps
5. Connect all cables (other than XT60) if not already
6. Plug into BetaFlight and Configure
   
