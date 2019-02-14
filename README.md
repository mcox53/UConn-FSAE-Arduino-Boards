# UConn-FSAE-Arduino-Boards

This repository contains all the necessary board support files to efficiently program the custom boards designed by UConn Formula SAE

Ideas and formatting for this repository were borrowed, with love, from:
  - [sparkfun/Arduino_Boards](https://github.com/sparkfun/Arduino_Boards)
  - [MCUdude/MicroCore](https://github.com/MCUdude/MicroCore)
  - [Arduino/ArduinoCore-samd](https://github.com/arduino/ArduinoCore-samd)
  
Installation Instructions:
  - Coming soon
  
To-Do List:
  - Edit .inf file for team boards and build .cat file
  - Add production bootloaders to /samd/bootloaders
  - Under /samd/variants :
	- Modify variant.cpp
	- Modify variant.h
	- Note to self: SPI PAD values found in samd/cores/arduino/sercom.h
	- Note to self: Pin names for SPI Interface > 1 found in samd/libraries/SPI/SPI.cpp
  - Under /samd/ :
	- Modify boards.txt
	- Modify platform.txt
	- Modify programmers.txt
  - Make a picture showing SAMD21-Dev-Board pin mapping
  - Eventually test native implementation of multiple SPI Classes
  - Test Board Package Using SAMD21-Dev-Board
  
