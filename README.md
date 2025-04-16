# 🤖 Hawkeye32

**Hawkeye32** is a manually controlled, self-balancing surveillance robot built using ESP32 boards. It streams real-time video via an ESP32-CAM and uses a web-based control panel for remote navigation. Designed for indoor monitoring and patrol applications, Hawkeye32 combines live video, motion control, and self-balancing capabilities in one compact bot.

---

## 🌟 Features

- **Self-Balancing Mechanism**  
  Uses PID control with gyroscope and accelerometer feedback to stay upright on two wheels.

- **Real-Time Video Streaming**  
  ESP32-CAM streams live video feed over Wi-Fi to a web interface.

- **Manual Remote Control**  
  Navigate the bot using on-screen directional buttons or keyboard arrow keys.

- **Web Interface (Flask)**  
  Simple and responsive control panel for real-time monitoring and movement control.

---

## 🛠️ Technologies Used

### Hardware
- **ESP32-CAM** – For Wi-Fi video streaming  
- **ESP32 Dev Board** – For balance + movement logic  
- **MPU6050** – Gyroscope + accelerometer for balance feedback  
- **Stepper Motors + Driver** – Mobility  
### Software
- **Arduino IDE** – Microcontroller programming  
- **Python 3** – Backend logic  
- **Flask** – Web framework for UI  
- **OpenCV** – For object detection  
- **HTML/CSS/JS** – Frontend controls  
- **PID Algorithm** – Real-time balance control

---
