# Autonomous Underwater Glider Drone for Environmental Monitoring of Lakes

**Authors**: Sophie Caplan, William Droin, Rohith Raghunathan Nair, Doran Moison, Dhruv Pandit, Arushi Khokhar  
**Institution**: King’s College London, Department of Natural, Mathematical & Engineering Sciences  
**Program**: MSc in Robotics  
**Date**: 16th April 2024

## Product Brief

### About

The Autonomous Underwater Glider is designed to enhance lake health monitoring by overcoming the limitations of traditional surveying methods. This glider navigates lake depths efficiently, offering extensive temporal and spatial coverage while optimizing resources. It operates autonomously, eliminating the need for human intervention and ensuring continuous data collection. Equipped with advanced sensors, it captures crucial environmental data necessary for effective mitigation strategies.

### Key Elements

- **Figure**: Detailed CAD model of the glider showcasing its main components.

### Technical Specifications

| Component                       | Value                                          |
|---------------------------------|------------------------------------------------|
| **General**                     |                                                |
| Dry Weight                      | 31.934 Kg                                      |
| Total Length                    | 1970mm                                         |
| **Hull**                        |                                                |
| Length                          | 1700mm                                         |
| Outer diameter                  | 150mm                                          |
| Inner diameter                  | 140mm                                          |
| Material                        | Acrylic                                        |
| **Control System and Sensors**  |                                                |
| Linear Actuators x2             | 12v, 3.5A, 300mm (Length), 25% (Duty Cycle)    |
| Motor Drivers x2                | BTS7960B (5v, 43A)                             |
| Temperature Sensor              | TSYS01 (3.3v), Range: -40 to +125 C, Resolution: 0.1 C |
| Sonar                           | Ping Sonar (3.3v), Range: 0.3 - 100m, Resolution: 0.001m |
| Microcontroller                 | Arduino Uno R4, Core: ESP32-S3, Connectivity: USB-C, WiFi, Bluetooth |
| **Buoyancy Engine**             |                                                |
| Syringe x2                      | Volume: 200ml                                  |
| **Battery/Pitch Control Module**|                                                |
| NiMH Battery (D)                | 1.2v, 10000mAH                                 |
| **Wings**                       |                                                |
| Aluminium Wings x2              | 600mm x 200mm (Length X Width)                 |
| Wing Mounts (Upper and Lower)   | 270mm x 200mm (Length X Width)                 |
| Bolts                           | 6                                              |
| Nuts                            | 6                                              |
| **Other**                       |                                                |
| End caps x2, Rubber             | 165mm x 155mm (Outer diameter X Inner diameter)|
| Nose                            | 250mm                                          |
| Reinforcing Mesh, x9            | 130mm x 130.5mm (Outer diameter X Inner diameter) |
| Mesh Plugs                      | 19.5mm x 4mm (Outer diameter X Inner diameter) |

### Mission Statement

Our mission is to revolutionize lake health monitoring through the development of an autonomous underwater glider. This project aims to provide a cost-effective, comprehensive solution that ensures continuous data collection for effective environmental preservation.

### Conclusion

The Autonomous Underwater Glider represents a significant advancement in lake health monitoring. It offers extensive spatial and temporal coverage, autonomous operation, and the ability to incorporate advanced sensors. This innovative solution provides a cost-effective alternative to traditional methods, improving the frequency and accuracy of data collection and optimizing resource allocation for sustainable monitoring practices.

![Prototype Image](link-to-image)  
*Figure: Prototype of the autonomous underwater glider tested at Mercers Lake, Redhill, UK.*

[Watch the video demonstration](https://emckclac-my.sharepoint.com/:v:/g/personal/k23117823_kcl_ac_uk/ERo8BjIcuO9GiismgcfTDVgBBQ3YHtATHzcV7ot-Q-JfUQ?e=ZMMHtV&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

## Appendices

### Follow Up on Project Plan

The project plan provided a clear direction, allowing important decisions on functionalities and material choices. Agile adjustments were necessary as the project progressed, including changes to the hull material and sensor choices due to supply limitations and time constraints. Despite these challenges, the project successfully created a minimum viable product with modular design for future enhancements.

### Technical Analyses

#### Buoyancy Engine

A syringe-based buoyancy engine was selected for its effectiveness in state-of-the-art underwater gliders. Key constraints included size, strength, and availability. The design met these constraints, ensuring the glider's functionality at the target depth of 70 meters.

#### Battery Module

NiMH batteries were chosen over Li-ion due to supplier limitations and safety regulations. Although Li-ion offers superior qualities, NiMH batteries provided a feasible alternative within the project's constraints.

### Testing Protocol and Results

Three real-world tests were conducted to ensure a fully operational product: two at the Ocean Towing Tank at University College London and one at Mercers Lake in Redhill, UK. Precautions were taken to prevent drone loss or damage, ensuring successful testing outcomes.

## Technical Diagrams

[Insert technical diagrams here]

## Bill of Materials

[Insert bill of materials here]

## Description of Computer Code

### Control System Overview

[Insert control system overview here]

### Electronic System Overview

[Insert electronic system overview here]

### Software Architecture

[Insert software architecture here]

## Photos of Final Product

[Insert photos of final product here]

## Testing Protocol and Results

### Testing Results

[Insert testing results here]
