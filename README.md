# Blinking-LED
## About
This program demonstrates simple Arduino setup that can blink two **LEDs** in sync. You can use simulators like [TinkerCad](https://www.tinkercad.com/dashboard) and [Wokwi](https://wokwi.com/) to simulate this program incase you don't have any physical devices.


You can Add multiple LEDs and modify their synchronizaiton accordingly.

You can see my project [here](https://wokwi.com/projects/463167114024859649).


<img width="1396" height="784" alt="Screenshot 2026-05-05 at 12 56 46" src="https://github.com/user-attachments/assets/535ef997-5817-4f8a-b4ac-b6c8e2175758" />

## Program features
**-Blinks two LED in sync**

**-Multiple LEDs can be added**
 
 ## Materials Required
 --Breadboard
 
 --Jumper wires
 
 --LED
 
 --Resistors
 
 --Arduino

 ## Connections Required (For single LED)
 -- Place **LED** in a breadboard 

 -- Connect the positive side with **Resistor**

 -- Connect the negative side to the **GND**(Ground) of the Arduino

 -- Connect the Resistor to any pin in Arduino(13 commonly used) except 0 and 1 unless necessary.

 --  Repeat Same process for Multiple LEDs.

 ## Space Constraint in Arduino
 There are limited number of ground and pins in the Arduino. In such cases, connect the GND to the -ve terminal of the Breadboard Bus and then you will have the whole line as GND. 

 Repeat the same process for pin e.g. connect the 13 no pin to the +ve bus of the Breadboard you will have whole bus of the breadboard working as 13th pin of the Arduino.
 
