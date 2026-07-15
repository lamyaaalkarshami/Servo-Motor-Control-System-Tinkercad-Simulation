# Servo-Motor-Control-System-Tinkercad-Simulation
This project shows how four servo motors can be controlled using an Arduino Uno in Tinkercad. Each servo receives independent PWM signals, allowing smooth rotation between 0° and 180°, then holding at 90°. The simulation helps users understand servo motion, signal control, and basic Arduino programming.
Components Used:
- Arduino Uno  
- 4 × Micro Servo Motors  
- Jumper Wires
- 
Circuit Wiring:
| Servo | Signal Pin | Power (+5V) | Ground (GND) |
|-------|------------|-------------|--------------|
| Servo 1 | Pin 3~ | 5V | GND |
| Servo 2 | Pin 5~ | 5V | GND |
| Servo 3 | Pin 6~ | 5V | GND |
| Servo 4 | Pin 9~ | 5V | GND |
All servos share the same 5V and GND rails, while each servo receives its own dedicated PWM signal pin.

How the Simulation Works:
The servo motors smoothly rotate between 0° and 180° for a fixed duration.
After completing the movement cycle, all servos move to a final angle of 90° and remain steady.
This behavior demonstrates how PWM signals are used to control servo motion through the Arduino Uno in the Tinkercad environment.
