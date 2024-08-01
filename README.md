# Autonomous Underwater Glider Drone for Environmental Monitoring of Lakes

**Project carried out during the course of a Robotics MSc at King's College London**   

## Product Brief

### About

The Autonomous Underwater Glider is designed to enhance lake health monitoring by overcoming the limitations of traditional surveying methods. This glider navigates lake depths efficiently, offering extensive temporal and spatial coverage while optimizing resources. It operates autonomously, eliminating the need for human intervention and ensuring continuous data collection. Equipped with advanced sensors, it captures crucial environmental data necessary for effective mitigation strategies.




### Mission Statement

Our mission is to revolutionize lake health monitoring through the development of an autonomous underwater glider. This project aims to provide a cost-effective, comprehensive solution that ensures continuous data collection for effective environmental preservation.



[Watch the video demonstration](https://emckclac-my.sharepoint.com/:v:/g/personal/k23117823_kcl_ac_uk/ERo8BjIcuO9GiismgcfTDVgBBQ3YHtATHzcV7ot-Q-JfUQ?e=ZMMHtV&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)



### Technical Analyses
The Glider was first simulated in SIMULINK along with the various forces that would act on it. The final diagram is shown below. It was then used to design a PID controller to control the pitch angle of the glider 
![simulink](https://github.com/user-attachments/assets/f0a9834c-b10e-4f4f-9ba3-5405282cd520)
#### Buoyancy Engine

A syringe-based buoyancy engine was selected for its effectiveness in state-of-the-art underwater gliders. Key constraints included size, strength, and availability. The design met these constraints, ensuring the glider's functionality at the target depth of 100 meters.


### Control System Overview
The glider was controlled using an arduino uno. With the Depth Conditions being monitored by both a timer and an Ultrasonic Sensor

![statespace](https://github.com/user-attachments/assets/7f930494-8882-4be8-a410-c937b8547c21)



### Electronic System Overview

![Circuit](https://github.com/user-attachments/assets/c7c3eb1f-6083-46e9-ab1f-fe229bf79518)



