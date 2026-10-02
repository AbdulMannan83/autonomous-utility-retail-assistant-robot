# Autonomous Utility Store Robot

An autonomous utility store robot developed as a Final Year Project.

## System

- Raspberry Pi 5
- ESP32
- 4-wheel drive chassis
- 2 × L298N motor drivers
- 4 motors with quadrature encoders
- LIDAR
- ROS 2
- RViz2
- SLAM Toolbox
- Nav2
- AprilTags
- Robotic arm
- Web ordering interface
- Supabase

## Architecture

Web Interface
        ↓
Supabase
        ↓
Mission Manager
        ↓
ROS 2 / Nav2
        ↓
ESP32
        ↓
Motor Drivers
        ↓
4-Wheel Robot

## Current Progress

- [x] Chassis assembled
- [x] Motor drivers connected
- [x] ESP32 motor control
- [x] Four encoder signals verified
- [ ] ROS 2 setup
- [ ] LIDAR integration
- [ ] RViz2 visualization
- [ ] SLAM mapping
- [ ] Nav2 navigation
- [ ] ESP32 ROS 2/serial bridge
- [ ] AprilTag positioning
- [ ] Robotic arm integration
- [ ] Mission Manager
- [ ] Web ordering system
