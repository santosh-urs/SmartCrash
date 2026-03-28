# SmartCrash
Hardware Project
🚗 IoT-Based Vehicle Accident Alert System
📌 Project Description

This project is an IoT-based vehicle safety system designed to detect accidents and automatically send alerts with the vehicle’s location. The system uses sensors and communication modules integrated with an Arduino microcontroller to improve emergency response time.

🎯 Objective

The main objective of this project is to:

Detect accidents using motion sensing
Send real-time location to an emergency contact
Enable remote vehicle control using Bluetooth
Improve safety and reduce response delay
⚙️ Components Used
Arduino UNO
L298N Motor Driver
HC-05 Bluetooth Module
MPU6050 Accelerometer Sensor
NEO-6M GPS Module
GSM Module (SIM800/SIM900)
DC Motors (4)
Li-ion Battery (7.4V)
Additional 4V Batteries (for motor power)
Buck Converter
Breadboard and Connecting Wires
🔧 Working Principle
The vehicle is controlled using a mobile phone via Bluetooth communication.
The MPU6050 sensor continuously monitors acceleration and detects sudden impacts.
When an accident is detected:
The vehicle stops immediately
GPS module fetches current location
GSM module sends an SMS with location
A call is made to the emergency contact
The system ensures quick response during emergencies.
🔌 System Architecture

The system consists of an Arduino microcontroller connected to various modules:

Bluetooth module for control
Motor driver for vehicle movement
MPU6050 for accident detection
GPS module for location tracking
GSM module for communication
🚀 Features
Real-time accident detection
Automatic SMS alert with GPS location
Emergency calling system
Wireless vehicle control using Bluetooth
Low-cost and efficient system
⚠️ Limitations
GPS requires open sky for accurate location
GSM network availability is required
L298N driver has limited current capacity
Sensor sensitivity needs calibration
🔮 Future Enhancements
Integration with mobile app
Cloud-based tracking system
Use of advanced motor drivers
Adding camera for live monitoring
AI-based accident detection
📚 References
Arduino Documentation – https://docs.arduino.cc/
MPU6050 Datasheet – https://www.alldatasheet.com
SIM800 GSM Module Guide – https://lastminuteengineers.com
NEO-6M GPS Tutorial – https://lastminuteengineers.com
Circuit Digest Projects – https://circuitdigest.com
👨‍💻 Conclusion

This project demonstrates how IoT technology can be used to enhance vehicle safety. By combining sensors, communication modules, and automation, the system provides a reliable and efficient accident alert mechanism.
