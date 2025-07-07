
---
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github.com/ManchesterRoboticsLtd/Puzzlebot/blob/main/Misc/Logos/Puzzle_Bot_Logo_W.png">
  <source media="(prefers-color-scheme: light)" srcset="https://github.com/ManchesterRoboticsLtd/Puzzlebot/blob/main/Misc/Logos/Puzzle_Bot_Logo_B.png">
  <img alt="Shows MCR2 logo in black or white." width="250" align="right">
</picture>

 <div id="user-content-toc">
  <ul align="center" style="list-style: none;">
    <summary>
      <h1>Hackerboard</h1>
    </summary>
  </ul>
</div>


---

## Introduction
<picture>
  <source srcset="https://github.com/user-attachments/assets/eb51dce0-a365-46e1-846d-bc73f76db434">
  <img alt="Shows Puzzlebot views in black or white." width="400" align="right">
</picture>

* **The Hackerboard** is the core electronics platform designed by Manchester Robotics to power the Puzzlebot family of educational robots. It offers a compact, modular, and robust hardware interface for real-time control, sensor integration, and communication with embedded Linux systems like the Jetson Nano or Raspberry Pi.

* Puzzlebot in all its version, is powered by the **Hackerboard** for algorithms which require real-time processing capabilities, such as: Low level control, Navigation, Obstacle avoidance, 2D-LiDAR based SLAM, Fault tolerant control.

<br/><br/>

## Key Features 🔌
* Dual motor driver with encoder feedback support
* High-resolution quadrature encoder inputs
* IMU (Inertial Measurement Unit) support
* Time-of-Flight (ToF) distance sensor support
* Servo control interface
* Serial/UART and I2C communication channels
* Modular connectors for rapid assembly and expansion

## Designed For 🧠
* Puzzlebot Jetson Edition
* Puzzlebot RPi Edition
* Custom educational robotics platforms

## Use Cases 🛠️
* Real-time motor control with encoder feedback
* Sensor data acquisition (IMU, ToF, encoders)
* Serial communication with Jetson Nano or Raspberry Pi
* Rapid prototyping for robotics research and education

## General characteristics

<picture>
  <source srcset="https://github.com/user-attachments/assets/621b5530-34fa-49a0-a7bb-8086bf104a69">
  <img alt="Shows Puzzlebot views in black or white." width="400" align="right">
</picture>

  * ESP32-based Microcontroller
  * Xtensa dual-core 32-bit LX6 microprocessor
  * 520 KB of SRAM
  * Wi-Fi & Bluetooth
  * DC-DC Converter
  * Dual DC-Motor Driver
  * 0.96” I2C LCD Display

<br/><br/>
## Basic Internal Diagram

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/67285979/232494892-2e2e8409-6c73-4c42-8883-155d9cab9b60.png">
  <source media="(prefers-color-scheme: light)" srcset="https://user-images.githubusercontent.com/67285979/232494720-39c1937a-e8b6-48ce-8809-e09511e2dfa7.png">
  <img alt="Shows Puzzlebot block diagram." width="800" align="center">
</picture>

## Control Modes
The Hackerboard has two different control modes depending on the user’s requirements.
The two programming configurations:
* Standalone Configuration
* External-Control Configuration


