# Robotics Software Engineering Portfolio

## Overview

This portfolio consists of a series of projects designed to build practical robotics software engineering skills. The projects progressively introduce concepts such as concurrent programming, localization, mapping, path planning, computer vision, control systems, networking, distributed systems, and robotic middleware.

By completing these projects, you will develop a portfolio that demonstrates the foundational skills required for robotics software engineering, autonomy engineering, embedded systems development, and simulation engineering roles.

---

# Recommended Project Order

The projects are organized to build upon one another:

1. Multi-Threaded Robot Control System
2. Robot Vacuum Simulator
3. Autonomous Boat Navigation Simulator
4. Camera-Based Object Tracking Turret
5. ROS 2 Delivery Robot
6. Warehouse Robot Fleet Simulator
7. Autonomous Fishing Spot Finder

This progression moves from software fundamentals to increasingly complex robotics systems.

---

# Project 1: Autonomous Boat Navigation Simulator

## Overview

This project simulates an autonomous boat navigating through a virtual environment using GPS coordinates and waypoint-based navigation. Environmental factors such as wind, water currents, and sensor inaccuracies are incorporated to create realistic navigation challenges.

## Skills Learned

* Path Planning
* GPS Navigation
* Sensor Fusion
* Multithreading
* Networking

## Project Goals

* Simulate a boat operating on a lake map
* Introduce GPS noise and positioning errors
* Model wind and water current effects
* Navigate autonomously between waypoints

## Technologies

* C++
* Python Visualization
* A* Path Planning
* Multithreading

## Stretch Goal

Create simulations based on real-world locations such as Stampede Reservoir or Alameda Harbor.

---

# Project 2: Robot Vacuum Simulator

## Overview

This project simulates an autonomous robot vacuum operating inside a home environment. The robot must discover rooms, avoid obstacles, clean efficiently, and return to a charging station.

## Skills Learned

* Mapping
* Localization
* Path Planning
* State Machines

## Project Goals

* Simulate autonomous cleaning behavior
* Discover and map rooms
* Avoid obstacles and furniture
* Return to a charging dock when complete

## Technologies

* Python
* Occupancy Grid Mapping
* A* Path Planning
* ROS 2 (future enhancement)

## Stretch Goal

Generate random furniture layouts and have the robot adapt to new environments.

---

# Project 3: Multi-Threaded Robot Control System

## Overview

This project simulates the internal software architecture of a robot by dividing responsibilities among multiple concurrent threads. It directly applies concepts learned in operating systems and concurrent programming.

## Skills Learned

* Threads
* Synchronization
* Producer-Consumer Patterns
* Real-Time Systems

## System Architecture

### Thread 1: Camera

Captures sensor information and publishes observations.

### Thread 2: Localization

Processes sensor data and estimates robot position.

### Thread 3: Planning

Determines the robot's next action and movement goals.

### Thread 4: Motor Controller

Converts plans into actuator commands.

## Implementation Details

Use mutexes and condition variables to safely share data between threads.

## Learning Outcome

This project demonstrates concurrency and system architecture concepts that are highly valued in robotics software engineering.

## Technologies

* C
* POSIX Threads (pthreads)
* Mutexes
* Condition Variables
* Linux
* Makefiles

---

# Project 4: Autonomous Fishing Spot Finder

## Overview

This project combines environmental data and decision-making algorithms to identify promising fishing locations. It is a unique portfolio project that blends robotics concepts with a personal interest in boating and fishing.

## Skills Learned

* Sensor Fusion
* Decision Making
* Data Analysis
* Mapping

## Inputs

* Wind Conditions
* Tide Information
* Water Temperature
* Water Depth

## Output

* Recommended Fishing Locations

## Future Expansion

Expand the project into a digital "Captain's Assistant" capable of providing fishing recommendations and environmental analysis.

---

# Project 5: Camera-Based Object Tracking Turret

## Overview

This project uses computer vision to detect and track an object in real time. A virtual turret uses feedback control to keep the target centered within the camera view.

## Skills Learned

* Computer Vision
* Control Systems
* PID Controllers

## Project Goals

* Detect objects using a webcam
* Track target movement
* Implement PID-based feedback control
* Maintain target lock

## Technologies

* Python
* OpenCV

## Learning Outcome

This project introduces robotic perception and control systems while combining computer vision with real-time feedback loops.

---

# Project 6: Warehouse Robot Fleet Simulator

## Overview

This project simulates multiple autonomous warehouse robots working together to complete transportation tasks while avoiding collisions and sharing resources.

## Skills Learned

* Networking
* Distributed Systems
* Multi-Agent Planning

## Project Goals

* Simulate a fleet of ten robots
* Maintain a shared warehouse map
* Assign package pickup and delivery tasks
* Prevent collisions between robots

## Implementation Details

Use network sockets to allow robots to communicate and coordinate actions.

## Learning Outcome

This project introduces distributed robotics concepts commonly found in modern warehouse automation systems.

---

# Project 7: ROS 2 Delivery Robot

## Overview

This project implements a simulated delivery robot using ROS 2. The robot navigates hallways, avoids obstacles, and delivers items between locations.

## Skills Learned

* ROS 2
* Navigation Stack
* Robotics Middleware

## Project Goals

* Create a simulated robot
* Navigate autonomously through hallways
* Avoid obstacles
* Deliver items to designated locations

## Technologies

* ROS 2
* Python
* C++
* Gazebo Simulation Environment

## Learning Outcome

This project demonstrates proficiency with industry-standard robotics software and middleware used throughout the robotics industry.

---

# Portfolio Outcomes

By completing these projects, the portfolio will demonstrate proficiency in:

* Concurrent Programming
* Networking
* Algorithms
* Computer Vision
* Control Systems
* Robotics Middleware
* Localization
* Mapping
* Path Planning
* Sensor Fusion
* Distributed Systems
* Autonomous Navigation

Together, these projects create a strong foundation for pursuing junior-level roles in robotics software engineering, autonomy engineering, embedded systems, or simulation engineering, even without a traditional robotics degree.
