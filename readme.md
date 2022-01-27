# PortableLAB

## Project Description

### PortableLAB is the advanced data acquisition system (but not only that) intended for various data acquisition tasks one can stumble upon. 

### The system is based on Cortex-M7 STM32H753II microcontroller from STMicroelectronics and Texas Instrument's ADS8586SIPMR, 16-bit precision, 6-channel simultaneous sampling ADC. 

### Short description of modules that will be on the system:
* advanced DAQ (external simultaneous sampling 16-bit ADC + integrated MCU ADC)
* programmable output voltage power supply 
* programmable constant current source 
* frequency generator (DDS-based)
* connectivity:
  * USB 2.0 for PC connection (FS + HS) 
  * Ethernet (10/100 Mbps) 
  * CAN  
  * RS232
  * RS485
  * SPI
  * I2C
  * Power monitoring
  * Relay control
  * On-board temperature sensing
  * MCU-external FLASH/EEPROM memory for non-volatile data storage

### Firmware support will be based on the FreeRTOS real-time operating system, allowing for the easier project managment, tasks division and maintaining. For PC control of the PortableLAB hardware, GUI will be developed based on the Qt framework, thus allowing software control on multiple platforms (Windows, Linux).


