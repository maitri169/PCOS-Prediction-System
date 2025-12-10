# 🩺 **PCOS Prediction – Clinical & Ultrasound Modalities**

A dual-modality machine learning system that predicts **Polycystic Ovary Syndrome (PCOS)** using:

- **Clinical (Hormonal + Symptoms) Data**
- **Ultrasound (Ovarian) Images**

This project evaluates how **biochemical indicators** and **ovarian morphological patterns** contribute to PCOS diagnosis using both classical ML and deep learning.

---

## 📌 **Project Workflow**

### **1️⃣ Clinical Data Pipeline**
- Missing value handling, scaling & feature selection  
- **Models Used:** Logistic Regression, SVM, Random Forest, XGBoost  
- **Top Performer:** ⭐ **Random Forest (~89% accuracy)**  
- **Key Insight:** **AMH**, **LH/FSH ratio**, and **Cycle irregularities** are major predictors.

---

### **2️⃣ Ultrasound Image Pipeline**
- Image resizing → noise reduction → augmentation  
- **Models Used:** Custom CNN, VGG16, ResNet50, DenseNet121, MobileNetV2  
- **Top Performer:** ⭐ **MobileNetV2 (~99% accuracy)**  
- **Key Insight:** Follicle distribution, ovarian volume & stromal texture help detect PCOS.

---

## 🖼 **Important Visuals**

### 📍 **Correlation Heatmap (Clinical Data)**  
`![Correlation Heatmap](results/correlation_heatmap.png)`

---

### 📍 **Ultrasound Augmentation Workflow (GIF Animation)**  
*Shows rotation, shift, zoom, flip, brightness & contrast variations.*

`![Augmentation GIF](results/ultrasound_augmentation.gif)`

---

### 📍 **Sample Ultrasound – Normal vs PCOS**  
Normal Ovary | PCOS Ovary  
:-------------------------:|:-------------------------:  
![Normal](results/sample_normal.png) | ![PCOS](results/sample_pcos.png)

---

### 📍 **Training Curves – MobileNetV2**  
`![Training Curve](results/training_curves.png)`

---

## 📈 **Results Summary**

| **Modality**   | **Best Model**     | **Accuracy** |
|----------------|--------------------|--------------|
| Clinical       | Random Forest       | **~89%**     |
| Ultrasound     | MobileNetV2         | **~99%**     |

---

## ⚙️ **Tech Stack**
- **Python**
- **NumPy, Pandas**
- **Scikit-Learn**
- **TensorFlow / Keras**
- **Matplotlib**

---

## 🚀 **Run the Project**
```bash
git clone https://github.com/maitri169/PCOS-Prediction-System.git
cd PCOS-Prediction-System
pip install -r requirements.txt
