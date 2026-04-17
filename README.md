
# 🌿 PlantGuard: Plant Disease Classification using Deep CNN with PyTorch

PlantGuard is a deep learning-based plant disease classification system built using **PyTorch** and **Convolutional Neural Networks (CNN)**.  
It is trained on the **PlantVillage dataset** to classify healthy and diseased plant leaves across multiple crop species.

---

## 📌 Project Overview

This project focuses on automating plant disease detection using image classification.  
The model learns visual patterns from leaf images and predicts the corresponding disease class or healthy status.

---

## 📊 Dataset

- **Dataset:** PlantVillage Dataset  
- **Total Images:** ~54,000+  
- **Crop Species:** 14  
- **Classes:** Healthy + Multiple diseases (17 diseases, 4 bacterial, 2 viral, 2 fungal, etc.)

---

## 🧠 Model Architecture

A custom **Deep CNN** model is used with:

- Convolutional Layers (Feature Extraction)
- Batch Normalization
- ReLU Activation
- Max Pooling
- Fully Connected Layers
- Dropout for Regularization

---

## ⚙️ Technologies Used

- Python 🐍  
- PyTorch 🔥  
- Torchvision  
- NumPy  
- PIL (Pillow)

---

## 🚀 Training Pipeline

1. Load and preprocess dataset
2. Apply transformations (Resize, Normalize, Tensor conversion)
3. Train CNN model using CrossEntropyLoss
4. Optimize using Adam optimizer
5. Evaluate on test dataset

---

## 📈 Results

- High training accuracy achieved
- Strong generalization on test dataset
- Minimal overfitting observed

*(You can update this section with exact accuracy values)*

---

## 📂 Project Structure
