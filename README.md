PCOS Prediction – Clinical & Ultrasound Modalities

A dual-modality machine learning system that predicts Polycystic Ovary Syndrome (PCOS) using:

Clinical (Hormonal + Symptoms) Data

Ultrasound (Ovarian) Images

This project compares how biochemical indicators and morphological changes contribute to PCOS diagnosis.

📌 Project Workflow
1. Clinical Data Pipeline

Preprocessing → Feature Selection → Scaling

Models: Logistic Regression, SVM, Random Forest, XGBoost

Best Model: Random Forest

Key Insight: Hormonal markers (AMH, LH/FSH) strongly influence prediction.

2. Ultrasound Image Pipeline

Augmented & preprocessed ultrasound images

Models: Custom CNN, VGG16, ResNet50, DenseNet121, MobileNetV2

Best Model: Fine-tuned MobileNetV2

Key Insight: Follicle count & ovarian volume patterns drive detection.

🖼 Important Visuals
📍 Correlation Heatmap (Clinical Data)
<img width="1295" height="1188" alt="image" src="https://github.com/user-attachments/assets/2e55e2f9-0a39-4151-ae5d-625bb24b33e9" />


📍 Preprocessing of Ultrasound Images
<img width="1489" height="926" alt="image" src="https://github.com/user-attachments/assets/9b5ffb89-aa43-4de3-8249-e848e2bce83d" />

	
📍 Training Curves – VGG16

📈 Results Summary
Modality	Best Model	Accuracy
Clinical	Random Forest	~89%
Ultrasound	MobileNetV2 ~99%
⚙️ Tech Stack

Python, NumPy, Pandas, Scikit-Learn, TensorFlow/Keras, Matplotlib

🚀 Run the Project
git clone https://github.com/maitri169/PCOS-Prediction-System.git
cd PCOS-Prediction-System
pip install -r requirements.txt

👩‍💻 Author

Maitri
B.Tech CSE, IGDTUW

