# 🩺 PCOS Prediction System

A **data-driven machine learning project** that predicts **Polycystic Ovary Syndrome (PCOS)** using clinical and ultrasound records. This project applies feature engineering, data visualization, and model evaluation to identify key health indicators linked to PCOS and support early diagnosis.

---

## 📊 Overview

This project analyzes a dataset of **1,200+ patient records**, containing clinical, hormonal, and ultrasound parameters.
Through **data preprocessing, correlation analysis, and statistical modeling**, the system achieved up to **91% accuracy** in predicting PCOS occurrence.

---

## 🧠 Key Highlights

* Cleaned and processed structured healthcare data.
* Identified major influencing parameters using correlation and visualization techniques.
* Trained and evaluated multiple machine learning models to ensure robust predictions.
* Highlighted feature importance and health insights through graphical analysis.

---

## 🧰 Tech Stack

**Languages:** Python
**Libraries:** Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib
**Environment:** Jupyter Notebook

---

## 📂 Project Structure

```
PCOS-Prediction-System/
│
├── dataset/
│   └── PCOS_data.csv                
│
├── notebooks/
│   └── PCOS_Prediction_Analysis.ipynb  
│
├── results/
│   ├── confusion_matrix.png
│   ├── correlation_heatmap.png
│
├── requirements.txt
├── README.md
└── .gitignore
```

---

## 🚀 How to Run

1. Clone the repository

   ```bash
   git clone https://github.com/maitri169/PCOS-Prediction-System.git
   cd PCOS-Prediction-System
   ```
2. Install dependencies

   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook

   ```bash
   jupyter notebook notebooks/PCOS_Prediction_Analysis.ipynb
   ```

---

## 📈 Results

| Metric    | Best Performance |
| --------- | ---------------- |
| Accuracy  | **91.41%**       |
| Precision | 91%              |
| Recall    | 89%              |
| F1-Score  | 90%              |

> **Gradient Boosting** achieved the best overall performance on the dataset.

---

## 🔍 Insights

* Ultrasound-related parameters and hormone levels were found to be major predictors.
* The project highlights the importance of data-driven insights in women’s health research.

---

## 🧩 Future Scope

* Integrate ultrasound image-based classification using Deep Learning (CNN).
* Deploy as a web app for clinical usage via Flask or Streamlit.
* Add explainability using SHAP or LIME for feature interpretation.

---

## 💡 Author

**Maitri**
📍 B.Tech CSE, IGDTUW
🔗 [LinkedIn](https://www.linkedin.com/in/maitri-60b43225a/) | [GitHub](https://github.com/maitri169)

---

