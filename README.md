### **Autonomous Line Follower Robot**

**General Description:**
Development of an autonomous embedded system capable of identifying and following a track marked by a black line, using the Arduino platform. The project integrates DC motor control with analog sensor signal processing to ensure precise real-time navigation.

**Responsibilities and Technical Achievements:**

* **Sensor Integration and Calibration:** Implementation of a data acquisition subsystem using the **QTRSensors** library for two analog sensors. I developed an automatic calibration routine (400 iterations) to ensure the robot's adaptability to various lighting and contrast conditions.
* **Control and Navigation Algorithm:** Designing decision logic that interprets sensor values (on a scale of 0 to 1000) to determine the optimal travel direction: forward, left, or right.
* **Motor Control (PWM):** Managing the propulsion system through **PWM (Pulse Width Modulation)** signals for speed control, allowing smooth transitions between forward movement and steering maneuvers.
* **Diagnosis and Feedback System:** Implementation of a debugging interface via Serial communication and visual feedback through LEDs for monitoring sensor status and movement direction during testing.
* **Code Efficiency:** Utilizing enumerated data types (`enum`) and modular function structuring to ensure readable and maintainable code.

**Technologies Used:**

* **Language:** C++ (Arduino Sketch).
* **Hardware:** Arduino-compatible microcontroller, QTR analog sensors, DC motor drivers, status LEDs.
* **Concepts:** Open-loop control, signal processing, real-time systems, sensor calibration.
