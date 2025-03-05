# Underwater Sea Perch Model

## Introduction
The **Underwater Sea Perch Model** is a remotely operated underwater vehicle (ROV) designed for real-time control and data acquisition. It features three motors, enabling **3 degrees of freedom (DOF)** for efficient underwater maneuverability. The system is powered by an **ESP32 microcontroller**, integrated with **Arduino IoT Cloud** for remote monitoring and control. Additionally, a waterproof **ultrasonic sensor** is used for distance measurement, providing crucial object detection capabilities.

---

## Working Principle
The ROV utilizes **three DC motors** to achieve movement in three axes:
- **Forward and backward motion** (X-axis)
- **Lateral movement (left and right)** (Y-axis)
- **Vertical ascent and descent** (Z-axis)

Each motor is controlled via **pulse width modulation (PWM)**, allowing precise speed regulation. The **ESP32 microcontroller** acts as the brain of the system, handling motor control signals, sensor data processing, and real-time communication with the Arduino IoT Cloud.

---

## Interface and Control
### 1. **ESP32 Microcontroller**
- Acts as the central controller.
- Interfaces with the motors, ultrasonic sensor, and IoT cloud.

### 2. **Arduino IoT Cloud**
- Provides real-time data visualization.
- Enables remote control of the ROV via a user-friendly interface.

### 3. **Waterproof Ultrasonic Sensor**
- Measures the distance between the ROV and underwater objects.
- Enhances navigation and collision avoidance.

### 4. **Display Unit on Arduin IOT Cloud**
- Shows real-time sensor readings and control parameters.
- Assists the operator in decision-making during navigation.

---

## Features
✔ **Three-degree-of-freedom movement** for versatile underwater navigation.  
✔ **ESP32-based real-time control** via Arduino IoT Cloud.  
✔ **Waterproof ultrasonic sensor** for object detection and distance measurement.  
✔ **User interface with real-time monitoring** through a display.  
✔ **Custom PCB design** (future integration) for optimized electronics.  

---

## Future Enhancements
🔹 **Integration of a camera module** for live underwater video feed.  
🔹 **Enhanced autonomy** using AI-based navigation algorithms.  
🔹 **Battery optimization** for extended operational time.  
🔹 **Pressure and temperature sensors** for environmental analysis.  

---

## How to Use
1. **Power on the system** and ensure a stable connection with Arduino IoT Cloud.
2. **Use the IoT dashboard** to control motor speeds and directions.
3. **Monitor real-time sensor data** on the display unit.
4. **Use ultrasonic feedback** to avoid obstacles and navigate efficiently.
5. **Shutdown properly** after operation to preserve battery life.

---

## Contributions
Contributions and improvements are welcome! Feel free to submit a pull request or report issues.

### Author
👤 **Akanksha9821**  
📌 *Electronics & Communication Engineering *
