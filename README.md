# 🛠️ Ogre OBD Dash

**A custom iOS SwiftUI app for Force Gurkha diagnostics, telemetry, and off-road monitoring using ELM327 Bluetooth OBD-II adapter.**

---

## 🚙 Overview

**Ogre OBD Dash** is a tailor-made iOS app built for vehicle enthusiasts, especially Force Gurkha owners, to monitor, diagnose, and log real-time vehicle data directly from the ECU. Built using SwiftUI, the app connects to standard ELM327 Bluetooth OBD-II adapters and provides a modern, dashboard-friendly interface.

---

## ✨ Features

- ✅ **Read Diagnostic Trouble Codes (DTCs)**
- 🧹 **Clear/Erase DTCs**
- 📈 **Live Telemetry Monitoring**  
  - RPM, speed, coolant temperature, engine load, and more
- 🧭 **Off-Road Inclinometer**  
  - G-force monitoring with real-time pitch, roll, and lateral angles
- 🧾 **Trip Logging & Exporting**  
  - Save and export diagnostic + movement data
- 🧪 **Mock Mode for Development**  
  - Test the app without being connected to the vehicle
- 📱 **SwiftUI Native**  
  - Optimized for iPhone and iPad (perfect for dashboard mounts)

---

## 📸 Screenshots (Coming Soon)

> Add screenshots or short videos of the app in action here once the UI is implemented.

---

## 📦 Tech Stack

- `SwiftUI` – UI framework
- `CoreBluetooth` – ELM327 Bluetooth communication
- `CoreMotion` – For accelerometer & gyroscope-based inclinometer
- `Combine` – Reactive programming for real-time data streams

---

## 🚧 Development Notes

- Support for ELM327-compatible adapters only
- Currently focused on ISO 9141 / CAN protocol vehicles
- Mocked telemetry mode available for local development

---

## 📍 Future Plans

- Dark mode + off-road night UI theme
- Real-time alert system (e.g., engine overheating, sensor anomalies)
- GPS route tracking and export
- Apple Watch support for remote engine health glance

---

## 👨‍🔧 Author

**Aqeel Ashraf**  
_2025 BS6.2 Force Gurkha 3D Green owner • Code tinkerer • Off-road enthusiast_

---

## 📄 License

MIT License. Feel free to fork, modify, and ride with it.

---

> _“Built for Ogre. Powered by code. Tested on trails.”_
