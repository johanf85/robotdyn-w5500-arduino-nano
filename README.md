# Pins wiring of Robotdyn w5500 with arduino nano

This is a description of how to wire a Robotdyn W5500 module to an arduino nano. 

W5500 ethernet modules are known to be way more reliable than ENC28J60 in combination with arduino. 

Manufacturer website: [Robotdyn w5500 module](https://robotdyn.com/ethernet-module-w5500-3-3v-5v.html)  
Tutorial on how to edit the Ethernet.h library for the W5500: [Instructables Arduino W5500](https://www.instructables.com/Arduino-Nano-with-WIZ550io-Easy-Internet/)

![](https://user-images.githubusercontent.com/43075793/114510933-8e54f980-9c37-11eb-90af-017696a3020c.png)

Pins 

| Arduino | Robotdyn w5500 |
| --- | --- |
| physical pin 1 (ICSP) | RST |
| D8 | INT |
| D10 | CSN |
| physical pin 17 (ICSP) | MOSI |
| physical pin 18 (ICSP) | MISO |
| D13 | CLK |
| 5V (ICSP) | 5V |
| GND (ICSP) | GND |

 I followed the same pins to which the shield (not the module) is connected to the nano, see below diagram. I did however put the MOSI,  MISO and SCK, RST, GND and 5V to the ICSP pins of the arduino.

![](https://user-images.githubusercontent.com/43075793/114511598-6619ca80-9c38-11eb-8957-94fb95d8c3b5.png)

The pinout of the nano:

![](https://user-images.githubusercontent.com/43075793/114511367-19ce8a80-9c38-11eb-8262-d595594c1f8a.png)
