# ESP32-CAM Video Streaming Web Server

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Platform](https://img.shields.io/badge/platform-ESP32-orange.svg)
![Arduino](https://img.shields.io/badge/framework-Arduino-00979D.svg)

A simple, lightweight video streaming web server for the **AI-Thinker ESP32-CAM** module. This project creates a standalone web page that streams MJPEG video directly from the ESP32 to your browser.

## 📸 Hardware Compatibility

This code is specifically tested and verified for:

* **Board:** Generic ESP32-CAM (AI-Thinker Model)
* **Camera Module:** Rhynx M21-45 (OV2640 2MP)

> **Note:** This is the version often identified by the "Rhynx M21-45" text printed on the black camera ribbon cable. While designed for the Rhynx M21-45, this code should also work with standard OV2640 camera modules commonly found on AI-Thinker boards.

## ✨ Features

* **Instant Streaming:** MJPEG video stream accessible via web browser.
* **Self-Contained:** HTML and CSS are embedded in the code (no SPIFFS upload required).
* **Simple Interface:** Clean, dark-themed web UI.

## 🛠️ Hardware Required

* **ESP32-CAM Board**
* **FTDI Programmer** (USB-to-TTL) for uploading code
* **5V Power Supply**
* Jumper wires

## 💻 Software Requirements

* **Arduino IDE** (1.8.x or 2.x)
* **ESP32 Board Manager** installed in Arduino IDE

## ⚙️ Setup & Installation

### 1. Clone the Repository
```bash
git clone [https://github.com/YOUR_USERNAME/ESP32-CAM-WebServer.git](https://github.com/YOUR_USERNAME/ESP32-CAM-WebServer.git)