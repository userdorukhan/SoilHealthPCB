# 🌱 SoilHealth – Smart Agriculture PCB Project

**SoilHealth** is a smart environmental monitoring system designed as part of the Hope DeCal at UC Berkeley. This project aims to measure key soil and atmospheric parameters to support precision agriculture, gardening, and sustainability efforts. The custom-designed PCB integrates multiple sensors, solar-powered charging, and wireless data transmission via an ESP32 microcontroller.

---

## 🔧 Features

* **Custom PCB Design** for low-power, compact, and modular sensor integration
* **Solar-Powered System** with a Li-ion battery and charging circuit
* **ESP32 Microcontroller** for sensor interfacing and Wi-Fi communication
* **U.FL Antenna Connector** for extended wireless range
* **Data Logging** to Firebase for real-time remote monitoring

---

## 🌡️ Sensors Used

| Sensor  | Measurement                     | Notes                       |
| ------- | ------------------------------- | --------------------------- |
| SEN0193 | Soil Moisture                   | Capacitive, analog output   |
| DS18B20 | Soil Temperature                | Waterproof, 1-Wire protocol |
| BH1750  | Light Intensity                 | Digital I2C sensor          |
| BME280  | Temperature, Humidity, Pressure | I2C protocol                |

---

## ⚡ Power Management

* **Solar Panel Input**
* **Lithium-Ion Battery** charging via onboard circuit
* **Voltage Regulator** to ensure stable 3.3V supply to ESP32 and sensors

---

## 📡 Connectivity

* **Wi-Fi Transmission** via ESP32
* **Firebase Integration** for remote data storage and visualization

---

## 📐 PCB Highlights

* Designed using KiCad
* Double-layer board optimized for low noise and compact routing
* Separate power domain for analog sensors to reduce interference
* Test points for debugging and voltage verification

---

## 🛠️ Future Improvements

* Add onboard SD card logging for offline operation
* Improve power optimization via deep sleep modes
* Add additional sensors (e.g., CO₂, VOC) for advanced monitoring
