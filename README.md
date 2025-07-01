# project_1
This project controls three different LEDs (red, green, and blue) using a single push button. Each time the button is pressed, a different LED turns on, and the previous one turns off.


<img width="710" alt="Image" src="https://github.com/user-attachments/assets/676d69e3-92bb-4153-b2fb-3d716485853d" />

The circuit was built and tested using Tinkercad Circuits, an online simulation platform.

How It Works
Button 1 (connected to pin 7) → controls LED 1 (pin 13): ON for 1s, OFF for 0.5s

Button 2 (pin 4) → controls LED 2 (pin 12): blinks every 300ms

Button 3 (pin 2) → controls LED 3 (pin 8): blinks every 200ms

If no buttons are pressed, all LEDs stay OFF.

This project teaches basic digital input/output handling and control logic in Arduino.

Tools and Platform
Tinkercad Circuits

Arduino Uno (simulated)

Breadboard, LEDs, push buttons, resistors (in simulation)


| Component      | Quantity  |
| -------------- | --------- |
| Arduino Uno    | 1         |
| Breadboard     | 1         |
| LEDs (Red)     | 3         |
| Push Buttons   | 3         |
| 220Ω Resistors | 6         |
| Jumper Wires   | As needed |


Circuit Diagram
Here’s the wiring diagram based on your Tinkercad setup:


Wiring Notes:

Each LED is connected in series with a 220Ω resistor to pins 13, 12, and 8.

Each push button is connected to pins 7, 4, and 2 with pull-down resistors to ground.

GND and 5V are correctly connected to the breadboard rails.

