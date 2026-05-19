# 🎓 Smart Student Portal | Attendance System

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Google Apps Script](https://img.shields.io/badge/Google_Apps_Script-4285F4?style=for-the-badge&logo=google&logoColor=white)
![Google Sheets](https://img.shields.io/badge/Google_Sheets-34A853?style=for-the-badge&logo=google-sheets&logoColor=white)

Welcome to the **Smart Student Portal**, a serverless, zero-maintenance web application designed to modernize university classroom attendance. This system eliminates paper rosters, prevents proxy check-ins, and provides real-time data to students.

---

## ✨ System Capabilities

This portal is designed to handle fast, high-volume check-ins during the first minutes of a lecture, ensuring only students physically present in the room get credit.

* **📍 GPS Geofencing Security:** Uses the HTML5 Geolocation API and the Haversine formula to calculate the student's exact distance from the classroom. If they are more than **30 meters** away, the system blocks the submission. Proxy attendance from dorm rooms is physically impossible.
* **⏰ Automated Time-Locks:** The portal automatically locks and unlocks based on a hardcoded weekly lecture schedule. It will not accept attendance submissions outside of active class hours.
* **📊 Real-Time Student Dashboard:** Students can instantly verify their attendance by entering their roll number. The portal calculates their exact attendance percentage, counts their total present days, and displays a scrollable history of every lecture they have attended.
* **🚦 Concurrent Traffic Handling:** Engineered with backend lock-services to handle hundreds of students clicking "Submit" at the exact same second without crashing or overwriting database records.

## 🛠️ Core Architecture
* **📱 Native App Experience:** Features a clean, glassmorphism-inspired UI with modern typography, smooth loading animations, and dynamic error messaging.
* **💬 Integrated Peer Support:** Features dynamic "Click-to-Chat" WhatsApp integration. One tap opens a pre-written WhatsApp message directed straight to the Class Representative (CR) for discrepancy resolutions.
* **☁️ 100% Free & Serverless:** Built entirely on GitHub Pages for the frontend and Google Apps Script + Google Sheets for the backend, meaning it runs 24/7 with zero hosting costs.

---

## ©️ Copyright & Management

**Developed by:** Souravh Choursiya    
**Managed by:** Souravh Choursiya  

&copy; 2026 Souravh Choursiya. All rights reserved.
