# 💧 IoT Based Water Level Monitoring & Pump Control System  
### ESP8266 · Ultrasonic Sensor · Adafruit IO · Automation

---

## 📘 Overview
This project presents an **IoT-based automated water tank monitoring and pump control system** using an ESP8266 and an ultrasonic sensor.  
The system measures real-time water levels, prevents tank overflow, avoids pump dry runs, and provides mobile-based monitoring through **Adafruit IO**.

It is designed to be **cost-effective, scalable, and reliable** for residential, institutional, and industrial water management.

---

## 🚀 Features
- 🟦 Real-time water level monitoring  
- 🟩 Automatic pump ON/OFF control  
- 🌐 IoT dashboard on Adafruit IO  
- 📡 Wireless monitoring via WiFi  
- 🔔 Alerts for overflow and low water levels  
- ⚙️ Manual pump control via app  
- 💰 Low-cost and scalable design  

---

## 🧩 Components Used
| Component | Description |
|----------|-------------|
| ESP8266 | WiFi-enabled microcontroller |
| Ultrasonic Sensor (HC-SR04) | Measures tank water level |
| Relay Module | Controls pump motor |
| DC/AC Pump | Water pumping unit |
| Adafruit IO | Cloud monitoring & control |
| Power Supply | 5V / 12V depending on setup |

---

## 📝 Problem Statement
Water tank overflow is a common issue leading to:
- Water wastage  
- Damage to surroundings  
- Increased water bills  
- Inefficiency due to manual monitoring  

A smart IoT solution is required to **automatically sense water levels**, control pump operation, and provide real-time monitoring.

---

## 🎯 Objectives
1. To design and implement an automated water level monitoring system using ESP8266 and ultrasonic sensor.  
2. To integrate Adafruit IO for real-time visualization and remote pump control.  
3. To prevent water overflow and pump dry-run conditions.  
4. To develop a cost-effective and scalable solution for water management.

---

## 📚 Literature Survey
1. **Towards an Autonomous and Smart Water Tank System**  
   A. Sayyed & M. W. Aziz, *International Journal*, vol. 9, no. 3, 2021.

2. **Cloud-based Water Tank Management and Control System**  
   C. C. Sekhar et al., SmartTechCon 2023, IEEE.

---

## 🔧 Methodology
### ✔ Sensor & Data Collection  
Ultrasonic sensor measures water level by calculating sound wave travel time.

### ✔ Microcontroller Processing  
ESP8266 computes distance and converts it into percentage of tank fill.

### ✔ IoT Communication  
Data is sent via WiFi to **Adafruit IO dashboard**.

### ✔ Automation  
Pump is automatically switched ON/OFF based on water level thresholds.

### ✔ Manual Override  
User can control pump manually using the Adafruit IO app.

---

# 📈 Flow Chart
> *(Add your flowchart image in the repo under `/images/flowchart.png`)*

