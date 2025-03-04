# Human-Following Robot

## Team Members:
- **Nageswara Janapareddy**, njanapar@buffalo.edu

## Project Objective
We propose to develop a human-following robot using Arduino and three ultrasonic sensors to autonomously track and follow a person. The robot will be capable of measuring distance in three directions (front, left, and right) and use this information to navigate and follow a human target. This project will focus on the integration of ultrasonic sensors for better tracking accuracy, allowing the robot to follow a person effectively.

## Contributions
This project is unique because it uses three ultrasonic sensors to create a more efficient and accurate human-following mechanism. Most human-following robots typically use one ultrasonic sensor or infrared sensors, but the addition of three ultrasonic sensors provides better distance measurements and improves the robot's ability to follow the human in various environments. The Arduino-based system will process the sensor data, control the motors, and ensure the robot moves accordingly.

## Project Plan
We will use an **Arduino UNO** as the main processing unit for reading sensor data and controlling the robot's movement. The necessary components for this project include:
- **Arduino UNO** board
- **Three ultrasonic sensors** for distance measurement
- **L298N motor driver** to control the motors
- **Two DC motors and wheels** for movement
- **Li-ion batteries** to power the robot
- **Breadboard, jumper wires, and other electronic components**

The robot will use the readings from the ultrasonic sensors to determine its distance from a human and adjust its movement accordingly. If the robot is too far from the target, it will move forward, and if it gets too close, it will move backward or adjust direction. The robot will continuously track and follow the human within a specified range.

## Milestones/Schedule Checklist
- **Complete hardware setup (robot chassis, motors, sensors, microcontroller)**
  - Assigned to: Nageswara Janapareddy
  - Due Date: March 10
- **Install Arduino IDE and necessary libraries**
  - Assigned to: Nageswara Janapareddy
  - Due Date: March 12
- **Connect ultrasonic sensors and motor driver module**
  - Assigned to: Nageswara Janapareddy
  - Due Date: March 15
- **Write and test basic Arduino code for sensor readings**
  - Assigned to: Nageswara Janapareddy
  - Due Date: March 25
- **Test robot movement with sensor feedback**
  - Assigned to: Nageswara Janapareddy
  - Due Date: March 30
- **Implement human-following logic based on sensor data**
  - Assigned to: Nageswara Janapareddy
  - Due Date: April 5
- **Create progress report**
  - Assigned to: Nageswara Janapareddy
  - Due Date: April 6
- **Test and refine the human-following functionality**
  - Assigned to: Nageswara Janapareddy
  - Due Date: April 15
- **Optimize movement accuracy and sensor calibration**
  - Assigned to: Nageswara Janapareddy
  - Due Date: April 20
- **Create final presentation**
  - Assigned to: Nageswara Janapareddy
  - Due Date: May 6
- **Provide system documentation (README.md)**
  - Assigned to: Nageswara Janapareddy
  - Due Date: May 13

## Measures of Success
We will measure success based on the ability of the robot to:
- **Track and follow a human** autonomously, adjusting its position based on sensor data.
- **Navigate effectively** using three ultrasonic sensors for more precise movement control.
- **React appropriately** to distance changes by moving forward, backward, or turning as necessary.
- **Successfully avoid obstacles** while following a person within a specified range.

## Necessary Components Needed for Human Following Robot
- **Arduino UNO board** ×1
- **Ultrasonic sensor** ×3
- **L298N motor driver** ×1
- **Robot chassis**
- **DC motors** ×2
- **Wheels** ×2
- **Li-ion battery 3.7V** ×2
- **Battery holder** ×1
- **Breadboard**
- **Ultrasonic sensor holder** ×3
- **Switch and jumper wires**

## Human Following Robot Circuit Diagram
Here is the schematic diagram of the Human-following robot circuit:

![Human Following Robot Circuit](./human-following-robot-circuit.png)

