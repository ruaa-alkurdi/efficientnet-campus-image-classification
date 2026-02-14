# EfficientNet-Based Multi-Class Campus Image Classification

This project presents a deep learning-based multi-class image classification system for university campus environments using transfer learning.

## 📌 Overview
The model classifies campus images into five categories:
- Buildings
- Cars
- Laboratories
- People
- Trees

Two architectures were implemented:
- Baseline EfficientNetB0
- Enhanced EfficientNetB0 with SE attention, class weighting, batch normalization, and dropout

The enhanced model achieved **98.32% test accuracy**, outperforming ResNet50.

## 🧠 Key Features
- Transfer Learning using EfficientNetB0
- Fine-tuning last layers
- Squeeze-and-Excitation Attention mechanism
- Class imbalance handling using class weights
- Performance evaluation using Accuracy, Precision, Recall, F1-score, and Confusion Matrix

## 🛠 Tools & Technologies
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib

## 📊 Results
- Baseline Accuracy: 96.09%
- Enhanced Model Accuracy: 98.32%
- Only 6 misclassified samples in test set

## 📂 Dataset
The dataset consists of 2,370 real campus images across five classes.

---

This project was developed as an academic research-based project at the University of Jordan.
