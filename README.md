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


## Code
```cpp
digitalWrite(redLED, HIGH);
digitalWrite(yellowLED, LOW);
delay(1000);

digitalWrite(redLED, LOW);
digitalWrite(yellowLED, HIGH);
delay(1000);
