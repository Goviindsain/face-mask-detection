# Face Mask Detection using YOLOv8

## Overview
This project detects whether a person is wearing a mask using object detection (YOLOv8).

## Features
- Detects multiple faces
- Classifies:
  - With Mask
  - Without Mask
  - Incorrect Mask

## Tech Stack
- Python
- YOLOv8 (Ultralytics)
- OpenCV

## 📊 Dataset
Dataset used from Kaggle:

👉 https://www.kaggle.com/datasets/andrewmvd/face-mask-detection

- Contains images and XML annotations  
- Converted to YOLO format for training  

---

## ⚙️ How It Works

### 1. Data Preparation
- Convert XML annotations → YOLO format  
- Normalize bounding box coordinates  
- Split dataset into train and validation  

---

### 2. Model Training
- Used YOLOv8 (nano model for efficiency)  
- Trained on custom dataset  
- Optimized for CPU training  

---

### 3. Prediction
- Model predicts bounding boxes  
- Labels each face with mask status  
- Outputs image with detections  

---