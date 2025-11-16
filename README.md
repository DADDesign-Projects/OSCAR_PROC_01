# OSCAR Processor Board - OSCAR_PROC_01
![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Hardware](https://img.shields.io/badge/hardware-PCB-green.svg)
![Audio](https://img.shields.io/badge/audio-DSP-orange.svg)
![KiCad](https://img.shields.io/badge/KiCad-9.0-blue.svg)
![KiCad](https://img.shields.io/badge/STM32-H743-blue.svg)

# 📋 Description
Dedicated electronic board implementing the processor section of the OSCAR effects pedal (https://github.com/DADDesign-Projects/OSCAR_P01A01). This board handles digital signal processing and audio control for the OSCAR effects platform.

# 🛠️ Technical Specifications
## Microcontroller STM32H743:
 - High-performance ARM Cortex-M7 MCU
 -  480 MHz frequency
 -  2MB Flash memory
 -  1MB RAM
## Flash Memory 2* W25Q128
 - 32 Moctet.
 - Double mode 8 bits SPI;
 - 120 Mhz
## SDRAM Memory IS42S16320
 - 64 Moctet
 - 200 Mhz
## USB OTG FS
  - CDC Virtual port COM
  - UDP DownLoad Firmware Update
  - MIDI / USB
## I/O
  - 4 Encoders
  - 2 Switchs
## TFT
  - SPI inteface 
  - 2.4 inch 
## MIDI
  - UART TRS Midi in
## Orogramming/Debugging
  - STLink serial port
  - USB UDP protocol.

## 💻 Software
The circuit design software for this board is available in the OSCAR repository (https://github.com/DADDesign-Projects/OSCAR_P01A01). This project is built upon the DAD Forge framework (https://github.com/DADDesign-Projects/DAD_FORGE), which provides a standardized foundation for hardware development and collaboration.

## 🛠️ Design Tools
This project was entirely designed using KiCad 9.0, the open-source electronics design automation suite.
    
# 📬 Contact
Feel free to contact me for any questions, feedback, improvement suggestions, or collaboration proposals related to the FORGE framework or the OSCAR hardware platform.
I am always open to discussion and community contributions (daddesign.projects@gmail.com).  
  
---
