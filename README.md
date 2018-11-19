# TeensyAV
A two-layer printed circuit board that breaks out a Teensy 3.5 or 3.6. Its primary goal is to provide a front end for the [Teensy Convolution Sofware Defined Radio](https://github.com/compeoree/Teensy-ConvolutionSDR), but can be used for any audio/video project. 
![front](Docs/Front.png "Front View")
![back](Docs/Rear.png "Back View")

# UNTESTED!
This is a work in progress and has yet to be fabricated, assembled, or tested.

# Easy Method
* Order PCB through [OSHPark](https://oshpark.com/shared_projects/IBIkLilf)

# DIY Method
* Install KiCad version 5 (http://kicad-pcb.org/download/)
* Copy Library and Modules to KiCad install directory (usually {install_location}/KiCad/share/kicad/)
* Open TeensyAV.pro project file

## BOM:
* Teensy 3.6 ([$29.25](https://www.pjrc.com/store/teensy36.html))
* Audio Board ([$14.25](https://www.pjrc.com/store/teensy3_audio.html))
* Touchscreen ([$15.00](https://www.pjrc.com/store/display_ili9341_touch.html))
* Si2371EDS MOSFET
* BSR802N MOSFET
* Switches
* Magnetic Encoder
* Optional Optical Encoder
* SMD Resistor
* CR2032 Battery and Holder
* SMD male headers
