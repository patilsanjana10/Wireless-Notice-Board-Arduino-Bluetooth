📌 Wireless Notice Board – Arduino + Bluetooth + P10 LED Panel

🔹 Project Overview

A wireless digital notice board that allows sending messages via Bluetooth to an Arduino, which then displays the message on a P10 LED panel.

Eliminates the need for wired notice boards.

Useful for schools, colleges, offices, bus stations, and public places.

🔹 Features

Wireless communication using HC-05 Bluetooth module.

P10 LED panel for bright and clear message display.

User-friendly mobile app for message sending.

Low-cost and easy-to-implement solution.

Portable and can be powered by adapter or battery.

🔹 Hardware Used

Arduino Uno / Mega

P10 LED Display Panel

HC-05 Bluetooth Module

Power Supply (5V)

Jumper Wires

🔹 Software Used

Arduino IDE (for programming)

Mobile Bluetooth Terminal App (to send messages)

🔹 Working Principle

User types a message on the mobile app.

Message is sent via Bluetooth (HC-05).

Arduino receives the message.

Arduino processes the string and displays it on the P10 LED panel.

🔹 Circuit Diagram / Connections

HC-05 → Arduino TX/RX pins

P10 Module → Arduino Digital Pins (with proper library support)

Power → 5V regulated supply

<img width="881" height="366" alt="image" src="https://github.com/user-attachments/assets/40c52fcb-0045-41e6-a01a-e6a047976371" />

🔹 Libraries Used

DMD2 Library (for controlling P10 LED panels)
RBX Matrix

🔹 Applications

School/College Notice Boards

Railway/Bus Station Announcements

Office/Industry Information Display

Event Management

🔹 Future Improvements

Wi-Fi (ESP8266/ESP32) instead of Bluetooth for long range.

Scrolling text and animations.

Voice-controlled input.

Multi-panel extension for larger displays.
