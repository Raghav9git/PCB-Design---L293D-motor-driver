# L293D Motor Driver PCB with Integrated IR Sensor

## Overview

This project presents the design and development of a custom PCB integrating the L293D dual H-Bridge motor driver IC with an onboard IR sensor interface for robotic motion control applications.

The board is designed to provide a compact and reliable motor driving solution for small robotics platforms using DC motors.

---

## Tools & Software Used

- KiCad (Schematic Capture and PCB Layout)
- ERC and DRC validation tools
- 2-layer PCB design
- KiCad 3D Viewer for mechanical verification

---

## Hardware Components

- L293D Dual H-Bridge Motor Driver IC
- IR Sensor module interface
- DC motor output terminals (Motor A and Motor B)
- Screw terminal blocks
- Decoupling capacitors
- Motor power supply input
- 5V logic supply input

---

## System Architecture

The PCB integrates:

- Dual motor control outputs
- Logic control pins (IN1, IN2, IN3, IN4, ENA, ENB)
- IR sensor signal input routed to an external microcontroller
- Separate motor supply (Vmotor) and logic supply (Vcc)
- Common ground with appropriate decoupling

The board is designed to interface with external microcontrollers such as Arduino or ESP32 for implementing motor control logic.

---

## Working Principle

The L293D IC functions as a dual H-Bridge motor driver enabling:

- Forward rotation
- Reverse rotation
- Brake mode
- PWM-based speed control via enable pins

The IR sensor output can be connected to a microcontroller to enable:

- Obstacle detection
- Line following logic
- Basic autonomous navigation

---

## PCB Design Highlights

- Appropriate trace width selection for motor current handling
- Decoupling capacitors placed close to IC power pins
- Separation of power and logic routing
- Compact layout to reduce signal noise
- Clearly labeled input and output terminals

---

## Applications

- Obstacle avoidance robots
- Line following robots
- Small autonomous vehicles
- Robotics prototyping platforms

---

