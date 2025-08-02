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

## ✅ Tested Seceniors 
