# Introduction

This is a basic Surge Protector PCB. It features robust large traces for high current carrying capacity and ensuring safety by preventing heating along unexpected regions. This board features an extremely small form factor of 61.6mm x 36.3mm so that it can be easily incorporated in any housing. It also features 3 M2 mounting points for securing the board to the housing. It is designed as a single sided pcb to reduce costs. 

Continuous Duty Electrical Rating: 250V/13A/50Hz/3250W   
Maximum Energy Dissipation: 396J    
Maximum Spike Current: 12,000 A   
Response Time: Less than 1 nanosecond
Maximum spike voltage: 6kV

Features Include:   
Thermal Resettable Fuse  
Low Cost  
Small Footprint  
 


# Schematic

<img src= "https://github.com/RandomDelta6/USB-Mouse/assets/53912269/448d8964-b8b8-4f8a-9179-4dc1928ab4a5"  width="750"> 


# PCB

<img src="https://github.com/RandomDelta6/USB-Mouse/assets/53912269/42b22267-ad44-4c84-bf96-2bf08c58f96c" width ="500">        

PCB Back View

<img src="https://github.com/RandomDelta6/USB-Mouse/assets/53912269/ecdb3ff5-6b36-43cb-a74d-336807115d50" width ="500">

PCB Front View


# Usage

Proceed to place all components on the back of the board. Use 10AWG Wires for Input Cabling. 

It is to be noted that +5VSB commences at the PSU Connector end and terminates at this board while +12VSB originates at this board and continues to the ATX12VO Motherboard Connector. +12V and GND wires are to run across the cable from the PSU connector end to the motherboard connector end and the +12V and GND connections for this board may use wires spliced in with the +12V and GND wires running across the cable or have dedicated wires run through the PSU connector end to the +12V and GND terminals of this board. The inline circuit assembly maybe encapsulated with a heatshrink for better isolation. It can then be bundled together with the other wires running across the cable and be sleeved together. 

# Notes

All items are mounted on the back of the board. A 23AWG wire (0 ohm link) should be run across the back of the board from Epass1 to Epass2. Solder mask is not used on either side of the board. It is not used on the front to allow for deposited solder to increase current carrying capacity. It is not used on the back since it is not required. All copper traces are on the front side of the board only as a cost saving measure. NPTH maybe used to reduce cost further. 

The Fuse and MOV Array maybe encapsulated in a piece of heatshrink tube of sufficient size.  The Brass rails used for Live and Neutral supply in the Surge Protected Power Strip are expected to be soldered directly to the PCB. The brass strip should be slid in from the back side into the appropriate slit marked for it, folded down on the front side and then soldered onto the large flat pad for it. Dip soldering is recommended for the pcb assembly.

Plastic Prongs or Screw Posts maybe provided on the frame for mounting the PCB. 3 M2 holes are provided on PCB for attaching via screws or plastic push pins.  Flat Plastic Protrusions maybe used as guides for PCB placement as well as enhanced isolation, they are expected to slide into the long rectangular cutouts between L out and N out traces and N and E traces.

Couldn't find a proper model for Thermal Circuit Breaker, so it is missing in PCB view.

This project was made with Kicad 7.0 .
Generate gerbers as per specifications of the fab of your choice.


# Disclaimer
This board has not been printed and tested physically to verify functionality. I do not assume any liability for the materials, information and opinions provided on, or available through, this project. I disclaim any liability for injury, death or damages resulting from the use thereof. Modify or work on it at your own risk.

# Licensing
All PCB design files and hardware are released under the [Creative Commons Attribution Share Alike 4.0 license](https://choosealicense.com/licenses/cc-by-sa-4.0/). 

Commercial Usage strictly disallowed.
