<p align="center">
  <img src="assets/pathguard-banner.png" width="100%" alt="PathGuard Banner">
</p>

<h1 align="center">🛡️ PathGuard</h1>

<h3 align="center">
IoT-Based Soldier Detection & Tracking System
</h3>

<p align="center">

<img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react"/>

<img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs"/>

<img src="https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express"/>

<img src="https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge"/>

<img src="https://img.shields.io/badge/GPS-0078D4?style=for-the-badge"/>

<img src="https://img.shields.io/badge/LoRa-00599C?style=for-the-badge"/>

</p>

---

## 📖 Overview

PathGuard is an IoT-based defense monitoring system designed to provide real-time soldier location tracking, secure communication, and battlefield awareness using ESP32, GPS, LoRa, React, and Node.js. 

PathGuard is an innovative GPS-based tracking system designed for defense and military operations.
The primary goal of this project is to track the real-time location of soldiers on the battlefield, ensuring better coordination, safety, and rapid response in critical missions.

This system bridges the gap between field soldiers and command centers by providing accurate, real-time location data that can save lives during high-risk operations.

---

## ✨ Features
- 🚗 Real-time **GPS location tracking**
- 🗺️ Interactive **map visualization** (frontend)
- 🔒 **CyberWall security module** for detecting suspicious traffic/logs
- 📡 **Arduino hardware integration** (ESP32 + LoRa + GPS)
- 🔗 **Backend APIs** for communication between devices and dashboard
- 🧩 Modular folder structure (easy to maintain & extend)

---

## 📂 Project Structure
PathGuard/
├─ frontend/ → React (Vite) based UI dashboard
├─ backend/ → Node.js/Express REST API server
├─ gps-tracker/ → GPS tracking service (Node.js)
├─ arduino_sketches/ → Arduino (.ino) codes for ESP32 + LoRa + GPS
├─ .gitignore
└─ README.md



---

## ⚙️ Setup & Run Instructions

### 🔸 1. Frontend (React/Vite)
```bash
cd frontend
npm install
npm run dev

🔸 2. Backend (Node/Express)
cd backend
npm install
npm start


🔸 3. GPS Tracker Service

cd gps-tracker
npm install
node server.js

🔸 4. Arduino Sketches
Open arduino_sketches/*.ino files in Arduino IDE
Select board & port → Upload

🛡️ CyberWall Module

The CyberWall module is designed to:
Collect logs and network traffic data
Detect anomalies or attack patterns
Provide alerts on the dashboard
Initial testing can be done using dummy traffic generators and manual JSON log submissions (via Postman).

A Project Dedicated to Soldiers

“Not all heroes wear capes, some wear uniforms. PathGuard ensures they return home safe.”
