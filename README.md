🚦 Arduino-Based Traffic Light Control System

A beginner-level embedded systems project that simulates a basic traffic light sequence using an Arduino UNO and three LEDs.

📸 Project Overview

This project demonstrates how an Arduino controls red, yellow, and green LEDs in a timed sequence. It introduces fundamental concepts of microcontroller programming, digital output pins, and time-based control.

"Arduino Traffic Light Control System" (images/traffic-light-circuit.jpg)

🎯 Objectives

- Understand the fundamentals of Arduino programming.
- Control LEDs using digital output pins.
- Implement sequential switching using "digitalWrite()".
- Learn time delays using the "delay()" function.
- Gain practical experience with breadboard circuit connections.

🛠️ Components Used

- Arduino UNO
- Red LED
- Yellow LED
- Green LED
- Current-limiting resistors
- Breadboard
- Jumper wires
- USB cable

⚙️ Working Principle

The Arduino controls three LEDs connected to digital pins 5, 6, and 7.

LED| Arduino Pin| ON Duration
🔴 Red| 5| 2 seconds
🟡 Yellow| 6| 1 second
🟢 Green| 7| 2 seconds

Sequence of Operation

1. The red LED turns ON for 2 seconds and then turns OFF.
2. The yellow LED turns ON for 1 second and then turns OFF.
3. The green LED turns ON for 2 seconds and then turns OFF.
4. The sequence repeats continuously.

💻 Arduino Source Code

int red = 5;
int yellow = 6;
int green = 7;

void setup() {
  pinMode(red, OUTPUT);
  pinMode(yellow, OUTPUT);
  pinMode(green, OUTPUT);
}

void loop() {
  digitalWrite(red, HIGH);
  delay(2000);
  digitalWrite(red, LOW);

  digitalWrite(yellow, HIGH);
  delay(1000);
  digitalWrite(yellow, LOW);

  digitalWrite(green, HIGH);
  delay(2000);
  digitalWrite(green, LOW);
}

🧠 Concepts Learned

- Arduino UNO and microcontroller basics
- Digital input/output configuration
- LED interfacing
- Sequential logic
- Time delays in embedded C/C++ programming

🚀 Future Improvements

- Add a pedestrian crossing signal.
- Introduce a countdown display.
- Use a push button to request pedestrian crossing.
- Implement non-blocking timing using "millis()".

👩‍💻 Project Information

Project Type: Beginner Embedded Systems Project
Platform: Arduino UNO
Programming Language: Arduino C/C++
Category: Electronics and Embedded Systems

