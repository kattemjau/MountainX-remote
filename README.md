# MountainX-remote
PCB of remote, designed in Kicad
Inspired by Adafruit, and SolidGeek
https://learn.adafruit.com/bluefruit-nrf52-feather-learning-guide?view=all#downloads

https://www.electric-skateboard.builders/t/simple-3d-printed-nrf-remote-arduino-controlled/28543

V3 is not yet tested

Arduino compadible CODE can be found here:
https://github.com/Heplaphon/MountainX-Remote

Follow setupguide from Adafruit: https://learn.adafruit.com/bluefruit-nrf52-feather-learning-guide?view=all#arduino-bsp-setup

V2 up and working with Arduino IDE, can be programmed over USB, JTAG and OTA (bluetooth)

3D model of PCB can be found here:
https://github.com/kattemjau/MountainX-remote/tree/master/3D%20model

3D model of remote can be found here:
https://github.com/kattemjau/MountainX-remote/tree/master/3D%20model/V2

Images can be found here:
https://github.com/kattemjau/MountainX-remote/tree/master/Images


Features:

3 Hall sensors for more accurate readings, 
Nordic NRF52 Bluetooth 5, Arm Cotex m4,
Oled screen with telematry from Vesc: Speed, distance, battery voltage, error codes e.t.c, 
Remote battery reading, 
1A Fast charger, 
Long battery life, 
Dual battery to prevent battery disconnect due to shaking, 
Spring loaded knob and trigger, 
Deadmans switch, 
Opensource reprogrammable firmware with arduino IDE, 
Connects with up to 20 clients, long range and high bandwidth,


Changes:

3D model now available, 
Integrated OLED screen, 
Correct angles on Hall sensors, 
Extra battery plug, 
More leds, 
More decoupling caps, 
Better layout, 
Changes to footprints, 
NOW USB C, 


Note:
Jtag programming header is mirrored, just flip the cable to get it to work. "Jtag is not needed"
https://shop-us.segger.com/J_Link_EDU_mini_p/8.08.91.htm

Footprint for Raytac NRF52832 not correct, and SS12D11 (SWITCH) is missing
