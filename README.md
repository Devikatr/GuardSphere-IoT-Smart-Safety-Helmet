# GuardSphere-IoT-Smart-Safety-Helmet
An IoT-enabled smart safety helmet integrating sensors for fall detection, alcohol detection, GPS tracking, and environmental monitoring to enhance worker safety.


# 🪖 GuardSphere: IoT-Enabled Smart Safety Helmet

## 🧠 Overview
**GuardSphere** is an IoT-enabled smart safety helmet that enhances worker safety in hazardous industries.  
It integrates multiple sensors to detect falls, alcohol presence, and environmental conditions, along with GPS tracking for real-time location monitoring.

---

## ⚙️ Features
- 🚨 **Fall Detection:** Detects sudden impacts or falls and triggers alerts.  
- 🍺 **Alcohol Detection:** Monitors worker sobriety using an MQ-3 sensor.  
- 📡 **GPS Tracking:** Tracks the user’s location for emergency response.  
- 🌡️ **Environmental Monitoring:** Measures temperature, humidity, and other environmental parameters.

---

## 🧩 Hardware Components
- NodeMCU / ESP32  
- MPU6050 (Accelerometer + Gyroscope)  
- MQ3 (Alcohol Sensor)  
- GPS Module (NEO-6M)  
- DHT11 (Temperature & Humidity Sensor)  
- IoT Cloud Platform (e.g. Blynk 

---

## 🧰 Software & Tools
- Arduino IDE  
- Python (for data visualization / IoT integration)  
- Blynk 


---

## 🚀 Working Principle
1. Helmet sensors collect live data (motion, alcohol level, temperature, GPS).  
2. Data is sent to an IoT cloud server.  
3. Alerts are triggered on abnormal readings (e.g., fall or intoxication).  
4. Supervisors can monitor data remotely through the dashboard.

---

## 📷 Demo / Block Diagram
*(Upload your system diagram or prototype photo here later)*  
Example:  
```markdown
![System Diagram](media/system-diagram.png)
