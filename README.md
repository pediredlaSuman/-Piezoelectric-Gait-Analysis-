

# Piezoelectric Sensor for Gait Analysis

## Description
This project involves creating a piezoelectric-based insole for gait analysis. The insole uses sensors to detect and analyze walking and running patterns by measuring forces and foot strikes.

## Table of Contents
- [Objective](#objective)
- [Components Used](#components-used)
- [Procedure](#procedure)
- [Diagram](#diagram)
- [Code and Output](#code-and-output)
- [Challenges](#challenges)

## Objective
To design an insole with piezoelectric sensors that can measure and analyze gait patterns in real-time using Arduino and accelerometer data.

## Components Used
- 4 x Piezoelectric Sensors  
- 1 x Arduino UNO  
- 1 x Accelerometer ADXL 345  
- 1 x Mini Breadboard  
- Resistor  
- Jumper Wires

## Procedure
1. **Sensor Setup:** Connect the piezoelectric sensors in series in pairs. Solder jumper wires to the outer rim and inner parts of each sensor.
2. **Placement in Insole:** Place one pair of sensors near the toes and the other pair near the ankle within the insole.
3. **Connections to Arduino:** Attach the sensors and the accelerometer to the mini breadboard and connect them to the Arduino UNO.
4. **Upload Code:** Prepare the Arduino code and upload it to the board for sensor data collection and visualization.

![Procedure Image](https://github.com/user-attachments/assets/08de778d-8dbb-4a82-8819-171b65f04fae)

## Diagram
Below is the connection diagram for the setup of the piezoelectric sensor and Arduino system.

![Diagram Image](https://github.com/user-attachments/assets/8bf17ec4-9748-485a-a527-00e12bc9e66b)

## Code and Output
The Arduino code captures sensor data and visualizes the output, providing gait pattern analysis.

![Code and Output Image](https://github.com/user-attachments/assets/bdfa591f-d533-4fb3-b4c3-ec2b78a45cc8)

## Challenges
1. **Variability in Gait:** Human gait patterns vary between individuals, making it challenging to standardize the readings.
2. **Sensor Placement:** Proper placement of sensors is crucial for accurate data collection and can affect the results.
3. **Technical Limitations:** Variations in equipment and software may lead to inconsistent data across different setups.

