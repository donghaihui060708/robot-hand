<p align="right">

<a href="./README.md">English</a> | 中文

</p>



\# 🤖 Embodied AI 机器人硅胶手



一个基于 ESP32、网页控制界面以及 AI 语音指令的线驱动硅胶机器人手系统。



\---



\## 📖 项目简介



本项目旨在设计并实现一套能够模拟人手运动的软体机器人手。



系统采用舵机拉绳驱动方式控制五根手指运动，并结合嵌入式控制、无线通信、网页交互以及人工智能技术，实现更加自然和直观的人机交互体验。



用户可以通过网页控制界面或自然语言语音指令控制机器人手完成不同动作。



\---



\## ✨ 主要功能



\### 🌐 网页控制



\* 五指独立控制

\* 实时动作控制

\* 预设手势执行

\* 通信状态显示

\* 科技风深色界面



\### 🤖 AI 语音控制



\* 语音识别

\* 自然语言理解

\* AI 自动生成手部动作



示例指令：



\* 张开手掌

\* 握拳

\* 食指指向前方

\* 竖起大拇指



\### 📡 无线通信



\* ESP32 控制架构

\* BLE 蓝牙通信

\* USB 串口通信

\* ESP-NOW 数据传输



\---



\## 🏗 系统架构



```text

网页控制界面

&#x20;     │

&#x20;BLE / USB

&#x20;     │

&#x20;     ▼

ESP32 发送端

&#x20;     │

&#x20;  ESP-NOW

&#x20;     │

&#x20;     ▼

ESP32 接收端

&#x20;     │

&#x20;  PCA9685

&#x20;     │

&#x20;   舵机驱动

&#x20;     │

硅胶机器人手

```



\## 🔧 硬件组成



\* Seeed Studio XIAO ESP32S3

\* PCA9685 舵机驱动板

\* 5 个舵机

\* 拉绳驱动机构

\* 硅胶机器人手



\---



\## 💻 软件技术栈



\### 前端开发



\* HTML5

\* CSS3

\* JavaScript



\### 嵌入式开发



\* Arduino IDE

\* ESP32

\* ESP-NOW

\* BLE



\### AI 功能



\* DeepSeek API

\* Web Speech API



\---



\## 📂 项目结构



```text

robot-hand/

│

├── index.html

├── api/

├── README.md

└── README\_CN.md

```



\---



\## 👨‍💻 作者



Dong Haihui



Temasek Polytechnic

Diploma in Electronics



GitHub：

https://github.com/donghaihui060708



\---



\## 📌 版权声明



© 2026 Dong Haihui



本项目仅用于学习交流及个人作品展示用途。



保留所有权利。



