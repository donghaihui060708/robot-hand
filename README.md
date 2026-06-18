<p align="right">

English | <a href="./README\_CN.md">中文</a>

</p>



\# 🤖 Embodied AI Soft Robotic Hand



A tendon-driven silicone robotic hand controlled through ESP32 microcontrollers, a web-based interface, and AI-powered voice commands.



\---



\## 📖 Overview



This project aims to develop a soft robotic hand capable of performing natural finger movements through servo-driven tendon actuation.



The system combines embedded systems, wireless communication, web technologies, and artificial intelligence to create an intuitive human–robot interaction platform.



Users can control the robotic hand through a browser-based dashboard or natural language voice commands interpreted by a large language model (LLM).



\---



\## ✨ Features



\### 🌐 Web Control Interface



\* Individual finger control

\* Real-time hand operation

\* Preset gesture execution

\* Communication status monitoring

\* Modern dark-themed dashboard



\### 🤖 AI Voice Control



\* Speech recognition

\* Natural language command interpretation

\* AI-generated hand actions



Example commands:



\* Open the hand

\* Close the hand

\* Make a fist

\* Point with the index finger

\* Thumbs up



\### 📡 Wireless Communication



\* ESP32-based architecture

\* BLE communication

\* USB Serial communication

\* ESP-NOW data transmission



\---



\## 🏗 System Architecture



```text

Web Interface

&#x20;     │

&#x20;BLE / USB

&#x20;     │

&#x20;     ▼

ESP32 Transmitter

&#x20;     │

&#x20;  ESP-NOW

&#x20;     │

&#x20;     ▼

ESP32 Receiver

&#x20;     │

&#x20;  PCA9685

&#x20;     │

&#x20;Servo Motors

&#x20;     │

Soft Robotic Hand

```



\## 🔧 Hardware



\* Seeed Studio XIAO ESP32S3

\* PCA9685 Servo Driver

\* Servo Motors × 5

\* Tendon-driven Mechanism

\* Silicone Soft Robotic Hand



\---



\## 💻 Software Stack



\### Frontend



\* HTML5

\* CSS3

\* JavaScript



\### Embedded Systems



\* Arduino IDE

\* ESP32

\* ESP-NOW

\* BLE



\### AI Integration



\* DeepSeek API

\* Web Speech API



\---



\## 📂 Project Structure



```text

robot-hand/

│

├── index.html

├── api/

├── README.md

└── README\_CN.md

```



\## 👨‍💻 Author



Haihui Dong



Temasek Polytechnic

Diploma in Electronics



GitHub:

https://github.com/donghaihui060708



\---



\## 📌 Copyright



© 2026 Haihui Dong



This repository is published for educational and portfolio purposes.



All rights reserved.



