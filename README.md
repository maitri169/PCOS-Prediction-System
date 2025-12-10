# 🩺 PCOS Prediction System  
### **Dual-Modality Diagnosis using Clinical Features & Ultrasound Imaging**

A machine learning system designed to predict **Polycystic Ovary Syndrome (PCOS)** using:

- **Clinical Data (Hormonal + Demographic + Symptom Features)**
- **Ultrasound Images (Ovarian Morphology)**

The project compares how **biochemical markers** vs **morphological patterns** contribute to PCOS diagnosis.

---

## 🚀 Overview

This study evaluates two independent pipelines:

### **1️⃣ Clinical Modality**
- Feature cleaning, encoding & z-score scaling  
- Hormonal markers: **AMH, LH, FSH, LH/FSH ratio**  
- ML Models: Logistic Regression, Decision Tree, KNN, SVM, MLP, Random Forest, Gradient Boosting  
- **Best Model:** ⭐ *Gradient Boosting (91.41% accuracy)*  
- **Most stable model:** ⭐ *Random Forest (89.57% accuracy)*  

---

### **2️⃣ Ultrasound Modality**
- Standardized preprocessing: resizing → denoising → contrast enhancement  
- Augmentation for robustness  
- DL Models: VGG16, ResNet50, DenseNet121, MobileNetV2  
- **Best Model:** ⭐ *MobileNetV2 (99% accuracy)*  
- Ultrasound morphology: follicle clustering, stromal texture & ovarian volume

---

## 🖼 Key Visuals

### 📊 **Clinical Feature Correlation (Heatmap)**
<img width="1295" height="1188" alt="image" src="https://github.com/user-attachments/assets/7d7964a9-bff9-4daa-8f33-97cb4a0654ca" />


---

### 🌀 **Ultrasound processing and visualization**
*Includes rotation, zoom, brightness, cropping, flipping.*
<img width="1489" height="926" alt="image" src="https://github.com/user-attachments/assets/7cd6318e-88ef-4aa0-9f13-762e7d6804d3" />


---

### 🫧 **Normal vs PCOS Ovary**
<img width="1462" height="670" alt="image" src="https://github.com/user-attachments/assets/c09aef9b-a4f2-4027-8988-c2eae0c24bd0" />

---

## 📈 Final Results

### **Clinical Models Performance**
| Model               | Accuracy | Precision | Recall | F1-Score |
|---------------------|----------|-----------|--------|----------|
| Gradient Boosting   | **91.41%** | 91%       | 89%    | 90%      |
| Random Forest       | **89.57%** | 90%       | 88%    | 89%      |
| Logistic Regression | 84.66%   | 86%       | 85%    | 85%      |

---

### **Ultrasound Models Performance**
| Model         | Accuracy | Precision | Recall | F1-Score |
|---------------|----------|-----------|--------|----------|
| **MobileNetV2**  | **99.0%** | 100%     | 97.53% | 98.75%   |
| DenseNet121   | 99.0%    | 98.77%   | 98.77% | 98.77%   |
| VGG16         | 98.5%    | 100%     | 96.30% | 98.11%   |
| ResNet50      | 76.5%    | 100%     | 41.98% | 59.13%   |

---

## ⚙️ Tech Stack
- **Python**, NumPy, Pandas  
- **Scikit-Learn**  
- **TensorFlow/Keras**  
- Matplotlib, OpenCV  

---

## 🛠 Run the Project

```bash
git clone https://github.com/maitri169/PCOS-Prediction-System.git
cd PCOS-Prediction-System
pip install -r requirements.txt


