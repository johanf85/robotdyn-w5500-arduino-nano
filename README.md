# robotdyn-w5500-arduino-nano

This is a description of how to wire a Robotdyn W5500 module to an arduino nano. 

Manufacturer website: 

![](https://user-images.githubusercontent.com/43075793/114510933-8e54f980-9c37-11eb-90af-017696a3020c.png)

Pins 

| Arduino  | Robotdyn w5500 |
| --- | --- |
| physical pin 1 (ICSP) | RST |
| D8 | INT |
| D10 | CSN |
| physical pin 17 (ICSP) | MOSI |
| physical pin 18 (ICSP) | MISO |
| D13 | CLK |
| 5V (ICSP) | 5V |
| GND (ICSP) | GND |

Based on the W5500 Ethernet shield from Robotdyn, I followed the same pins to which the shield is connected to the nano. I did however put the MOSI,  MISO and SCK, RST and 5V to the ICSP pins, see below diagram. 

![](https://user-images.githubusercontent.com/43075793/114511598-6619ca80-9c38-11eb-8957-94fb95d8c3b5.png)

![](https://user-images.githubusercontent.com/43075793/114511367-19ce8a80-9c38-11eb-8262-d595594c1f8a.png)
