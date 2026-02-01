# Industrial & Automotive Telematics Gateway

This repository showcases a non-confidential example of an industrial telematics gateway architecture used in large-scale fleet management and IoT monitoring systems.

The design reflects real production patterns applied in automotive and industrial deployments with thousands of active devices in the field.

---

## 🔧 Project Overview

The system acts as an embedded gateway responsible for:

- Vehicle data acquisition via CAN Bus (J1939 compatible)
- Cellular connectivity using LTE-M / NB-IoT modems
- GNSS positioning and time synchronization
- Remote firmware updates (FOTA)
- Low-power operation optimized for automotive battery environments

---

## 👨‍💻 My Role

**End-to-End Embedded System Development:**

- Hardware architecture and PCB design
- Firmware architecture and driver development
- Communication stack integration (CAN, LTE, GNSS)
- Bootloader and OTA update flow design
- Production testing strategy (FCT)

---

## 🛠 Technical Stack

**Firmware:**
- Language: Embedded C (Bare-Metal)
- Architecture: Layered firmware design (HAL + Drivers + Application)
- Bootloader + OTA ready structure

**Hardware & Interfaces:**
- CAN Bus (Vehicle Diagnostics / Telematics)
- UART, SPI, I2C
- LTE-M / NB-IoT modem interface
- GNSS module integration

**Power Management:**
- Automotive transient protection
- Advanced low-power modes
- Sleep scheduling and battery preservation strategies

---

## 🧱 Firmware Architecture Overview
Application Layer ↓ Communication Manager (CAN / LTE / GNSS) ↓ Driver Abstraction Layer ↓ Hardware Abstraction Layer (HAL)

This structure enables scalability, maintainability and production-grade reliability.

---

## 📦 Production-Oriented Design Considerations

- Non-blocking communication drivers
- Watchdog supervision
- Fault recovery mechanisms
- Robust modem reconnection handling
- OTA-safe firmware partitioning strategy

---

## 📸 Hardware Showcase

Industrial-grade automotive PCB design with EMC-aware layout and multi-layer routing:

![Preview](media/ST1_1.png)
![Preview](media/ST1_2.png)
![Preview](media/ST1_3.png)
![Preview](media/ST1_4.jpeg)
![Preview](media/ST1_5.jpeg)
![Preview](media/ST1_6.jpeg)

---

## 📌 Note

This repository contains only public, non-confidential examples.  
Commercial firmware and proprietary schematics are protected under NDA and are not included.

---

[⬅ Back to Main Portfolio](https://github.com/aleromio)

