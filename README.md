# 🌿 PlantGuard: Plant Disease Classification using Deep CNN with PyTorch

PlantGuard is a deep learning-based plant disease classification system built using **PyTorch** and **Convolutional Neural Networks (CNN)**. It is trained on the **PlantVillage dataset** to classify plant leaf images into **38 different classes**, including healthy and diseased leaves across multiple crop species.

---

## 📌 Project Overview

This project automates plant disease detection using image classification. The model learns visual patterns from leaf images and predicts the correct class among 38 categories, including healthy leaves and various plant diseases.

---

## 📊 Dataset

- **Dataset:** PlantVillage Dataset  
- **Total Images:** ~54,000+  
- **Crop Species:** 14  
- **Classes:** 38 total classes  
  - Healthy leaves  
  - Fungal, bacterial, viral diseases  

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

1. Load PlantVillage dataset  
2. Apply preprocessing (Resize, Normalize, ToTensor)  
3. Train Deep CNN using CrossEntropyLoss  
4. Optimize using Adam optimizer  
5. Evaluate on test dataset  

---

## 📈 Results

- Training Accuracy: ~88.6%  
- Testing Accuracy: ~87.0%  
- Good generalization with minimal overfitting  

---

## 📂 Project Structure

PlantGuard/
│── dataset/
│── models/
│── train.py
│── test.py
│── dataset.py
│── utils.py
│── README.md

---

## ▶️ How to Run

### Clone repository
git clone https://github.com/your-username/plantguard-pytorch-cnn.git  
cd plantguard-pytorch-cnn  

### Install dependencies
pip install torch torchvision numpy pillow  

### Train model
python train.py  

### Test model
python test.py  

---

## 📌 Future Improvements

- Transfer learning (ResNet, EfficientNet)  
- Data augmentation  
- Hyperparameter tuning  
- Deployment using Flask/FastAPI  
- Mobile app integration  

---

## 🤝 Acknowledgements

- PlantVillage Dataset  
- PyTorch Framework  

---
