# Geo-Fence Guard 🚧🐾

An IoT-based real-time virtual boundary alert system to monitor the movement of pets or children and notify their guardians if they leave a predefined safe zone.

## 📍 Overview

This project uses a NodeMCU ESP8266 and a GPS module (NEO-6M) to track real-time location and determine if the device is within a virtual fence. If the wearer moves beyond the safe zone, the system:

- Activates a buzzer or LED
- Sends a mobile push notification (via Blynk)
- (Optional) Sends an SMS/email alert using IFTTT

## 🎯 Objectives

- Ensure safety of pets or children outdoors
- Alert guardians immediately on boundary breach
- Demonstrate real-time location processing using GPS + cloud

## 🛠️ Hardware Used

| Component              | Quantity | Description                          |
|-----------------------|----------|--------------------------------------|
| NodeMCU ESP8266       | 1        | Wi-Fi enabled microcontroller        |
| NEO-6M GPS Module      | 1        | Real-time location tracking          |
| Buzzer / LED          | 1        | Alert output                         |
| Breadboard & Wires    | 1 set    | For circuit connections              |
| Power Bank            | 1        | Portable power supply                |
| Optional: OLED Screen | 1        | Display live coordinates             |

## ☁️ Cloud Services

- **Blynk** – Push notifications & map widget
- **IFTTT** – (Optional) SMS or email alerts
- **ThingSpeak** – (Optional) Data logging & visualization

## 📁 Folder Structure

