<img width="960" height="540" alt="Attendance_System_Example_Image" src="https://github.com/user-attachments/assets/96a05e4a-0d50-4e19-832f-2b5062823ad8" />
# Real-Time Face Recognition Attendance System


![Python](https://img.shields.io/badge/Python-3.9+-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-Keras-orange)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-green)
![Status](https://img.shields.io/badge/Project-Production--Ready-success)

---

## 🚀 Overview
## Technologies: Python, OpenCV, TensorFlow/Keras, NumPy, Custom CNN
The system processes live video streams, detects human faces, generates embeddings using a **custom CNN model**, and records attendance with timestamps—ensuring each individual is counted **only once per session**.

Designed with **modular architecture**, **clean preprocessing**, and **scalable dataset handling**, this project reflects industry best practices used in large-scale ML systems.

---

## 🧠 Key Features
- **Real-Time Face Detection**
  - Efficient Haar Cascade–based face detection using OpenCV.
- **Deep Learning–Based Face Recognition**
  - Custom CNN trained to generate discriminative facial embeddings.
- **Cosine Similarity Matching**
  - Robust similarity scoring for identity recognition.
- **Duplicate Attendance Prevention**
  - Ensures a person is counted only once per time window.
- **Timestamped Attendance Logging**
  - Accurate and automatic attendance records.
- **Extensible Dataset Pipeline**
  - Simple directory-based structure for adding new identities.

---

## 🧩 Tech Stack
- **Python** – Core application logic
- **OpenCV** – Real-time image & video processing
- **TensorFlow / Keras** – Custom CNN model for face embeddings
- **NumPy** – Numerical operations & vector similarity

---

## 🏗️ System Architecture
1. Capture frames from webcam using OpenCV  
2. Detect faces from each frame  
3. Preprocess detected faces (grayscale, resize, normalize)  
4. Generate face embeddings using a trained CNN  
5. Match embeddings using cosine similarity  
6. Mark attendance with timestamp  
7. Display results in live video stream
   
## System Workflow

1. Capture real-time video frames using a webcam.
2. Detect faces in each frame using OpenCV.
3. Preprocess detected faces (resize, normalize, reshape).
4. Extract facial features using the trained CNN model.
5. Compare embeddings with stored face representations.
6. Mark attendance with timestamps for recognized individuals.

## Display recognition results on the live video feed.
---


## Usage
1. Clone this repository:  
   ```bash
  https://github.com/Korbanul/Real-Time-Face-Recognition-Attendance-System/tree/main
