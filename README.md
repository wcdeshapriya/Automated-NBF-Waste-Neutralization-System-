# Low-Cost IoT-Based Automated Neutralization and Safe Disposal System for Neutral Buffered Formalin Waste in Laboratory Environments

---

## 📌 Project Overview
This project is a **low-cost IoT-based automated system** designed for the safe monitoring, neutralization, and disposal of **Neutral Buffered Formalin (NBF) waste** in laboratory environments.

The system reduces human exposure to hazardous chemicals by automating the neutralization process and enabling **real-time remote monitoring using IoT technology**.

---

## 🎯 Objectives
- Design an automated system for safe NBF waste management  
- Monitor chemical conditions in real time using sensors  
- Automate neutralization and disposal process  
- Reduce human exposure to toxic laboratory waste  
- Enable remote monitoring via web interface  
- Improve laboratory safety and efficiency  

---

## ⚙️ System Features
- 📡 Real-time IoT monitoring  
- ⚗️ Automated neutralization process  
- 🌐 Web-based dashboard interface  
- 🚨 Alert system for safety conditions  
- 🔄 Automatic pump/relay control  
- 💰 Low-cost hardware implementation  

---

## 🧰 Hardware Requirements
- ESP8266 WiFi Module  
- pH Sensor (or chemical sensor)  
- Temperature Sensor (DS18B20 or similar)  
- Relay Module  
- Liquid Pump / Valve System  
- Power Supply Unit  
- Connecting Wires & Breadboard  

---

## 💻 Software & Libraries Used

### Arduino Libraries
```cpp
#include <ESP8266WiFi.h>
#include <WiFiClient.h>
#include <ESP8266WebServer.h>
#include <WebSocketsServer.h>
#include <SoftwareSerial.h>

## 🏗️ System Architecture

The system consists of three main modules:

- Sensing Unit

Collects real-time data (pH, temperature, etc.)
Sends data to ESP8266

- Control Unit

Processes sensor data
Controls pump/relay for neutralization

- IoT Monitoring Unit

Sends data to web dashboard
Allows remote monitoring and alerts
