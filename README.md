# ESP32 GPS Interface Firmware (ESP-IDF | NEO-6M)

## 📌 Overview
ESP-IDF–based firmware for interfacing an **ESP32** with a **NEO-6M GPS module** using **UART**.  
The firmware reads and processes **NMEA sentences** within a **FreeRTOS task** and has been validated on physical hardware.

## 🛠 Technical Specifications
- **MCU:** ESP32  
- **SDK:** ESP-IDF (v4.x / v5.x)  
- **GPS Module:** u-blox NEO-6M  
- **Interface:** UART  
- **Baud Rate:** 9600 bps (default)  
- **RTOS:** FreeRTOS  

## ⚙️ Functionality
- UART driver initialization using ESP-IDF  
- Continuous GPS data reception  
- NMEA sentence handling (GGA, RMC, etc.)  
- Task-based processing with non-blocking I/O  

## ✅ Hardware Validation
- Tested with **ESP32 + NEO-6M** under real hardware conditions  

## 🚀 Applications
- GPS-enabled embedded systems  
- IoT location tracking  
- ESP-IDF UART/GPS reference design  
