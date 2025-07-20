#  Dancing LED Project - Arduino 

This project demonstrates a **Dancing LED pattern** using an Arduino Uno and 6 LEDs. It is a beginner-friendly project to understand digital output, loops, and timing in Arduino.

##  Components Used

| Component         | Quantity | Description                       |
|------------------|----------|-----------------------------------|
| Arduino Uno       | 1        | Microcontroller Board             |
| LED               | 6        | Any color                         |
| 220Ω Resistor     | 6        | Protects LEDs from overcurrent    |
| Breadboard        | 1        | For easy connections              |
| Jumper Wires      | Many     | To connect all components         |

---

##  Circuit Overview

Each LED is connected to digital pins **D2 to D7** of the Arduino Uno, and their cathodes are grounded via 220Ω resistors. The pattern runs in three phases:

1. **Left to Right Sweep**
2. **Right to Left Sweep**
3. **All LEDs Blink Together**


## 💻 Arduino Code

The sketch file is located in [`dancing_led.ino`](./dancing_led.ino).  


