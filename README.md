# 🚦 Arduino-Based Traffic Light Control System

### A Simple Traffic Signal Automation Project Using Arduino UNO

---

##  Project Overview

The **Arduino-Based Traffic Light Control System** is an electronics project designed to simulate the basic operation of a real-world traffic signal. It uses an Arduino UNO microcontroller to control three LEDs representing the Red, Yellow, and Green traffic lights.

The system operates automatically in a predefined sequence, switching between the three lights with specific time intervals. This project demonstrates fundamental concepts of Arduino programming, digital output control, and time-based automation.

## Project Objectives

- To understand the working principle of traffic light systems.
- To learn LED interfacing with Arduino UNO.
- To implement sequential LED control using programming.
- To understand digital output operations using `digitalWrite()`.
- To implement time delays using the `delay()` function.

##  Hardware Requirements

| S.No | Component 
|---|---|---
| 1 | Arduino UNO
| 2 | Red LED
| 3 | Yellow LED 
| 4 | Green LED 
| 5 | Resistors (220Ω) 
| 6 | Breadboard 
| 7 | Jumper Wires 
| 8 | USB Cable 

##  Software Requirements

- Arduino IDE
- Arduino C/C++ Programming
- USB Driver for Arduino UNO

##  Pin Configuration

| LED Color | Arduino Digital Pin |
|---|---|
| 🔴 Red LED | Pin 5 |
| 🟡 Yellow LED | Pin 6 |
| 🟢 Green LED | Pin 7 |

##  Working Principle

The traffic light system operates in a continuous sequence using three LEDs.

1. **Red Light:** The red LED turns ON for 2 seconds, indicating STOP.
2. **Yellow Light:** The yellow LED turns ON for 1 second, indicating WAIT.
3. **Green Light:** The green LED turns ON for 2 seconds, indicating GO.
4. **Repeat:** After the green LED turns OFF, the complete sequence starts again automatically.

The `delay()` function controls the duration of each LED, while `digitalWrite()` switches the LEDs ON and OFF.

##  Arduino Source Code

[View Traffic Light Arduino Code](./traffic_light.ino)

##  Project Output

The output demonstrates the sequential operation of the three traffic signal LEDs.

![Arduino Traffic Light Control System](<TRAFFIC LIGHT SEQUENCE.jpeg>)


##  Concepts Learned

- Arduino UNO Interfacing
- LED Control Using Digital Pins
- `pinMode()` Function
- `digitalWrite()` Function
- `delay()` Function
- Sequential Execution
- Basic Embedded Systems Programming

##  Applications

- Basic traffic signal simulation.
- Embedded systems learning.
- Arduino-based automation experiments.
- Educational electronics demonstrations.
- Introduction to intelligent traffic management systems.


