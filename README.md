# EV-Charging
Smart EV Charging Safety and Automatic Cutoff System
⚡ Smart EV Charging Safety and Automatic Cutoff System

📌 Project Overview

The Smart EV Charging Safety and Automatic Cutoff System is an electronic safety project designed to improve the safety of electric vehicle charging, particularly during overnight or unattended charging.

The system monitors temperature and smoke levels during charging. If abnormal temperature or smoke conditions are detected, the system activates an alarm and automatically disconnects the charging supply using a relay. This helps reduce the risk of overheating and potential fire hazards.

The main goal of this project is to provide an affordable safety solution that helps protect electric vehicles and their owners during charging.

🎯 Objectives

- To monitor temperature and smoke levels during EV charging.
- To detect abnormal conditions at an early stage.
- To provide an alert using a buzzer when a potential hazard is detected.
- To automatically cut off the charging supply during unsafe conditions.
- To reduce the risks associated with unattended and overnight charging.
- To develop a simple, cost-effective EV charging safety prototype.

🧰 Components Used

- Arduino microcontroller
- Smoke sensor
- Temperature sensor
- Relay module
- Buzzer
- LED indicators
- Voltage sensor
- Current sensor
- 5V, 1A power adapter
- Connecting wires
- Breadboard or suitable circuit board
- Prototype charging load

Note: Update the component list if any of these components are not included in your final prototype.

⚙️ Working Principle

The system continuously monitors the charging environment using smoke and temperature sensors.

Step 1: System Initialization

The Arduino initializes the sensors and checks the input readings.

Step 2: Temperature Monitoring

The temperature sensor measures the temperature near the charging setup. The Arduino checks whether the temperature is within the configured safe operating range.

Step 3: Smoke Detection

The smoke sensor monitors the surrounding environment for smoke or abnormal smoke levels that may indicate a potential fire hazard.

Step 4: Hazard Detection

If the temperature exceeds the configured limit or the smoke level crosses the specified threshold, the Arduino identifies a potentially unsafe condition.

Step 5: Alert Generation

The buzzer activates to alert the vehicle owner or nearby people about the detected abnormality.

Step 6: Automatic Cutoff

The Arduino controls the relay to disconnect the charging supply when a hazardous condition is detected.

Step 7: Continuous Monitoring

The system continues monitoring the sensors so that abnormal conditions can be identified during unattended charging.

🔄 System Workflow

Power ON → Sensor Initialization → Temperature and Smoke Monitoring → Condition Analysis → Hazard Detected?

- NO: Continue monitoring the charging environment.
- YES: Activate the buzzer and disconnect the charging supply through the relay.

🌟 Key Features

- Real-time temperature monitoring
- Smoke detection for early hazard identification
- Automatic charging cutoff during detected unsafe conditions
- Audible warning through a buzzer
- Continuous monitoring during unattended charging
- Potential integration with voltage and current monitoring
- Affordable and compact prototype design

🏠 Applications

- Electric scooter charging safety
- Electric bike charging systems
- Residential EV charging setups
- Overnight and unattended charging monitoring
- Educational EV safety projects
- Experimental charging safety prototypes

✅ Advantages

- Helps identify potential charging hazards.
- Reduces the need for continuous manual supervision.
- Provides an audible warning when abnormal conditions occur.
- Helps prevent continued charging after a detected hazard.
- Supports safer charging practices.
- Demonstrates the practical application of sensors, microcontrollers, and automatic control systems.

🔮 Future Enhancements

- Integrate an IoT module for mobile notifications.
- Send alerts through a mobile application.
- Monitor temperature trends to identify gradual overheating.
- Add real-time voltage and current monitoring.
- Store sensor readings for analysis.
- Introduce automatic fault logging and event history.
- Develop a more advanced system for EV battery health and charging safety monitoring.

📸 Project Gallery

This repository can include photographs and diagrams of the project, such as:

- Block Diagram: Illustrates the connections between the Arduino, sensors, buzzer, and relay.
- Circuit Diagram: Shows the electrical connections between the components.
- Hardware Setup: Displays the assembled prototype.
- Working Model: Demonstrates the smoke detection, temperature monitoring, alarm, and cutoff mechanism.
- Team Photo: Shows the team members involved in the project.

🎓 Learning Outcomes

Through this project, we gained practical knowledge of:

- Arduino-based embedded systems
- Sensor interfacing and monitoring
- Temperature and smoke detection
- Relay-based automatic control
- Basic electrical safety concepts
- Hardware integration and prototype development
- The role of automation in EV charging safety

⚠️ Safety Disclaimer

This project is an educational prototype and is not a certified EV charging protection device. It must not be relied upon as the sole protection against battery fires or electrical faults.

Testing should be performed using a safe, low-voltage prototype load. Actual EV charging systems require appropriately rated protection devices, electrical isolation, and professional safety validation before deployment.

📝 Conclusion

The Smart EV Charging Safety and Automatic Cutoff System demonstrates how sensor-based monitoring and automatic control can help improve EV charging safety. By monitoring smoke and temperature, activating an alarm, and disconnecting the charging supply when unsafe conditions are detected, the prototype provides a foundation for developing smarter charging safety solutions.

The project highlights the importance of embedded systems and automation in reducing potential hazards associated with unattended electric vehicle charging.

---

Project Domain: Electric Vehicle Safety | Embedded Systems | Automation

Project Type: Academic Engineering Project

Department: Electronics and Communication Engineering (ECE)

⭐ If you find this project interesting, consider giving this repository a star!
