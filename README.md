# 🚀 YOLO26 Real-Time Engineering Dashboard

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![YOLO26](https://img.shields.io/badge/Model-YOLO26--Small-orange.svg)
![Gradio](https://img.shields.io/badge/UI-Gradio-red.svg)

A high-performance, web-based object detection hub utilizing the state-of-the-art **YOLO26** architecture. This project demonstrates real-time, NMS-free inference deployed via a hybrid cloud-client architecture.

## ✨ Key Features
* **NMS-Free Inference:** Utilizes one-to-one matching to eliminate post-processing bottlenecks, achieving rapid FPS on T4 GPUs.
* **JavaScript-Python Bridge:** Custom-built local webcam streaming that bypasses cloud-hosted hardware limitations.
* **Unified UI:** A Gradio-powered dashboard supporting static images, recorded video files (H.264 encoded), and live streams.
* **Dynamic Tuning:** Real-time confidence threshold adjustment to handle environmental noise during live testing.

## 🛠️ Installation & Usage
This project was designed to run seamlessly in Google Colab. 

1. Clone this repository:
   ```bash
   git clone [https://github.com/sudarshanptl644/YOLO26-Real-Time-Object-Detection.git](https://github.com/sudarshanptl644/YOLO26-Real-Time-Object-Detection.git)
