# 🚗 WiFi Controlled Smart Robot with LiDAR & ESP32-CAM

## 📌 Overview
This project presents a **WiFi-controlled intelligent robotic system** built using the **ESP32 microcontroller**, integrating **LiDAR sensing, live camera streaming, and wireless control** for real-time navigation and monitoring.

The robot can operate in both **Manual Mode** and **Auto Navigation Mode**, enabling remote movement control, obstacle detection, collision prevention, and live video monitoring through a web-based dashboard.

The system combines:
- 📡 Wireless communication
- 🤖 Embedded motor control
- 📷 Real-time camera streaming
- 📏 LiDAR-based obstacle detection
- 🧭 IMU-based motion sensing

making it suitable for surveillance, inspection, exploration, and robotics research applications.

---

# ❗ Problem Statement

Traditional robotic systems often:
- Lack real-time obstacle detection
- Depend on wired or short-range control
- Have limited monitoring capabilities
- Struggle in dynamic environments

There is a need for a **low-cost, intelligent, and remotely accessible robotic platform** capable of:
- Real-time wireless control
- Obstacle avoidance
- Live monitoring
- Reliable navigation

---

# 🎯 Project Objectives

- Develop a WiFi-controlled robotic system using ESP32
- Implement real-time obstacle detection using LiDAR
- Enable live video streaming using ESP32-CAM
- Provide both manual and autonomous driving modes
- Implement safe navigation and collision prevention
- Create a scalable embedded robotics platform

---

# 🚀 Key Features

- ✅ WiFi-based remote control
- ✅ Manual & Auto navigation modes
- ✅ LiDAR-based obstacle detection
- ✅ Live video streaming (ESP32-CAM)
- ✅ MPU6050 motion sensing
- ✅ PWM motor speed control
- ✅ WebSocket-based dashboard communication
- ✅ Real-time telemetry monitoring
- ✅ Collision prevention system
- ✅ SD card image storage & upload support

---

# 🧠 System Architecture

## 🔧 Main Components

- **ESP32 NodeMCU-32S** – Main controller & WiFi communication
- **L298N Motor Driver** – DC motor control
- **TF Mini / TF-Luna LiDAR** – Distance measurement
- **ESP32-CAM** – Live video streaming & image capture
- **MPU6050** – Motion & orientation sensing
- **Web Dashboard** – Robot control & telemetry visualization

---

# ⚙️ Working Principle

1. The ESP32 creates a WiFi Access Point and hosts a WebSocket server.
2. The dashboard sends movement commands:
   - Throttle
   - Steering angle
   - Mode selection
3. The ESP32 processes commands and controls motors using PWM.
4. LiDAR continuously scans for nearby obstacles.
5. In AUTO mode:
   - Robot moves forward
   - Stops if obstacle detected
   - Rotates until path becomes clear
6. ESP32-CAM streams live video over WiFi.
7. MPU6050 provides acceleration & gyroscope telemetry.
8. Telemetry data is sent back to dashboard in real time.

---

# 🔄 Workflow

User Input → WiFi Communication → ESP32 Processing → Motor Control → Robot Movement  
                                                     ↓  
                                             LiDAR Sensing → Obstacle Detection  
                                                     ↓  
                                         ESP32-CAM → Live Video Streaming  

---

# 🛠️ Technologies Used

## 💻 Software

- Arduino IDE / PlatformIO
- C++
- Embedded Systems Programming

---

## 📚 Libraries Used

- WiFi.h
- ESPAsyncWebServer.h
- AsyncTCP.h
- ArduinoJson.h
- Wire.h
- Adafruit_MPU6050.h
- Adafruit_Sensor.h
- esp_camera.h
- HTTPClient.h
- WebServer.h
- SD_MMC.h

---

## 📖 Concepts

- Embedded Systems
- Robotics
- Wireless Communication
- Sensor Integration
- Autonomous Navigation
- Computer Vision
- IoT Systems
- PWM Motor Control

---

# 📋 Requirements

## 💻 Software Requirements

- Arduino IDE / PlatformIO
- ESP32 Board Package
- Python 3.x (optional for server-side image receiving)

---

## 🔧 Hardware Requirements

- ESP32 NodeMCU-32S
- ESP32-CAM (AI Thinker)
- L298N Motor Driver
- TF Mini / TF-Luna LiDAR
- MPU6050 Sensor
- DC Motors & Robot Chassis
- Battery (7V–12V)
- Buck Converter (LM2596)
- MicroSD Card (optional)

---

## ⚙️ System Requirements

- Laptop / PC
- Stable WiFi Connection
- USB-to-Serial Programmer
- Good 5V power supply

---

# 🔌 Hardware Connections

## 📍 Motor Driver (L298N)

| L298N | ESP32 |
|------|------|
| IN1 | GPIO 25 |
| IN2 | GPIO 26 |
| IN3 | GPIO 27 |
| IN4 | GPIO 14 |
| ENA | GPIO 32 |
| ENB | GPIO 33 |

---

## 📍 LiDAR (TF Mini)

| LiDAR | ESP32 |
|------|------|
| TX | GPIO 16 |
| RX | GPIO 17 |
| VCC | 5V |
| GND | GND |

---

## 📍 MPU6050

| MPU6050 | ESP32 |
|---------|------|
| SDA | GPIO 21 |
| SCL | GPIO 22 |
| VCC | 3.3V |
| GND | GND |

---

# 📊 Output

- Real-time robot movement
- Obstacle distance measurement
- Live video stream
- Motion telemetry
- Collision alerts
- Autonomous navigation behavior

---

# 📱 Applications

- Surveillance robots
- Inspection robots
- Autonomous navigation research
- Industrial monitoring
- Security systems
- Educational robotics
- Smart IoT robotics

---

# ✅ Advantages

- Low-cost implementation
- Wireless remote operation
- Real-time obstacle detection
- Autonomous movement capability
- Modular and scalable design
- Live monitoring support
- Easy integration with IoT systems

---

# 🔮 Future Improvements

- AI-based object detection
- SLAM mapping integration
- Voice control support
- Mobile app dashboard
- GPS navigation
- Cloud telemetry logging
- Swarm robotics support
- ROS integration

---

# 🏁 Conclusion

This project demonstrates the development of a **smart WiFi-controlled robotic platform** integrating LiDAR sensing, live video streaming, and embedded control systems.

The robot successfully performs:
- Remote wireless control
- Obstacle detection
- Autonomous navigation
- Live monitoring
- Real-time telemetry transmission

The system provides a strong foundation for future robotics, IoT, and autonomous navigation applications.

---

# 📷 Project Features Preview

- 🚗 Smart Robot Navigation
- 📡 WiFi Dashboard Control
- 📏 LiDAR Distance Monitoring
- 📷 ESP32-CAM Live Streaming
- 🧭 MPU6050 Motion Tracking

---

# 👨‍💻 Author

Developed as an embedded robotics and automation project using ESP32 technologies.
