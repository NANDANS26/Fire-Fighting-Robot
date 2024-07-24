# Firefighting Robot Project

## Overview

This project involves the design and implementation of an autonomous firefighting robot capable of detecting and extinguishing fires. The robot is built using an Arduino UNO, L298N motor drivers, DC motors, flame sensors, a water pump, and other components. The primary objective is to create a robot that can operate safely and efficiently in fire-prone environments.

## Team Members

- Bhanu Chandan
- Neharaj P
- Latika G
- Karukonda Tirumala
- Nandan S

## Mentor

- Stapley V S Sir

## Event

This project was demonstrated at the Demo Day "Vision Expo" organized by PES College of Engineering in collaboration with Inuinity on June 20, 2024.

## Components

- Arduino UNO R3
- L298N Motor Driver (x2)
- DC Motors (x4)
- Wheels (x4)
- Flame Sensors (x3)
- Mini Servo Motor
- Mini Water Pump (3.7V)
- Relay Module
- 18650 Batteries (x2)
- Battery Holder
- Breadboard
- Jumper Wires (Male to Male / Male to Female)
- Water Pipe
- Small Water Tank

## Circuit Diagram

![Circuit Diagram](schematics/circuit_diagram.png)

## Block Diagram

![Block Diagram](schematics/block_diagram.png)

## Features

- **Autonomous Fire Detection**: The robot uses flame sensors to detect the presence of fire and navigate towards it.
- **Water Pump Mechanism**: Equipped with a water pump and a servo motor to spray water and extinguish the fire.
- **Motor Control**: Utilizes L298N motor drivers to control the movement of the robot.
- **Relay Control**: A relay module is used to control the activation of the water pump.

## How It Works

1. **Initialization**: The robot initializes all sensors, motors, and the relay module.
2. **Fire Detection**: Flame sensors continuously monitor for the presence of fire.
3. **Navigation**: When a fire is detected, the robot moves towards the fire source.
4. **Extinguishing**: Upon reaching the fire, the robot activates the water pump to spray water and extinguish the fire.
5. **Patrol**: If no fire is detected, the robot continues to patrol the area.

## Usage

To use this project, follow these steps:

1. **Hardware Setup**:
   - Assemble the robot chassis with the DC motors and wheels.
   - Connect the Arduino UNO, motor drivers, flame sensors, relay module, and other components as per the circuit diagram.
   - Attach the water pump and servo motor to the robot.
   - Ensure all connections are secure and the batteries are charged.

2. **Software Setup**:
   - Upload the Arduino sketch to the Arduino UNO.
   - Ensure the correct libraries are installed for the servo motor and any other required components.

3. **Operation**:
   - Power on the robot.
   - The robot will start patrolling the area.
   - When a fire is detected, the robot will navigate towards it and activate the water pump to extinguish the fire.

## Future Work

1. **Enhanced Sensors**: Integrate additional sensors (e.g., temperature sensors, smoke detectors) for more accurate fire detection.
2. **Improved Navigation**: Implement advanced algorithms for obstacle detection and path planning.
3. **Extended Operation**: Increase battery capacity and optimize power usage for longer operational periods.
4. **Scalability**: Develop cost-effective production methods to make the robot accessible for widespread use.

## Acknowledgements

We would like to thank our mentor, Stapley V S Sir, for his guidance and support throughout this project. We also appreciate the support from PES College of Engineering and Inuinity for organizing the Vision Expo event.

