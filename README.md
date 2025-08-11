# 🤟 Sign Language Detection

A real-time sign language detection system using computer vision and deep learning for gesture recognition.

## 📌 Overview

This project uses a webcam to detect hand gestures and recognize American Sign Language (ASL) letters. It leverages MediaPipe for hand tracking and a trained neural network model for classification.

## 📁 Files

- `Sign_language_detection.ipynb` — Main notebook containing the full pipeline: data collection, model training, and real-time prediction.
- `model/` (optional) — Folder to save or load the trained model.
- `data/` (optional) — Folder for storing gesture data (hand landmarks).

## ⚙️ Requirements

Install the necessary Python libraries:

```bash
pip install opencv-python mediapipe tensorflow numpy pandas scikit-learn
