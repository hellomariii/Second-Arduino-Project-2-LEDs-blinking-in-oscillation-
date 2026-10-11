# Second-Arduino-Project-2-LEDs-blinking-in-oscillation-
Second physical project: 1 red LED and 1 yellow LED oscillating in blinks

## Goal
Make two LEDs alternate.
## Hardware
Arduino Mega 2560, two LEDs, two 330 Ω resistors, breadboard, jumper wires.
Outputs: Pin 9 controls red; pin 10 controls yellow.
## Results
LEDs alternate approximately once per second.

## What I learned
Debugging lesson: Check breadboard connections carefully and verify power connections before reconnecting USB.

## Photos
<img width="3024" height="4032" alt="IMG_1340" src="https://github.com/user-attachments/assets/95e49be6-6bd7-4e23-99f8-8e4eb9640ce0" />
<img width="3024" height="4032" alt="IMG_1341" src="https://github.com/user-attachments/assets/48bca639-06d6-41f0-8a2e-c87c8cb03c35" />


## Code
```cpp
digitalWrite(redLED, HIGH);
digitalWrite(yellowLED, LOW);
delay(1000);

digitalWrite(redLED, LOW);
digitalWrite(yellowLED, HIGH);
delay(1000);
