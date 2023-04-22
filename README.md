# LaskaKit Bat-Boost converter to 5V with DIO6605B

Miniature boost converter with 5V/600mA output ideal for powering sensors (air quality) or addressable RGB LED strips from a flashlight and functioning as a switch.

On the 15.3 x 10.2 mm board is a DIO6605 switching circuit operating at 1.2 MHz. With such a small board you are able to power devices with 5V input voltage and up to 600mA.

And it also acts as a switch. The EN pin has its own pin for controlling the inverter and also a solder bridge if you don't want to worry about switching and the inverter can run. If EN is connected to VIN (or the voltage is higher than 1.6V - for example from ESP8266/ESP32/RaspberryPi), the inverter is on. If the voltage is lower than 0.4V, it is in the off state and thus draws less than 1uA ! At the same time, of course, the device that is powered from the inverter is also switched off.

Designer: [@chiptron.cz](https://twitter.com/chiptronCZ)

You can buy on https://www.laskakit.cz/laskakit-bat-boost-menic-5v-0-6a-dio6605b/

Specifications:<br>
Chip: DIO6605B<br>
Input Voltage: 2.7-4.5V<br>
Output voltage fixed: 5V<br>
Output current: 0.6A<br>
Switching frequency: 1.2 MHz<br>
Efficiency: 95% (max)<br>
Dimensions: 10.2x5.3x2.8mm<br>
Weight: 0.6g<br>
