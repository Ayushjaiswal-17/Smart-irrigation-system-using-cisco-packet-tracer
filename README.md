# 🌱 Smart Irrigation System using Cisco Packet Tracer

## 📌 Problem Statement
To design a smart irrigation system that monitors moisture/water level and automates sprinklers using IoT components in Cisco Packet Tracer, optimizing water usage in agriculture.

## 🎯 Aim
To create an automated irrigation system that turns sprinklers ON/OFF based on moisture/water level readings.

## 📐 Architecture
- Two Water Level Monitors track soil moisture.
- Four Lawn Sprinklers are used for watering.
- All devices are connected to a central Home Gateway.
- A Smartphone is optionally used for remote monitoring/control.

![Circuit Diagram](./circuit-diagram/smart_irrigation_system.png)

## 🧠 Logic Used
If water level is below threshold (e.g., < 14), turn on sprinklers.
```javascript
function loop() {
    var moisture = analogRead(1);
    if (moisture < 14) {
        digitalWrite(2, HIGH); // Turn on sprinkler
    } else {
        digitalWrite(2, LOW); // Turn off sprinkler
    }
}
