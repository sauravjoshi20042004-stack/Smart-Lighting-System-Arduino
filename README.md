# Smart Lighting System Using Arduino and LDR Sensor

## 📌 Project Overview

The Smart Lighting System is an Arduino-based embedded system project designed to automatically control lighting according to the surrounding light intensity.

The system uses an LDR (Light Dependent Resistor) sensor to detect the amount of light available in the environment. When the surrounding light level becomes low, the Arduino automatically turns ON the LED. When sufficient light is available, the LED remains OFF.

This project demonstrates the basic concepts of Embedded Systems, sensor interfacing, and automation.

---

## 🎯 Objectives

- To understand the fundamentals of embedded systems.
- To learn Arduino programming and hardware interfacing.
- To interface sensors with a microcontroller.
- To design an automatic lighting control system.
- To understand real-world applications of IoT-based smart devices.

---

## 🛠️ Components Used

- Arduino UNO
- LDR (Light Dependent Resistor) Sensor
- LED
- 220Ω Resistor
- 10kΩ Resistor
- Breadboard
- Jumper Wires
- USB Cable

---

## 💻 Software Used

- Arduino IDE
- Tinkercad Circuits (Simulation)
- Embedded C/C++ Programming

---

## ⚙️ Working Principle

The LDR sensor detects the intensity of surrounding light and sends an analog signal to the Arduino UNO.

The Arduino processes this input value and compares it with a predefined threshold value.

- If the light intensity is low, Arduino turns ON the LED.
- If the light intensity is high, Arduino keeps the LED OFF.

The system continuously monitors the light condition and automatically controls the LED.

---

## 🔌 Circuit Connection

- LDR output pin connected to Arduino Analog Pin A0.
- LED positive pin connected to Arduino Digital Pin 13.
- LED negative pin connected to GND through a resistor.
- Arduino provides power supply to the circuit.

---

## 📂 Project Files
---

## 🚀 Applications

This smart lighting system can be used in:

- Automatic street lighting
- Smart home lighting systems
- Energy saving lighting solutions
- Garden lighting automation
- Industrial lighting control

---

## 🔮 Future Improvements

The project can be enhanced by:

- Adding ESP32 for IoT connectivity.
- Controlling lights through a mobile application.
- Cloud-based monitoring.
- Adding multiple sensors for advanced automation.

---

## 👨‍💻 Author

**Saurav Joshi**  
B.Tech (Electronics and Communication Engineering)  
Bipin Tripathi Kumaon Institute of Technology, Dwarahat

---

## 📜 Conclusion

This project provides practical knowledge of embedded systems, Arduino programming, and sensor-based automation. It demonstrates how microcontrollers can be used to develop smart and efficient electronic systems.
