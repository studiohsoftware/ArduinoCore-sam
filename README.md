# Arduino Core for SAM3S CPU

This repository contains the source code and configuration files of the Arduino Core for Atmel's SAM3S processor (used on [Studio H Modules](https://www.studiohsoftware.com)). 
The main modification is to the USB code, which is different on the SAM3S because the USB hardware is different.  

## Installation 
 
Create a folder called "hardware/fba/sam" in your sketches folder. Place the contents of this repository into that folder. 
This will add a new boards entry called "Arduino ARM (32=bits) Boards (in sketchbook)->Fueled by Anger (SAM3S)."


