LMP90100
========

Python Linux Repository designed for using the Texas Instruments LMP90100 ADC

If you wish to use this code commercially, please email me for a license 
License:  Attribution-NonCommercial-ShareAlike 3.0 United States
Written by Bruce Schaller 15JAN2014
bruce.schaller-@-gmail.com (remove dashes)

Texas Instruments - LMP90100 SPI Communications in Python

Goal: Interface a Beaglebone Black (or any linux system with an SPI master) to the Texas Instruments LPM90100 
to take accurate temperature measurements using a RTD (resistance temperature device) or TC (thermocouple).  
Create a library of code to permit copy-paste programming for basic functionality.

Background:
  There seems to be a limited availability of higher resolution ADCs for use in projects in the makersphere.  By providing these examples (currently untested) it is hoped that there will be additional adoption of higher resolution devices for use in academia.  
  
  These examples require that SPIdev is properly configured, and that you have determined the SPI address of the device, and that it is properly wired.  It is impractical to address each way that this product could be configured; however, by dividing the code into commentable sections, I hope to make this ADC easy to use for other developers.
  
  I haven't recieved my LMP90100 yet, so I'm not sure how or if this will work.  I'm trying to get a jump on it before it arrives.  You've been forewarned.  Please feel free to shoot me any problems you're having and maybe we can figure them out.
  
  Good Luck!
  Bruce Schaller
