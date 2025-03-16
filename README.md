## Traffic Light Controller using 7 segment diaplay Using Arduino in TinkerCad

## Introduction
Traffic control systems are essential for managing vehicle movement efficiently and preventing congestion. With advancements in embedded systems, microcontrollers like Arduino provide cost-effective and smart solutions for traffic light management.

## Project Overview
TThe project aims to design a simple traffic control system using a 7-segment display and Arduino on Tinkercad, a virtual simulation platform. The system will simulate a traffic light system by displaying countdown numbers on the 7-segment display, along with LED indicators representing the red, yellow, and green signals.

## Components Used
The following components were utilized in the project:
- Arduino Uno R3
- 7-Segment Display (Common Cathode or Anode)
- Resistors (220Ω)
- LEDs (Red, Yellow, Green)
- Breadboard
- Jumper Wires


## Traffic Light Sequence
The 7-segment display will show the countdown timer for each signal (e.g., 10 seconds(9-0) for red, 4 seconds4(3-0) for yellow, and 10 seconds(9-0) for green).
The Arduino will control the 7-segment display using a direct segment pin connections.
The system continuously cycles through red, yellow, and green phases.
The LEDs will turn on accordingly:
- Red LED for stop
- Yellow LED for wait
- Green LED for go

![Screenshot (84)](https://github.com/user-attachments/assets/913c2e20-42a1-4539-82a6-26c7d8f7384e)

## Implementation
The traffic light controller logic is implemented using Arduino Uno and programmed in C++ language. The Arduino code includes:
- Defining pin configurations for LEDs and resistors.
- Implementing a traffic light sequence algorithm with appropriate delays for Red, Green and Yellow lights.

## Applications
- Smart traffic signal control
- Pedestrian crossing management
- Adaptive traffic control systems

## Conclusion
The traffic control management system using a 7-segment display and Arduino successfully simulates a real-world traffic light system in Tinkercad. By integrating LED indicators and a countdown timer, this project provides a structured and efficient way to regulate vehicle movement.

This system can be further enhanced by implementing sensors for real-time traffic monitoring, IoT integration for remote control, or adaptive signal timing based on traffic density. The project serves as a fundamental step toward understanding embedded systems, Arduino programming, and traffic management technologies.



