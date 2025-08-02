# IoT-Based Personal Safety Device for Women 👩‍💻🔐

This repository contains the design and implementation of an **IoT-based personal safety device for women** developed using **Proteus simulation**, **Arduino**, and **embedded systems**. The system is capable of detecting emergency conditions and sending automated alerts via SMS with GPS coordinates to predefined contacts.

## 📌 Project Overview

This IoT-enabled device continuously monitors physical and environmental conditions such as:

- Heartbeat
- Body temperature
- Pressure
- Motion

In case of abnormal readings or a panic button press, it triggers an emergency workflow:
- Sends an **SMS alert** using a **GSM module**
- Shares real-time **GPS location**
- Activates an audible **buzzer**
- Includes a **confirmation mechanism** to prevent false alerts

## 🛠️ Technologies & Tools Used

- **Arduino UNO**
- **Proteus 8 Professional** (for circuit simulation)
- **GSM Module (SIM800L)**
- **GPS Module (Neo-6M)**
- **Sensors**: Heartbeat, Temperature, Pressure, IR (Motion)
- **Arduino IDE**, **TinyGPS++**, **SoftwareSerial**

## 🧠 Features

- Continuous monitoring of vitals and movement
- Panic button for manual emergency triggering
- Automatic detection of abnormal sensor data
- GPS + GSM-based location alert system
- Buzzer activation for nearby awareness
- Simple and cost-effective design

## ⚙️ System Workflow

1. Sensors continuously read physical/environmental data
2. If abnormality is detected or button is pressed:
   - A confirmation window allows the user to cancel
   - If not cancelled, an SMS with GPS location is sent
3. Buzzer activates to alert nearby people.

## 🖥️ Circuit Simulation

This is the simulated circuit in **Proteus 8 Professional**. It integrates:

- Arduino UNO
- SIM900D GSM module
- Neo-6M GPS module
- Heartbeat sensor
- Infrared motion sensor
- LM35 temperature sensor
- Buzzer and push buttons

## ✅ Result

The IoT-based personal safety system was successfully designed, simulated in Proteus, and tested using Arduino. The system functioned as intended under various emergency scenarios.

### Observed Outcomes:
- When the panic button was pressed, the system immediately sent an SMS with GPS coordinates to the predefined mobile number.
- In case of abnormal sensor readings (e.g., heartbeat, temperature, pressure, motion), the system:
  - Entered a confirmation state
  - If unconfirmed, triggered an emergency alert
  - Activated the buzzer and sent the alert message with location
- The **buzzer** responded correctly to high-pressure values, drawing local attention.
- All modules (GSM, GPS, sensors) interacted correctly and real-time data was visible through the Serial Monitor.
- The confirmation mechanism helped reduce false alerts.

> ✅ The project achieved its primary goal of providing a low-cost, reliable, and responsive safety system that works without internet and ensures immediate communication during emergencies.
