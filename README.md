# Motion-Dection-Fan-Motor
What it does

Measures distance in front of the sensor.

If the object is farther than ~30 cm, the motor turns ON.

If the object gets closer than ~20 cm, the motor turns OFF.

The 30 cm/20 cm gap (hysteresis) keeps the motor stable near the boundary.

You can change the on and off thresholds in code to whatever distances you want.

Parts (basic)

1 × Arduino Uno

1 × HC-SR04 ultrasonic distance sensor

1 × DC motor (small fan)

1 × NPN transistor (e.g., 2N2222 or 2N3904/TIP120)

1 × Flyback diode (e.g., 1N4001–1N4007) across the motor

1 × Base resistor ~1 kΩ

(Optional) 1 × Pulldown resistor 10 kΩ (from base to GND)

Breadboard + jumper wires

Power: Arduino 5 V is OK for very small motors; for bigger motors use an external 5–6 V supply (tie grounds together)

<img width="1740" height="1107" alt="Screenshot 2025-08-24 140917" src="https://github.com/user-attachments/assets/c8ddd6ea-45f4-4256-ae71-27addc0f7d5c" />
video: https://www.youtube.com/watch?v=-ciG0Aa4bys
