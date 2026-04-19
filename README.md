# 🐱🐶 Cat vs Dog Image Classification using CNN & Transfer Learning

## 🔥 Final Result
Achieved **98.64% accuracy** using Transfer Learning (VGG16) with minimal overfitting.

---

## 📌 Overview
This project focuses on building an intelligent image classification system to distinguish between cats and dogs using Deep Learning.

We started with a basic Convolutional Neural Network (CNN) and progressively improved the model by addressing overfitting and enhancing generalization. The final solution uses **Transfer Learning (VGG16)** to achieve high accuracy and stability.

---

## 👥 Team
This is a **group project** developed as part of university coursework.

- **K.D.H. Rashmika** (Team Lead)  
- R.D.M.N. Premathilaka  
- S.W.L.B. Sandaruwan  
- P.G.H.B. Upasena  

---

## 🎯 Objectives
- Build a baseline CNN model  
- Identify and analyze overfitting  
- Improve model performance using advanced techniques  
- Apply Transfer Learning for better accuracy  

---

## 🧪 Project Workflow

### 1. Baseline Model (CNN)
- Simple CNN trained for initial evaluation  
- Achieved high training accuracy (~99%)  
- Poor validation accuracy (~82%) → **Overfitting identified**

---

### 2. Model Improvements
- Retrained base model → Increased overfitting  
- Built a fresh CNN model → Slight improvement in generalization  

---

### 3. Improved Architecture
- Added **Batch Normalization**
- Applied **Dropout (0.2–0.4)**
- Used **Data Augmentation**
- Increased image resolution

👉 Result: Better generalization, reduced overfitting

---

### 4. Final Model (Transfer Learning - VGG16)
- Used pre-trained **VGG16** model  
- Frozen base layers  
- Added custom classification layers  
- Applied Dropout to reduce overfitting  

👉 Result: **Best performance achieved**

---

## 🧰 Technologies Used
- Python  
- TensorFlow / Keras  
- NumPy  
- Matplotlib  
- Google Colab  

---

## 📊 Results

| Model                     | Accuracy   | Overfitting |
|--------------------------|-----------|------------|
| Baseline CNN             | ~82%      | High       |
| Improved CNN             | ~92%      | Moderate   |
| Transfer Learning (VGG16)| **98.64%**| Very Low   |

---

## 📈 Visual Results

> Add your images here (recommended):
- Training vs Validation Accuracy/Loss Graph  
- Confusion Matrix  
- Sample Predictions  

---

## 💡 Key Learnings
- Overfitting is a major challenge in deep learning  
- More training does not always improve performance  
- **Data quality directly impacts results ("Garbage In, Garbage Out")**  
- Data augmentation improves generalization  
- Transfer Learning is highly effective for real-world problems  

---

## ⚠️ Challenges Faced
- Handling corrupted dataset files  
- Limited GPU resources (Google Colab)  
- Hyperparameter tuning (learning rate, epochs)  

---

## 🚀 Future Improvements
- Fine-tune VGG16 layers for further accuracy  
- Experiment with lightweight models like MobileNet  
- Deploy as a web application (e.g., Streamlit)  

---
