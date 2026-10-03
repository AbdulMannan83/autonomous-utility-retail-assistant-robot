# Autonomous Utility Retail Assistant Robot

An autonomous mobile robot developed as a **Final Year Project (FYP)** to assist customers and automate item delivery within retail and utility store environments.

## Overview

The **Autonomous Utility Retail Assistant Robot** is designed to navigate a store environment autonomously, reach designated locations, and assist customers by transporting selected items. The system combines **robotics, embedded systems, autonomous navigation, mapping, and web-based interaction** into an integrated robotic platform.

The robot uses a **Raspberry Pi 5** as the primary computing platform and an **ESP32** for low-level motor control and encoder feedback. The software architecture is built around **ROS 2**, with **SLAM** and **Nav2** used for mapping, localization, path planning, and autonomous navigation.

## System Architecture

The project consists of the following major components:

* **Raspberry Pi 5** — Main onboard computing platform
* **ESP32** — Motor control and encoder processing
* **4 DC Gear Motors with Encoders** — Differential-drive movement and odometry feedback
* **ROS 2** — Robot software and communication framework
* **SLAM** — Environment mapping and localization
* **Nav2** — Autonomous path planning and navigation
* **Web Interface** — User interaction and robot control
* **Sensors** — Environmental perception and navigation
* **Custom Robot Chassis** — Mobile robotic platform

## Project Goals

* Develop an autonomous mobile robot for retail and utility store environments
* Enable autonomous movement between designated store locations
* Build and maintain a map of the operating environment using SLAM
* Implement encoder-based odometry for accurate movement estimation
* Develop reliable motor control using an ESP32
* Integrate the ESP32 motor subsystem with Raspberry Pi 5 and ROS 2
* Implement autonomous path planning and navigation using Nav2
* Provide a web-based interface for user interaction
* Integrate the hardware and software components into a complete robotic system

## Technologies

### Hardware

* Raspberry Pi 5
* ESP32
* DC Gear Motors
* Quadrature Encoders
* Robot Chassis
* Navigation and Environmental Sensors

### Software

* Ubuntu
* ROS 2
* Nav2
* SLAM
* Python
* C/C++
* Web Technologies
* Git & GitHub

## Project Status

The **Autonomous Utility Retail Assistant Robot** is actively under development as a **Final Year Project**.

### Completed

* ✅ Robot drive system assembled and tested
* ✅ 4-motor drive system integrated
* ✅ ESP32-based motor control implemented
* ✅ Motor speed calibration completed
* ✅ Straight-line movement tested and calibrated
* ✅ Pivot-turn speed calibrated and tested
* ✅ All 4 motor encoders connected to the ESP32
* ✅ Encoder pulse counting verified using interrupts
* ✅ Raspberry Pi 5 configured as the main computing platform
* ✅ Ubuntu installed on Raspberry Pi 5
* ✅ ROS 2 project workspace established
* ✅ Project source code organized using Git
* ✅ GitHub repository established

### In Progress

* 🔄 ESP32–Raspberry Pi communication
* 🔄 ROS 2 motor-control node integration
* 🔄 Encoder data integration with ROS 2
* 🔄 Odometry implementation and validation
* 🔄 SLAM configuration and mapping
* 🔄 Nav2 autonomous navigation
* 🔄 Sensor integration
* 🔄 Web interface integration
* 🔄 Full hardware–software integration testing

### Planned

* ⬜ Complete store environment mapping
* ⬜ Implement reliable robot localization
* ⬜ Implement autonomous point-to-point navigation
* ⬜ Integrate obstacle detection and avoidance
* ⬜ Connect the web interface with the ROS 2 system
* ⬜ Test the robot in a realistic store environment
* ⬜ Optimize navigation and movement accuracy
* ⬜ Perform complete system testing
* ⬜ Prepare the final FYP demonstration and documentation

## Repository Structure

```text
autonomous-utility-retail-assistant-robot/
├── documentation/
├── esp32/
├── hardware/
├── nav2/
├── ros2_ws/
├── slam/
├── web/
└── README.md
```

## Development

This repository contains the hardware, embedded software, ROS 2 packages, navigation configuration, SLAM resources, web interface, and documentation associated with the **Autonomous Utility Retail Assistant Robot**.

The project is being developed as a Final Year Project with the objective of integrating embedded motor control, encoder feedback, ROS 2, mapping, localization, and autonomous navigation into a functional retail-assistance robot.

