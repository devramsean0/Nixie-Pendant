mm# 21/05/2025
## Some basic goals:
- 2 Nixie Tubes
- Fully self contained
- "Safe"
- Powered by a battery or USB

## Choosing a tube
I went for [IN-16](https://www.nixies.us/bwg_gallery/in16/) tubes, due to them being vertical.
They are also relatively affordable on Ebay.

IN-16 digits use 2mA and run at 170v, The dot uses .3mA.
These tubes have a diameter of 13mm.

## A rough 2D Design
I then set out to design the rough 2d (top down) shape in Figma.
This allowed me to plan out screw positioning and have a template for PCB shape.

This, while Rough Describes kinda what I'm thinking.
The red circles are where the tubes are going, and the little whitish dots are where the 3 screws will go

![Image of Rough Plan](Journal/Images/2025-05-21-rough-plan.png)

I do need to remember that it is 4x actual size.

The plan is 3 long screws that will go the whole way through the body.

## The Physical Stackup
Physically, it's going to be stacked up in a few different layers, In order of top to bottom:
1. Socket PCB (Tubes are soldered into here, will be sturdier than using an actual socket
2. High Voltage PCB (The control transistors, Boost Converter etc)
3. Low Voltage PCB (Battery Management, Charging, Micrcontroller
4. Battery


