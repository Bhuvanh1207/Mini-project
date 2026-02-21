# ⛏️ IoT-Based Coal Mine Safety Monitoring & Alert System



## 📌 Overview

The **IoT-Based Coal Mine Safety Monitoring & Alert System** is designed to enhance worker safety in underground coal mines by continuously monitoring hazardous environmental parameters and generating real-time alerts.

This system detects methane gas leakage, abnormal temperature rise, humidity levels, and fire presence using IoT sensors. The collected data is transmitted wirelessly to a cloud dashboard for remote monitoring and emergency alert generation.

---

## 🎯 Objectives

- Monitor Methane (CH₄) gas levels
- Detect temperature rise and fire hazards
- Monitor humidity levels
- Provide real-time alerts
- Enable remote monitoring via IoT dashboard
- Reduce accidents and improve mine safety

---

## 🛠️ Hardware Components

| Component | Description |
|-----------|------------|
| ESP8266  | Microcontroller Unit |
| MQ-4 / MQ-2 | Methane Gas Sensor |
| DHT11 / DHT22 | Temperature & Humidity Sensor |
| Flame Sensor | Fire Detection |
| Buzzer | Alert System |
| LCD Display | Local Display (Optional) |
| GSM / WiFi Module | Communication Module |
| Power Supply | 5V / 12V |

---

## 💻 Software & Technologies Used

- Embedded C / Arduino IDE  
- ThingSpeak / Blynk / Firebase  
- MQTT / HTTP Protocol  
- WiFi / GSM Communication  
- Git & GitHub  

---

## ⚙️ System Architecture

![Block Diagram](![WhatsApp Image 2026-02-21 at 20 00 16](https://github.com/user-attachments/assets/636822df-3f57-4dc1-978f-51430d0fb5db)
)

### Working Flow:
1. Sensors collect environmental data.
2. Microcontroller processes sensor values.
3. Data is transmitted via WiFi/GSM.
4. Cloud platform stores and visualizes data.
5. Alerts are triggered if thresholds exceed safe limits.
6. Buzzer & notifications warn workers immediately.

---

## 📊 Alert Conditions

| Parameter | Condition | Action |
|-----------|------------|--------|
| Methane Gas | Above Threshold | Buzzer + Cloud Alert |
| Temperature | Above Safe Level | Emergency Alert |
| Flame Detection | Flame Detected | Immediate Alarm |
| Humidity | Abnormal Level | Warning |

---

## 🔔 Alert Mechanism

- 🔊 Local Buzzer Alarm  
- 📱 SMS Notification (via GSM)  
- 🌐 Cloud Dashboard Alert  
- 📲 Push Notifications  

---

## 📷 Project Demonstration

### Circuit Diagram
[View Circuit Diagram](<img width="1167" height="996" alt="image" src="https://github.com/user-attachments/assets/e9650af8-69d4-4455-9b1c-9c1d51930c6f" />
)


### Demo Video
[Watch Demo Video](https://www.linkedin.com/posts/bhuvan-h-8b557232b_iot-blynkiot-coalminesafety-ugcPost-7406255143710552064-WNIq?utm_source=share&utm_medium=member_android&rcm=ACoAAFMy9YkBSpeUIvtvhvPKjVBeHcCPV6ouwZ8)


## 🚀 Future Enhancements

- AI-based predictive hazard analysis  
- Oxygen level monitoring  
- Miner tracking system  
- LoRa communication for long-range transmission  
- Mobile application integration  

---

## 📈 Applications

- Underground Coal Mines  
- Industrial Hazard Zones  
- Tunnels  
- Gas Storage Plants  

---

## 👨‍💻 Author

**Bhuvan and team**  
ECE Engineer  

🔗 LinkedIn: [Your LinkedIn Profile](https://www.linkedin.com/in/bhuvan-h-8b557232b)  
💻 GitHub: [Your GitHub Profile](https://github.com/Bhuvanh1207)  

---

## ⭐ Support

If you found this project useful, please ⭐ star the repository and share your feedback!
