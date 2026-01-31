# Bronchiectasis-prediction
A machine learning–based clinical decision support system for predicting Bronchiectasis using patient symptoms and laboratory data.

--

🫁 Bronchiectasis Prediction Using Machine Learning

📌 Project Overview

Bronchiectasis is a chronic lung disease characterized by permanent dilation of the bronchi, leading to recurrent infections and impaired respiratory function. Early prediction can help clinicians initiate timely interventions and reduce complications.

This project uses machine learning classification models to predict the presence of Bronchiectasis based on clinical symptoms and laboratory parameters.


---

🎯 Objectives

Predict whether a patient has Bronchiectasis

Compare multiple ML algorithms

Identify the best-performing model

Build a reliable clinical prediction system



---

🧠 Machine Learning Models Used

Support Vector Machine (SVM)

Decision Tree Classifier

Random Forest Classifier ✅ (Best performing)



---

🗂 Dataset Description

The dataset contains clinical and lab-based features, including:

Feature	Description

Gender	Male / Female
WBC Count	White Blood Cell count (cells/µL)
CRP Level	C-reactive protein (mg/L)
ESR	Erythrocyte Sedimentation Rate (mm/hr)
Hemoglobin	Hemoglobin level (g/dL)
Sputum Color	Clear / Yellow / Green
Chronic Cough	Yes / No
Shortness of Breath	Yes / No
Clubbing	Yes / No
Fatigue	Yes / No
Previous Respiratory Infections	Yes / No
Bronchiectasis (Label)	0 = No, 1 = Yes



---

🔄 Data Preprocessing

Removed non-predictive columns (Patient ID, Age)

Encoded categorical variables using LabelEncoder

Split data into training and testing sets (80:20)



---

📊 Model Evaluation

Cross-validation was used to compare models:

Model	Accuracy (Approx.)

SVM	~61%
Decision Tree	~91%
Random Forest	~95% ✅


Final test accuracy:

Random Forest Accuracy: 97%


---

🚀 Technologies Used

Python

Pandas

NumPy

Scikit-learn

Jupyter Notebook


---

📁 Project Structure

Bronchiectasis-Prediction-ML/
│
├── Bronchiectasis_Prediction.ipynb
├── Bronchiectasis_Prediction_Dataset.xlsx
├── requirements.txt
└── README.md
