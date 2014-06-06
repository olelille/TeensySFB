TeensySFB
=========
Teensy Sensor Fusion Board

Spesification
-------------
This board is a shield to the Teensy 3.1 with the following features:
 - DJI CAN port with 6V power input 
 - 3.3V Switching regulator 
 - 4 Analog inputs with RC filter  
 - 1 Analog output (DAC with amplifier and filter, max 5V)
 - INA219B, I2C Highside Power measurement of battery voltage, current and power   
 - MPU-9150, I2C 9DOF MPU sensor (3-axis MEMS gyrometer,accelerometer and magnetometer) 
 - PMB180, I2C Pressure Sensor 
 - 6 PWM outputs with optional output voltage (3.3V or 5V from seccond soruce)
 - Micro SD card 
 - FrSky S-Port (UART1) 
 - GSM connector to SIM900 with UART3(TX,RX) and control signals(RST,PWR_ON)
 - Spare UART2 port (OSD, sensor or controller)


Hardware
---------
The schematic and PCB are designed in DesignSpark PCB 6.0
http://www.rs-online.com/designspark/electronics/eng/page/designspark-pcb-home-page



Software
--------
Using Arduino Eclipse anddon with Teensy 3.1 support

