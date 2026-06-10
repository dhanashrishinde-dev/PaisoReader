# 💸 PaisoReader – Currency Detection and Counting Application

<p align="center">
  <img src="assets/paisoreader-banner.png" alt="PaisoReader Banner" width="1000"/>
</p>

<p align="center">
  <strong>Real-Time Currency Detection and Automated Value Calculation using YOLOX, ONNX Runtime, and OpenCV</strong>
</p>

---

## 🌟 Overview

PaisoReader is an AI-powered Computer Vision application designed to automatically detect, classify, and count currency notes in real time.

The system leverages the YOLOX object detection framework to identify multiple currency denominations simultaneously and calculate the total monetary value instantly. Optimized with ONNX Runtime, the application delivers fast edge inference suitable for real-time deployment on resource-constrained devices.

Additionally, the application provides synchronized audio feedback, making it useful for accessibility-focused financial assistance systems.

---

## 📸 Application Demo

### Currency Detection

<p align="center">
  <img src="assets/currency-detection.png" width="1000">
</p>

The system detects multiple notes simultaneously and identifies their denominations accurately.

---

### Real-Time Value Calculation

<p align="center">
  <img src="assets/value-calculation.png" width="1000">
</p>

Detected notes are automatically summed to provide the total currency value in real time.

---

### Audio Output Integration

<p align="center">
  <img src="assets/audio-output.png" width="1000">
</p>

The calculated amount is announced through synchronized audio output for improved accessibility.

---

## 🚀 Key Features

### 🔍 Real-Time Currency Detection

* Multi-note detection
* Multiple denomination support
* Real-time video processing
* High detection accuracy

### 🧠 YOLOX-Based Object Detection

* State-of-the-art object detection architecture
* Fast inference speed
* Robust detection performance
* Accurate denomination classification

### ⚡ Edge AI Optimization

* ONNX Runtime acceleration
* Low-latency inference
* Optimized deployment pipeline
* Resource-efficient execution

### 💰 Automated Currency Counting

* Instant value computation
* Multiple note aggregation
* Real-time total updates

### 🔊 Audio Feedback System

* Text-to-speech integration
* Accessibility support
* Instant value announcement

---

## 🏗️ System Architecture

```text
Camera Input
      │
      ▼
Frame Capture
(OpenCV)
      │
      ▼
Image Preprocessing
      │
      ▼
YOLOX Detection Model
      │
      ▼
Currency Note Detection
      │
      ▼
Denomination Classification
      │
      ▼
Total Value Calculation
      │
      ├─────────────► Audio Output
      │
      ▼
Real-Time Display
```

---

## ⚙️ Execution Flow

### Step 1: Image Acquisition

The application captures live video frames from the camera using OpenCV.

### Step 2: Preprocessing

Frames are resized and prepared for inference.

### Step 3: Currency Detection

YOLOX identifies currency notes present in the frame.

### Step 4: Denomination Classification

Each detected note is classified according to its denomination.

Example:

```text
₹10
₹20
₹50
₹100
₹200
₹500
```

### Step 5: Value Aggregation

Detected denominations are summed automatically.

Example:

```text
₹500 + ₹200 + ₹100 + ₹50

Total Amount = ₹850
```

### Step 6: Audio Announcement

The calculated amount is converted into speech and announced.

### Step 7: Real-Time Visualization

Bounding boxes and calculated totals are displayed on the screen.

---

## 📊 Performance Metrics

| Metric          | Value        |
| --------------- | ------------ |
| Detection Model | YOLOX        |
| Framework       | ONNX Runtime |
| Accuracy        | 90%+         |
| Latency         | ~110 ms      |
| Processing Mode | Real-Time    |
| Detection Type  | Multi-Object |

---

## 🛠️ Technology Stack

### Computer Vision

* OpenCV
* YOLOX

### Deep Learning

* PyTorch
* ONNX

### Inference Optimization

* ONNX Runtime

### Programming Language

* Python

### Audio Processing

* Text-to-Speech (TTS)

---

## 🎯 Use Cases

* Currency Counting Automation
* Smart Financial Assistance Systems
* Retail Cash Management
* Banking Applications
* Accessibility Solutions for Visually Impaired Users
* Automated Cash Verification

---

## 📈 Project Highlights

✅ Real-Time Currency Detection

✅ Multi-Note Recognition

✅ 90%+ Detection Accuracy

✅ Edge AI Optimization

✅ Low-Latency Inference (~110ms)

✅ Automatic Value Calculation

✅ Audio Feedback Integration

✅ Computer Vision Deployment Pipeline

---

## 🔮 Future Enhancements

* Mobile Application Deployment
* Multi-Currency Support
* Counterfeit Currency Detection
* OCR-Based Serial Number Recognition
* Cloud Dashboard Integration
* Edge Device Deployment (Raspberry Pi / Jetson Nano)

---


### Skills Demonstrated

* Computer Vision
* Deep Learning
* Object Detection
* YOLOX
* OpenCV
* Edge AI
* ONNX Runtime
* Model Optimization
* Real-Time Inference

---

⭐ If you found this project useful, consider giving it a star.
