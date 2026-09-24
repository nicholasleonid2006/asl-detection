# American Sign Language (ASL) Recognition
A real-time Computer Vision system designed to classify American Sign Language alphabet gestures, bridging communication barriers through machine learning.

---

## Overview
* **Domain:** Computer Vision & Gesture Recognition
* **Goal:** Multi-class classification of ASL hand gestures using classical ML (SVM/HOG) and MediaPipe landmarking.
* **Dataset:** [ASL Dataset (Kaggle)](https://www.kaggle.com/datasets/ayuraj/asl-dataset/data)
* **Stack:** Python, OpenCV, MediaPipe, Scikit-Learn, Flask

---

## Repository Structure
```text
asl-detection/
├── app.py                  # Flask web interface engine
├── SignLanguageImpl.py     # Feature extraction & classification pipeline
├── Sign_Lang_MP.ipynb      # MediaPipe landmark extraction notebook
├── Sign_Language.ipynb     # Baseline model training notebook
├── frontend/               # Web application UI assets
└── requirements.txt        # Project dependencies
