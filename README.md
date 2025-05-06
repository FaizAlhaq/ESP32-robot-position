# ESP32 Robot Positioning System

This project is a closed-loop position control system for a two-wheeled robot using an ESP32 microcontroller. It determines the center point between two obstacles using two ultrasonic sensors and corrects the robot's position by comparing left and right distance readings.

## 📚 Background
This project was developed as a final semester assignment in the *System Dynamics* course. It demonstrates the application of feedback control and error correction using real-time sensor inputs and motor control.

## 🧩 Components Used
- ESP32 Dev Module
- 2x HC-SR04 Ultrasonic Sensors
- 2x DC Motors
- L298N Motor Driver Module
- 8x 3.7V Li-ion Batteries
- Jumper Wires, Breadboard

## 🛠️ Tools & Software
- Arduino IDE
- C/C++ Programming
- Custom PID-style logic for error correction

## ⚙️ System Overview
- The robot reads distance from the left and right ultrasonic sensors.
- If distances are unequal, the system calculates the error and corrects the position by adjusting motor direction.
- Once the left and right distances are equal (or within a defined threshold), the robot stops.
- Real-time sensor readings are displayed via Serial Monitor.

## 📷 Images
![Schematic](Documentation/schematic_placeholder.png)
![Flowchart](Documentation/flowchart_placeholder.png)
![Real Device](Images/robot_photo_placeholder.jpg)

## 📂 Repository Structure
- `Arduino_Code/`: Main `.ino` code for the ESP32
- `Documentation/`: Schematic, flowchart, and component list
- `Images/`: Real-life photos of the robot (placeholder)

## ✍️ Author
Muhammad Faiz Al Haq – Majoring Physics Engineering, 2025
