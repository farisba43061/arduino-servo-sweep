# Arduino Servo Sweep Example

## Description
This project demonstrates the Arduino **Servo Sweep** example using **four SG90 servo motors** connected to an Arduino Uno. All four servos sweep smoothly from **0° to 180°** and back for **2 seconds**, then stop at the **90° (center) position**.

## Components
- Arduino Uno
- 4 × SG90 Servo Motors
- Breadboard
- Jumper Wires
- USB Cable

## Wiring
| Servo | Arduino Pin |
|--------|-------------|
| Servo 1 | D3 |
| Servo 2 | D5 |
| Servo 3 | D6 |
| Servo 4 | D9 |

- Red wires → 5V
- Brown/Black wires → GND
- Orange wires → Arduino digital pins

## How It Works
1. The Arduino initializes all four servos.
2. The servos move together from **0° to 180°**.
3. They return from **180° to 0°**.
4. This motion repeats for **2 seconds**.
5. After 2 seconds, all servos stop at the **90° center position**.

## Files
- `SweepExample.ino` – Arduino source code
- `Circuit.png` – Tinkercad circuit screenshot

## Tinkercad Circuit
https://www.tinkercad.com/things/iUAGCuXcbPS-sweep-example


## Preview

<img width="1528" height="635" alt="sweep example" src="https://github.com/user-attachments/assets/5dc5b57d-734b-4082-8cdc-4ca286d946c9" />

# Author

**Faris Bahussain**

Electrical Engineering, Electronics, and Internet of Things (IoT) Track




