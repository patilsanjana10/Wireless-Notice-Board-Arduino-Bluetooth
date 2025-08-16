# 📢 Wireless Notice Board using Arduino & Bluetooth  

> From smartphone to display in seconds — an Arduino-powered wireless notice board for real-time updates.  

[![Arduino](https://img.shields.io/badge/Made%20with-Arduino-blue?logo=arduino)](https://www.arduino.cc/)  
[![Bluetooth](https://img.shields.io/badge/Module-HC05-lightblue?logo=bluetooth)](https://www.electronicwings.com/nodemcu/hc-05-bluetooth-module)  

---

## 🔎 Project Overview  
The **Wireless Notice Board** replaces traditional paper-based notice boards with a **modern, eco-friendly solution**.  
It uses an **Arduino Uno + Bluetooth HC-05** to receive text messages sent from a smartphone and display them on a **16x2 LCD (I2C)** or a **P10 LED panel** in **real-time**.  

This makes it suitable for **schools, colleges, offices, hospitals, and public spaces** where announcements must be updated quickly.  

---

## 📌 Project Highlights  

- **Objective**: To design a **Wireless Notice Board** that displays messages sent wirelessly via a smartphone.  
- **Technology Used**: Arduino Uno, Bluetooth HC-05, LCD (16x2 with I2C) / P10 LED panel.  
- **Working Principle**:  
  1. Message typed on smartphone (via Serial Bluetooth Terminal app).  
  2. Sent to HC-05 Bluetooth module.  
  3. Arduino receives & processes data.  
  4. Message displayed on LCD / LED board in real-time.  
- **Hardware Implemented**: Arduino Uno, HC-05 Bluetooth module, I2C LCD, regulated power supply, breadboard wiring.  
- **Software Used**: Arduino IDE (for coding), Android app (Bluetooth Terminal).  
- **Output**: Successfully displayed messages like *“JAI SHREE RAM”* on the LCD.  
- **Applications**: Schools, colleges, offices, hospitals, shopping malls, public spaces for **instant communication**.  
- **Advantages**: Real-time updates, eco-friendly (no paper), cost-effective, compact.  
- **Limitations**: Limited Bluetooth range (~10m), LCD text capacity, basic security.  
- **Future Scope**: Upgrade with Wi-Fi/IoT for longer range, scrolling messages, mobile app integration.


---
## 🔌 Circuit Connections  

The circuit connects the **Arduino Uno**, **HC-05 Bluetooth Module**, and **16x2 LCD with I2C** as follows:  

- **HC-05 Bluetooth Module**  
  - VCC → 5V  
  - GND → GND  
  - TXD → Pin 0 (RX) of Arduino  
  - RXD → Pin 1 (TX) of Arduino  

- **I2C LCD (16x2 Display)**  
  - VCC → 5V  
  - GND → GND  
  - SDA → A4  
  - SCL → A5  

- **Power Supply**: Arduino powered via USB / 5V adapter.    

---

## ⚙️ Features  
✔️ Wireless message updates via smartphone  
✔️ Supports LCD (16x2 with I2C) and P10 LED display  
✔️ Easy to use with Android app (Serial Bluetooth Terminal)  
✔️ Eco-friendly alternative to paper-based notices  
✔️ Low-cost and portable system  

---

## 📸 Prototype Output  

Below is the working prototype of the Wireless Notice Board.  
The LCD displays the message **"JAI SHREE RAM"** sent wirelessly from a smartphone via Bluetooth HC-05.  

![Prototype Output]("C:\Users\patil\OneDrive\Desktop\Diag2.jpg".jpg)  

---

## 📜 Applications  

- **Educational Institutions** 🏫 – announcements, exam schedules, notices.  
- **Corporate Offices** 🏢 – meeting schedules, alerts, greetings.  
- **Public Spaces** 🚉 – bus/train updates, emergency alerts.  
- **Hospitals** 🏥 – doctor availability, health tips, queue info.  
- **Shopping Malls / Retail** 🛍️ – offers, ads, promotions.  
- **Smart Homes** 🏠 – reminders, alerts, IoT integration.  

---

## 🔮 Future Improvements  

- Add Wi-Fi (ESP8266/ESP32) for longer range than Bluetooth.  
- Support for scrolling text on P10 LED panel.  
- Android app with custom UI (instead of Serial Bluetooth Terminal).  
- Cloud/IoT integration for smart campus & industry.  


---

