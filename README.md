# 🚀 BuildScan Rover – AI-Based Autonomous Robot for Indoor Structural Health Inspection

<div align="center">

![AI](https://img.shields.io/badge/AI-YOLO26n--seg-blue)
![IoT](https://img.shields.io/badge/IoT-ESP32CAM-green)
![Python](https://img.shields.io/badge/Python-3.11-yellow)
![PyTorch](https://img.shields.io/badge/PyTorch-DeepLearning-red)
![Arduino](https://img.shields.io/badge/Arduino-Uno-teal)
![Streamlit](https://img.shields.io/badge/Streamlit-Dashboard-orange)
![Status](https://img.shields.io/badge/Status-Completed-success)

### Intelligent AI + IoT + Robotics based system for real-time structural crack detection and monitoring

</div>

---

## 📌 Project Overview

BuildScan Rover is an AI-powered autonomous and Bluetooth-controlled robotic platform designed for **indoor structural health inspection** and **real-time crack detection**. The project combines **Artificial Intelligence, Robotics, IoT, Computer Vision, and Embedded Systems** into a single smart inspection platform.

The system uses an **ESP32-CAM** for live video streaming, **Arduino Uno** for hardware control, and a lightweight **YOLO26n-seg deep learning model** for real-time crack segmentation and analysis. A **Streamlit dashboard** provides live monitoring, crack measurements, severity estimation, repair suggestions, and automatic PDF report generation.

---

## ✨ Key Features

✅ Autonomous obstacle avoidance mode

✅ Manual Bluetooth control using mobile app

✅ Real-time ESP32-CAM video streaming

✅ AI-based crack detection using YOLO26n-seg

✅ Crack segmentation and localization

✅ Crack severity analysis

✅ Crack width and size estimation

✅ Repair recommendation generation

✅ Streamlit dashboard monitoring

✅ Automatic PDF report generation

✅ GPU accelerated training (CUDA + cuDNN)

---

# 🎥 System Workflow

```text
Structural Surface
        ↓
ESP32-CAM Video Stream
        ↓
Image Preprocessing
        ↓
YOLO26n-seg AI Model
        ↓
Crack Detection + Segmentation
        ↓
Crack Measurement
        ↓
Severity Analysis
        ↓
Repair Suggestion
        ↓
Streamlit Dashboard
        ↓
Automatic PDF Report
```

---

# 🤖 Hardware Components Used

| Component | Purpose |
|---|---:|
| Arduino Uno SMD R3 | Main controller |
| ESP32-CAM | Live video streaming |
| HC-05 Bluetooth Module | Manual control |
| L298N Motor Driver | Motor control |
| HC-SR04 Ultrasonic Sensor | Obstacle detection |
| SG90 Servo Motors | Pan-tilt movement |
| DC Geared Motors | Rover movement |
| XL4015 Buck Converter | Voltage regulation |
| 3S Lithium-ion Battery | Power supply |
| Capacitors | Noise filtering |

---

# 🧠 Software & Libraries Used

### Languages

- Python
- C/C++

### Frameworks

- Streamlit
- PyTorch
- Ultralytics YOLO

### Libraries

- OpenCV
- NumPy
- Pandas
- Pillow
- Matplotlib
- ReportLab
- CVZone
- PySerial

### Development Tools

- Arduino IDE
- VS Code
- Google Colab
- CUDA
- cuDNN

---

# 💻 System Requirements

| Component | Specification |
|---|---:|
| Processor | Intel Core i5 / Ryzen 5 |
| RAM | 8GB Minimum |
| GPU | NVIDIA RTX 3050 |
| Storage | 10GB Free Space |
| OS | Windows 11 64-bit |

---

# 📂 Project Structure

```text
BuildScan-Rover-AI-Structural-Health-Inspection
│
├── BuildScan_Rover_Thesis.pdf
├── Research_Publication.pdf
│
├── CameraWebServer/
│       app_httpd.cpp
│       CameraWebServer.ino
│
├── Circuit Diagram/
│       circuit_image.png
│
├── crack_detection/
│   │   app.py
│   │   train.py
│   │   test_model.py
│   │
│   └── BuildScan_SegModel/
│       │
│       ├── weights/
│       │      best.pt
│       │      last.pt
│       │
│       ├── results.png
│       ├── confusion_matrix.png
│       └── labels.jpg
│
├── Dashboard View Snapshots/
│
├── Final_Rover_Code/
│       Final_Rover_Code.ino
│
├── Hardware Components/
│
└── Report Generated/
        Camera_Report.pdf
        Upload_Report.pdf
```

---

# ⚙️ Installation Guide

## Clone Repository

```bash
git clone https://github.com/YourUsername/BuildScan-Rover-AI-Structural-Health-Inspection.git

cd BuildScan-Rover-AI-Structural-Health-Inspection
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

or

```bash
pip install streamlit
pip install ultralytics
pip install opencv-python
pip install torch torchvision
pip install numpy pandas matplotlib
pip install reportlab
pip install pillow
pip install cvzone
pip install pyserial
```

---

# 🚀 Running the Project

## Step 1

Upload ESP32 Camera Code

```text
CameraWebServer/CameraWebServer.ino
```

---

## Step 2

Upload Rover Control Code

```text
Final_Rover_Code/Final_Rover_Code.ino
```

---

## Step 3

Run Dashboard

```bash
streamlit run app.py
```

---

# 📊 Dataset Information

Dataset Type:

Crack Segmentation Dataset

Total Images:

```text
4029 Images
```

Dataset Split:

```text
Training Images: 3223 (80%)

Validation Images: 403 (10%)

Testing Images: 403 (10%)
```

---

# 📈 Training Configuration

| Parameter | Value |
|---|---:|
| Model | YOLO26n-seg |
| Epochs | 50 |
| Batch Size | 16 |
| Image Size | 640x640 |
| Framework | PyTorch |
| GPU | RTX 3050 |
| CUDA | Enabled |

---

# 📉 Experimental Results

| Metric | Score |
|---|---:|
| Precision | 91.2% |
| Recall | 86.4% |
| Box mAP@50 | 89.6% |
| Mask mAP@50 | 85.3% |
| F1 Score | 88.7% |

---

# 📷 Dashboard Results

### Live ESP32-CAM Detection

- Real-time crack visualization
- Severity estimation
- Repair suggestions
- Live monitoring

### Local Image Upload Detection

- Upload image analysis
- Crack measurements
- Prediction confidence
- Report generation

---

# 📄 Generated Reports

The system automatically generates PDF reports containing:

- Captured image
- Crack size
- Crack width
- Severity level
- Confidence score
- Repair suggestions
- Date and time

---

# 🏆 Key Contributions

⭐ Integrated AI + Robotics + IoT into a single platform

⭐ Supports both autonomous and manual Bluetooth control

⭐ Real-time crack segmentation using YOLO26n-seg

⭐ Smart dashboard with PDF reporting

⭐ Low-cost and portable structural inspection solution

---

# 🔮 Future Enhancements

- GPS integration
- Cloud storage support
- Mobile app deployment
- Autonomous path planning
- Thermal camera integration
- Multi-defect detection

---

# 📚 Publications

**BuildScan Rover: AI-Based Autonomous Robot for Indoor Structural Health Inspection**

Published in:

**International Conference on Intelligent Computing and Explainable AI (ICICEA'26)**

A.V.C College of Engineering, Mannampandal

ISBN: 978-935717-038-3

April 2026

---

# 📜 Documentation

📘 Thesis:

```text
BuildScan_Rover_Thesis.pdf
```

📄 Research Paper:

```text
Research_Publication.pdf
```


<div align="center">

### ⭐ If you like this project, give it a star ⭐

</div>
