# 🌱 Smart Irrigation System using Cisco Packet Tracer

## 📌 Problem Statement
To design a smart irrigation system that monitors moisture/water level and automates sprinklers using IoT components in Cisco Packet Tracer, optimizing water usage in agriculture.

## 🌐 Scope of the solution
- Real-time simulation using virtual sensors and actuators
- Automatic control based on water level data
- Central IoT gateway handling decision logic
- Optional mobile control/monitoring extension

## 🎯 Aim
To create an automated irrigation system that turns sprinklers ON/OFF based on moisture/water level readings.

## 📐 Architecture
1. **Sensors**: Two water level monitors (waterlevel1, waterlevel2) sense the soil moisture.
2. **Actuators**: Four lawn sprinklers (sprinkler1 to sprinkler4) irrigate based on sensor data.
3. **IoT Gateway**: DLC100 Home Gateway collects sensor data and triggers actuators.
4. **Optional**: Smartphone0 used for remote viewing or override.

Each sensor sends data to the gateway. If moisture falls below a set threshold (e.g., <5), the sprinklers are activated automatically.

## Required Components

- 2 × Water Level Monitor (Moisture Sensors)
- 4 × Lawn Sprinkler
- 1 × DLC100 IoT Home Gateway
- 1 × Smartphone (for optional remote monitoring)
- Cisco Packet Tracer (Simulation Environment)

## 🔩 Circuit Diagram
![image](https://github.com/user-attachments/assets/e0d3173a-21ad-4424-a4b8-ee7f992c3d07)


## 🧠 Logic Used
If water level is below threshold (e.g., < 5), turn on sprinklers.
![image](https://github.com/user-attachments/assets/af4dc0b1-00a9-4aee-8c9b-dde6de90302b)

## 🔩 Simulation video


https://github.com/user-attachments/assets/d12af10b-1b06-41f3-9e3e-810544aedd55




