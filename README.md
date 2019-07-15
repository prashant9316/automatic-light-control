# automatic-light-control
This project will turn on the lights in a room automatically whenever a person enters the room 

this project is an Arduino nano based smart home appliance control. This project uses a ultrasonic module HCSR04 fixed around the door to detect if someone passes the door. After that a 12v relay module is used to turn ON a 220V AC light bulb. Any other electrical appliance can also be used instead of a bulb.

## Apparatus Required
1. Arduino Nano
2. HCSR 04 ultrasonic sensor
3. 12V relay module
4. a bulb and its holder
5. breadboard and connecting wires

## Circuit schematic
this is the link to circuit 
[schematic](https://drive.google.com/file/d/1kMSx11q7l_5U-MCHBY0NgY5SOxAjIM8g/view?usp=drive_open)

1. connect data pin of the relay module to digital pin 8.
2. the trigger pin of the ultrasonic sensor should be connected to the digital pin 9.
3. the echo pin of the ultraasonic sensor should be connected to the digital pin 10.
