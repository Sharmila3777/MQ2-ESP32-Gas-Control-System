An IoT-based gas leakage detection and safety automation system built using an ESP32 and MQ-2 sensor.
The system provides real-time monitoring, automatic alerts, cloud logging, and safety control actions to prevent
gas-related accidents in homes, hotels, and industries.

---

## 🚨 Problem Statement
Gas leaks in households, commercial places, and industries can lead to:
- Fires and explosions
- Toxic gas exposure
- Property damage
- Delayed manual detection

Existing systems lack:
- Real-time alerts
- Automation
- Remote monitoring
- Cloud data logging

---

## 🎯 Objectives
- Detect LPG/Methane gas levels in real-time.
- Trigger buzzer, LEDs, LCD, and mobile notifications.
- Automatically control exhaust fans or gas valves using a relay.
- Display live readings on an LCD.
- Send data to cloud platforms like ThingSpeak / AWS / Blynk.
- Enable remote and continuous monitoring.

---

## 🧰 Major Components Used
- **ESP32 Microcontroller**
- **MQ-2 Gas Sensor**
- **Relay Module**
- **Buzzer**
- **Red & Green LEDs**
- **LCD Display**
- **5V Power Supply**

---

## 🏗️ System Architecture
- MQ-2 sensor detects gas concentration.
- ESP32 processes gas values using ADC input.
- If threshold is crossed → alarm activates.
- Relay controls exhaust/gas valve.
- WiFi sends sensor data to cloud.
- Cloud dashboard displays real-time and historical data.

---
