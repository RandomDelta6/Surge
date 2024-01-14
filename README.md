# Introduction


This is a Surge Protector PCB. It features robust large traces for high current carrying capacity and ensuring safety by preventing heating along unexpected regions. This board features an extremely small form factor of 61.6mm x 36.3mm so that it can be easily incorporated in any housing. It also features 3 M2 mounting points for securing the board to the housing. It is designed as a single sided pcb to reduce costs. 

Continuous Duty Electrical Rating: 250V/13A/50Hz/3250W   
Maximum Energy Dissipation: 476J    
Maximum Spike Current: 13,000 A   
Response Time: Less than 1 nanosecond


Features Include 
> Thermal Resettable Fuse
> Low Cost
> Small Footprint
> 


# Schematic

<img src= "https://user-images.githubusercontent.com/53912269/232120125-1deb1704-0188-4783-b5d2-be8cb820dbed.png"  width="750"> 


# PCB

<img src="https://user-images.githubusercontent.com/53912269/232188920-34c76fb8-cfb7-4699-81d4-b1005601bacc.png" width ="250">        

PCB Front View

<img src="https://user-images.githubusercontent.com/53912269/232189052-a326f1e7-1ed4-454e-8c3d-7d5ca8a89cb7.png" width ="250">

PCB Back View


# Usage

Proceed to place the diode and inductor on the back, these are held in place via the adhesive. Then place the front smd components and reflow solder the entire assembly. Thread in the cables from the back and solder onto the front side, ensure enough solder flows to make a solid connection through the plated through hole and solder flows across to the exposed contact on the back side. Please note that +12V and GND terminals are pretty close, ensure the terminals are not bridged during soldering.

It is to be noted that +5VSB commences at the PSU Connector end and terminates at this board while +12VSB originates at this board and continues to the ATX12VO Motherboard Connector. +12V and GND wires are to run across the cable from the PSU connector end to the motherboard connector end and the +12V and GND connections for this board may use wires spliced in with the +12V and GND wires running across the cable or have dedicated wires run through the PSU connector end to the +12V and GND terminals of this board. The inline circuit assembly maybe encapsulated with a heatshrink for better isolation. It can then be bundled together with the other wires running across the cable and be sleeved together. 

# Notes

All items are mounted on the back of the board, 

Although I am pretty confident the board should work, you might still wish to have the board verified by a professional.Couldn't find a proper model for Thermal Circuit Breaker, so it is missing in PCB view.

This project was made with Kicad 7.0 .
Generate gerbers as per specifications of the fab of your choice.


# Disclaimer
This board has not been printed and tested physically to verify functionality. I do not assume any liability for the materials, information and opinions provided on, or available through, this project. I disclaim any liability for injury, death or damages resulting from the use thereof. Modify or work on it at your own risk.

# Licensing
All PCB design files and hardware are released under the [Creative Commons Attribution Share Alike 4.0 license](https://choosealicense.com/licenses/cc-by-sa-4.0/). 

Commercial Usage strictly disallowed.
