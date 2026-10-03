# Autonomous Utility Store Robot

An autonomous mobile robot developed as a **Final Year Project (FYP)** to assist customers and automate item delivery inside retail and utility stores.

## Overview

The **Autonomous Utility Store Robot** is designed to navigate a store environment autonomously, identify and reach designated locations, and assist in transporting selected items to customers. The system integrates **robotics, embedded systems, computer vision, autonomous navigation, and web-based interaction** into a single platform.

The robot uses a **Raspberry Pi 5** as the primary computing platform and an **ESP32** for low-level motor control and encoder feedback. The software architecture is based on **ROS 2**, with autonomous navigation and mapping handled through the robotics software stack.

## System Architecture

The project consists of the following major components:

* **Raspberry Pi 5** — Main onboard computer
* **ESP32** — Motor control and encoder processing
* **DC Gear Motors with Encoders** — Differential-drive movement and odometry feedback
* **ROS 2** — Robot software and communication framework
* **SLAM** — Environment mapping and localization
* **Nav2** — Autonomous path planning and navigation
* **Web Interface** — User interaction and robot control
* **Sensors** — Environmental perception and navigation
* **Custom Robot Chassis** — Mobile robotic platform

## Project Goals

* Develop an autonomous mobile robot for retail environments
* Create a map of the store environment using SLAM
* Enable autonomous navigation between predefined locations
* Implement reliable motor control and encoder-based feedback
* Provide a user-friendly interface for interacting with the robot
* Integrate embedded hardware and ROS 2 into a complete robotic system

## Technologies

**Hardware:** Raspberry Pi 5, ESP32, DC Gear Motors, Encoders, Sensors

**Software:** Ubuntu, ROS 2, Nav2, SLAM, Python, C/C++, Web Technologies

## Project Status

The **Autonomous Utility Store Robot** is actively under development, with the core mobile platform, motor control, encoder feedback, and initial ROS 2 infrastructure established.

### Completed

* ✅ **Robot drive system assembled and tested**
* ✅ **4 DC motors integrated with the robot platform**
* ✅ **ESP32-based motor control implemented**
* ✅ **Motor speed calibration completed for straight movement**
* ✅ **Pivot-turn speed calibrated and tested**
* ✅ **All 4 motor encoders connected to the ESP32**
* ✅ **Encoder pulse counting verified using interrupts**
* ✅ **Raspberry Pi 5 configured as the main onboard computer**
* ✅ **Ubuntu installed on Raspberry Pi 5**
* ✅ **Project ROS 2 workspace established**
* ✅ **Initial robot software structure organized**
* ✅ **Git/GitHub repository established for project development**

### In Progress

* 🔄 **ESP32 ↔ Raspberry Pi communication**
* 🔄 **ROS 2 motor-control node integration**
* 🔄 **Publishing encoder/odometry data to ROS 2**
* 🔄 **Robot odometry validation**
* 🔄 **SLAM configuration and mapping**
* 🔄 **Nav2 autonomous navigation**
* 🔄 **Sensor integration**
* 🔄 **Web-based robot control and interaction**
* 🔄 **Integration testing between hardware and software**

### Planned

* ⬜ Complete autonomous mapping of the store environment
* ⬜ Implement reliable localization
* ⬜ Configure autonomous point-to-point navigation
* ⬜ Integrate obstacle detection and avoidance
* ⬜ Connect the web interface with the ROS 2 system
* ⬜ Test navigation in a realistic store-like environment
* ⬜ Optimize movement accuracy and reliability
* ⬜ Perform complete system testing
* ⬜ Prepare the final FYP demonstration and documentation

### Development Focus

The current development phase is focused on integrating the **ESP32 motor and encoder subsystem with the Raspberry Pi 5 and ROS 2**, establishing reliable odometry, and progressing toward autonomous mapping and navigation.

The final objective is to achieve a fully integrated mobile robot capable of navigating a retail environment and assisting with store-related tasks autonomously.

