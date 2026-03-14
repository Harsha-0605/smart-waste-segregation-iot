# Smart Waste Segregation System (IoT)

![Circuit Diagram](circuit/smart-waste-segregation-circuit.png)

## Overview
The Smart Waste Segregation System is an IoT-based solution designed to automate the process of waste classification and disposal.  
The system uses sensors and a microcontroller to detect waste type and control a mechanical mechanism that directs the waste into appropriate compartments.

This project helps improve waste management efficiency and supports smart city initiatives.

---

## Problem Statement
Manual waste segregation is inefficient and often leads to improper recycling.  
An automated system can detect waste type and sort it into the correct category to improve recycling and reduce environmental impact.

---

## Features
- Automatic waste detection using sensors
- Motorized waste segregation mechanism
- Real-time sensor-based decision making
- Modular hardware design
- Scalable for smart waste management systems

---

## Hardware Components
| Component | Description |
|----------|-------------|
| Arduino Uno | Main microcontroller |
| IR Sensor | Detects waste object |
| Rain Sensor | Detects wet waste |
| Stepper Motor | Rotates segregation mechanism |
| A4988 Driver | Controls stepper motor |
| Breadboard | Circuit connections |
| Power Supply | 12V external supply |

---

## Software Used
- Arduino IDE
- Embedded C / Arduino programming
- Sensor input processing
- Motor control logic

---

## Project Structure
smart-waste-segregation-iot
│
├── circuit
│ └── smart-waste-segregation-circuit.png
│
├── code
│ └── smart_waste_segregation.ino
│
├── docs
│ ├── project_report.md
│ ├── components_list.md
│ ├── pin_connections.md
│ └── working.md
│
├── images
│ └── prototype.jpg
│
└── README.md


---

## Working Principle
1. Waste is placed into the smart dustbin.
2. The IR sensor detects the presence of waste.
3. The rain sensor checks if the waste is wet or dry.
4. The Arduino processes the sensor input.
5. The stepper motor rotates the bin mechanism to the appropriate compartment.

---

## Circuit Diagram
See the complete circuit inside the **circuit** folder.

---

## Applications
- Smart cities
- Automated waste management
- Recycling plants
- Environmental monitoring systems

---

## Future Improvements
- AI-based waste classification using camera
- Cloud-based monitoring dashboard
- IoT connectivity for smart city integration
- Machine learning waste recognition

---

## Author
V Harsha Teja  
Embedded Systems | IoT | AIoT Enthusiast
