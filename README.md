#  License Plate Recognition System

##  Overview
This project implements an Automatic License Plate Recognition (ALPR) system using Computer Vision and Deep Learning. It detects vehicle number plates and predicts the plate text.

##  Features
- Plate detection using OpenCV (Canny + contours)
- Plate cropping using XML annotations
- OCR-based label extraction
- CNN + LSTM model for text prediction
- Synthetic dataset generation (3000+ images)

##  Model
CNN for feature extraction + LSTM for sequence prediction.

##  Results
- Character Accuracy: ~30–60%
- Plate Accuracy: Improving with better data

##  Tech Stack
Python, OpenCV, PyTorch, EasyOCR

##  Output
Takes vehicle image → detects plate → predicts number
