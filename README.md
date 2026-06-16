# Robotics Software Learning Portfolio

This repository contains a collection of projects designed to build foundational robotics software engineering skills. The goal is to gain hands-on experience with perception, localization, mapping, planning, control systems, networking, and concurrent programming while creating practical portfolio projects.

## Project 1: Robot Vacuum Simulator

### Overview

The Robot Vacuum Simulator models an autonomous cleaning robot operating in a virtual home environment. The robot must navigate through rooms, avoid obstacles, build a map of its surroundings, and return to a charging station when its cleaning task is complete.

### Objectives

* Implement autonomous navigation
* Build and maintain an environment map
* Perform obstacle avoidance
* Develop path planning algorithms
* Simulate battery management and docking behavior

### Technologies

* Python
* Occupancy Grid Mapping
* A* Path Planning
* State Machines

### Learning Outcomes

This project introduces several fundamental robotics concepts, including mapping, localization, navigation, and decision-making.

---

## Project 2: Multi-Threaded Robot Control System

### Overview

This project simulates the software architecture of a modern robot by dividing responsibilities across multiple concurrent threads. Each thread performs a dedicated function while communicating with the rest of the system through shared data structures.

### Objectives

* Design a concurrent robotics architecture
* Implement thread-safe communication
* Simulate sensor processing and control loops
* Explore real-time software concepts

### System Architecture

#### Camera Thread

Captures simulated sensor data and publishes observations to the system.

#### Localization Thread

Processes sensor information to estimate the robot's position and orientation.

#### Planning Thread

Analyzes the robot's state and determines the next movement or action.

#### Motor Controller Thread

Receives planned actions and translates them into simulated actuator commands.

### Technologies

* C++
* POSIX Threads (pthreads)
* Mutexes
* Condition Variables

### Learning Outcomes

This project demonstrates how robotics systems coordinate multiple concurrent tasks such as sensing, planning, and control while maintaining data consistency and responsiveness.

---

## Future Expansion

Planned projects include:

* Autonomous Boat Navigation Simulator
* Camera-Based Object Tracking System
* ROS 2 Delivery Robot
* Warehouse Robot Fleet Simulator

Together, these projects will provide experience in robotics software architecture, computer vision, motion planning, networking, distributed systems, and robotic middleware.
