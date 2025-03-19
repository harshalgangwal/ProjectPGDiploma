# 🏙️ Real-Time Crowd Management and Analysis in Metro Premises

![Python 3.8+](https://img.shields.io/badge/Python-3.8%2B-brightgreen.svg)  
![YOLO](https://img.shields.io/badge/YOLO-🔍-red)  
![SAHI](https://img.shields.io/badge/SAHI-📸-orange)  
![Facebook Prophet](https://img.shields.io/badge/Prophet-📈-blue)  
![Computer Vision](https://img.shields.io/badge/Computer%20Vision-🤖-yellow)  
![Deep Learning](https://img.shields.io/badge/Deep%20Learning-🧠-purple)

---

## 📌 **Project Overview**
🚇 **Real-Time Crowd Management and Analysis** is an AI-driven system designed to **detect and predict** crowd density in metro premises. The project integrates **Computer Vision and Time-Series Forecasting** to assist **metro authorities in managing congestion and optimizing train schedules**.  

### 🔹 **Key Features:**
✅ **Real-time crowd detection** using YOLO+SAHI  
✅ **Time-series forecasting** with Facebook Prophet  
✅ **Heatmaps & analytics** for metro stations  
✅ **Overcrowding alerts & notifications**  

---

## 🚀 **Project Workflow**
<img src="workflow_diagram.png" alt="Workflow Diagram" width="auto"/>

---

## 🛠️ **Technology Stack**
| **Component**          | **Technology Used**   |
|------------------------|----------------------|
| Programming Language  | Python 3.8+          |
| Object Detection      | YOLOv8 + SAHI        |
| Forecasting Model     | Facebook Prophet     |
| Data Processing      | OpenCV, NumPy        |
| Database             | SQLite, Pandas       |
| Web Framework        | Streamlit            |

---

## 📊 **System Architecture**
<img src="system_architecture.png" alt="System Architecture" width="auto"/>

---

## 🔍 **Project Breakdown**

### 1️⃣ **Crowd Detection Using YOLO + SAHI**
```python
from ultralytics import YOLO
