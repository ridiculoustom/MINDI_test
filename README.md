<!-- Please do not change this html logo with link -->
<a href="https://www.microchip.com" rel="nofollow"><img src="images/microchip.png" alt="MCHP" width="300"/></a>

# Getting started with Mindi(R) simulation and the AVR DB
This is how you get going in n easy steps
## Download Mindi
Download and install the applicaiton from here:

## Model
Mindi needs a model for the part. Find it.

## Schematic 
Download an example schematic 
<a id="raw-url" href="assets/Voltage_Follower.wxsch">here</a>

## Tweak
Tweak the schematic

## Release
Ship it

## Related Documentation

* [ANxxxx - AVR128DB48 Low-BOM Microphone Interface Using the Analog Signal Conditioning (OPAMP) Peripheral](https://microchip.com/DSxxxxxxxxxx) <!--fill in DS number once it has been assigned-->
* [AVR128DB48 device page](https://www.microchip.com/wwwproducts/en/AVR128DB48)

## Software Used

* [Atmel Studio](https://www.microchip.com/mplab/avr-support/atmel-studio-7) 7.0.2397 or later
* Atmel Studio AVR-DB_DFP version 1.0.21 or later <!-- Not public DFP-->
## Hardware Used

* [AVR128DB48 Curiosity Nano](https://www.microchip.com/wwwproducts/en/AVR128DB48) <!-- Not the correct link, fix when curiosity nano page exists-->
* Electret microphone
* One 2.2kΩ resistor
* One 1µF capacitor

## Setup

* Connect the hardware together as seen in the schematic of the [application note](https://microchip.com/DSxxxxxxxxxx) <!--fill in DS number once it has been assigned-->

## Operation
* Connect the AVR128DB48 Curiosity Nano to a computer using a USB cable
* Download the zip file or clone the example to get the source code
* Open the .atsln file with Atmel Studio
* Press *Start Without Debugging* (CTRL+ALT+F5) to run the application

## Conclusion
After going through this example, you should have a better understanding of how to set up the OPAMP peripheral to amplify weak signals from sensors into detectable signals for the MCU.  

