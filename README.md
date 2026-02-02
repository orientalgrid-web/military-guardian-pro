# MILITARY GUARDIAN PRO (Tactical Interface)
### Counter-Terrorism & Perimeter Defense System

This repository contains the core front-end tactical interface for the **Military Guardian Pro** system. Designed for deployment on high-durability hardware (Proto Douglas / Orient Neo 7), this tool provides real-time situational awareness for troop movements and road-side threat detection.

## 🛡️ Core Operational Protocols

### 1. Satellite Perimeter Scan (50m Delta)
The system is programmed to perform an active geospatial scan of the terrain **50 meters to the left and right** of the current coordinate. 
* **Objective:** Identify anomalies, thermal signatures, or irregular gatherings in the "blind corners" of rural roads.
* **Frequency:** Optimized for a **20-30 minute pulse** to balance battery life with tactical safety.

### 2. Stealth & Surveillance Loop
* **Background Operation:** The "Moving Pulse" scan runs as a persistent background process.
* **Silent Alert Logic:** Implements non-visual, non-auditory alert triggers (Volume Button x3 / Shake Detection) to notify Command Centers without alerting hostile actors.
* **Zero-Reporting Policy:** This public repository is a **Source Code Template**. All data transmission endpoints (IPs/Ports) must be configured by Military Command to point to internal, secure servers.

## 🚀 Deployment Instructions (Military IT)

1.  **Self-Hosting:** Download the `index.html` and host on an air-gapped internal server or a secure military intranet.
2.  **Hardware Integration:** Ensure the `index.html` is set as the default "Home" or "Kiosk" view on the **Proto Douglas** and **Orient Neo 7** devices.
3.  **GPS Calibration:** The system utilizes browser-based Geolocation. Ensure the device has "High Accuracy" GPS enabled for precise 50m road-side scanning.

## 📋 Technical Specs
* **Format:** Single-file HTML5/CSS3/JS (Zero dependencies for security).
* **UI:** Military Green / Night-Vision Stealth Mode.
* **Compatibility:** Optimized for the 2026 Proto-Series mobile chipsets.

---
**NOTICE:** This software is for authorized military personnel only. Unauthorized distribution of the tactical scanning logic is prohibited.
