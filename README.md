# 🤖 SPY-DER: Speech & Web Controlled Surveillance Spider Robot

## 🧠 Overview:
This project aims to build a Surveillance Robot which can be controlled via **Voice Command** and also **Wirelessly** via a web interface.  
It uses a **Spider Robot Chassis**, integrated with **Raspberry Pi** and **Arduino UNO**.  
Live video feed is streamed from the robot to the user over the browser.

---

## 🔧 Components Used:

- Raspberry Pi
- Arduino UNO
- USB Webcam
- Spider Robot Chassis
- 8 Servo Motors
- L293D Motor Driver
- Jumper Wires
- Breadboard

---

## ⚙️ Technologies Used:

- Python 3
- Flask (for web control)
- Google Speech Recognition API
- OpenCV (for video streaming)
- Arduino C++ (for motor movement)

---

## 🖥️ Control Interface:

- Web UI allows manual control of robot movements
- Voice input allows speech-based direction control
- Raspberry Pi acts as a server and connects to the Arduino for motor commands

---

## 📝 How It Works:

1. The user accesses the robot via a web browser or gives voice commands.
2. Raspberry Pi receives input, interprets it, and sends commands to Arduino UNO.
3. Arduino controls the 8-leg movement (servos) accordingly.
4. Raspberry Pi streams live video using the webcam and OpenCV.

---
