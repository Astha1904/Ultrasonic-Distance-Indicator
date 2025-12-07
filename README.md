# Ultrasonic Distance Indicator with Buzzer 🚨  
**An IoT-Based Object Detection and Alert System Using Arduino**

---

## 📌 Project Overview
The **Ultrasonic Distance Indicator with Buzzer** is an IoT-based embedded system designed to detect nearby objects using an **HC-SR04 ultrasonic sensor** and alert users through a **buzzer and LED** when the object comes within a predefined distance range. The system is controlled using an **Arduino Uno** and provides real-time distance monitoring with both **audio and visual feedback**.

---

## 👩‍🎓 Prepared By  
- **IT003 – Astha Ankola**
- **IT022 – Ami Desai**

---

## 🎯 Objectives
- To measure distance using ultrasonic waves  
- To provide audible alert using a buzzer  
- To give visual indication using an LED  
- To understand real-time sensor interfacing with Arduino  
- To develop a low-cost obstacle detection system  

---

## 🔧 Hardware Components
- Arduino Uno  
- Ultrasonic Sensor (HC-SR04)  
- Buzzer  
- LED  
- 220 Ohm Resistor  
- Breadboard  
- Jumper Wires  

---

## 💻 Software Requirements
- Arduino IDE  
- Windows / Linux / macOS  

---

## ⚙️ Working Principle
1. The **HC-SR04 sensor** sends ultrasonic sound waves.
2. These waves reflect back after hitting an object.
3. The **Arduino calculates the distance** using the echo return time.
4. If the distance is less than the defined threshold:
   - ✅ The **buzzer turns ON**
   - ✅ The **LED glows**
5. As the object gets closer, the **buzzer beeps faster**.

---

## 🔌 Circuit Connections
- **Trig Pin → Arduino Digital Pin 9**
- **Echo Pin → Arduino Digital Pin 10**
- **Buzzer → Arduino Digital Pin 11**
- **LED → Arduino Digital Pin 13 via 220Ω resistor**
- **VCC → 5V**
- **GND → Ground**

---

## 📐 Project Structure
- ├── Arduino_Code.ino        
- ├── Circuit_Diagram.jpg       
- ├── Ultrasonic Distance Indicator With Buzzer.pdf 
- └── README.md              

