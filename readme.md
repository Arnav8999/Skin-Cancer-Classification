# 🩺 Skin Cancer Classification (9-Class ISIC)

![Python](https://img.shields.io/badge/Python-3.10-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange)
![EfficientNet](https://img.shields.io/badge/Model-EfficientNet-green)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

## 📌 Project Overview

This project implements a 9-class skin lesion classification system using EfficientNet with transfer learning and Stratified 5-Fold Cross Validation on the ISIC dataset.

The goal is to classify dermoscopic images into clinically relevant categories using deep learning while integrating explainability using Grad-CAM.

---

## 📂 Dataset

- ISIC Skin Cancer Dataset
- ~2300 Images
- 9 Diagnostic Classes
- Stratified 5-Fold Cross Validation

Classes:
- Actinic Keratosis
- Basal Cell Carcinoma
- Dermatofibroma
- Melanoma
- Nevus
- Pigmented Benign Keratosis
- Seborrheic Keratosis
- Squamous Cell Carcinoma
- Vascular Lesion

---

## 🧠 Model Architecture

- EfficientNet (ImageNet Pretrained)
- Transfer Learning
- Fine-Tuning Strategy
- Focal Loss
- Data Augmentation
- Grad-CAM Visualization

---

## 📊 Results

- Average 5-Fold Accuracy: ~55–65%
- Best Validation Accuracy: ~XX%
- Cross-validation improves robustness
- Grad-CAM used for lesion region visualization

---

## 🔬 Explainability (Grad-CAM)

Grad-CAM is implemented to visualize the regions influencing model decisions, increasing medical interpretability.

---

## ⚠ Challenges

- Class imbalance
- High inter-class similarity
- Limited dataset size

---

## 🚀 Future Improvements

- Ensemble models
- Advanced augmentation (MixUp / CutMix)
- Larger dataset training
- Hyperparameter optimization

---

## 👨‍💻 Author

**Arnav Singh**  
B.Tech Electronics & Computer Science  
KIIT University  
