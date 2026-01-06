# Titanic_ML
Predicting Titanic passenger survival using machine learning models with feature engineering and performance evaluation.

# Titanic Survival Prediction using Machine Learning

## 📌 Project Overview
This project applies **supervised machine learning** techniques to the classic **Titanic dataset** to predict passenger survival.  
The analysis follows an end-to-end data science workflow, including data exploration, preprocessing, feature engineering, model training, and evaluation.

The goal is to identify key factors influencing survival and build predictive models using structured passenger data.

---

## 🎯 Objectives
- Perform exploratory data analysis (EDA) on passenger demographics and travel information  
- Clean and preprocess missing and categorical data  
- Engineer meaningful features for modeling  
- Train and evaluate machine learning classification models  
- Assess model performance using standard evaluation metrics  

---

## 📂 Dataset
- **Source:** Kaggle – Titanic: Machine Learning from Disaster  
- **Target Variable:** `Survived` (0 = No, 1 = Yes)  
- **Features:** Passenger class, age, sex, fare, family relationships, embarkation port, etc.

> 📌 The dataset represents a historical passenger manifest and is commonly used for benchmarking classification models.

---

## 🧠 Methodology

### 1. Exploratory Data Analysis (EDA)
- Summary statistics and distributions  
- Survival analysis by gender, class, and age  
- Visualization of key feature relationships  

### 2. Data Preprocessing
- Handling missing values (e.g., Age, Embarked)  
- Encoding categorical variables  
- Feature scaling where required  

### 3. Feature Engineering
- Creation of derived features (e.g., family size, title extraction if applicable)  
- Selection of relevant predictors  

### 4. Model Training
- Baseline classification models trained on processed data  
- Hyperparameter tuning where applicable  

### 5. Model Evaluation
- Accuracy  
- Confusion matrix  
- Precision, recall, and F1-score  

---

## 📊 Evaluation Metrics
The models are evaluated using:
- **Accuracy**
- **Precision**
- **Recall**
- **F1-score**

These metrics provide a balanced view of classification performance, especially for imbalanced outcomes.

---

## 🗂 Repository Structure
├── notebooks/
│ └── Titanic_ML.ipynb
├── data/
│ └── README.md
├── README.md
├── .gitignore
└── requirements.txt


---

## 🛠️ Tools & Technologies
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

---

## 🔍 Key Takeaways
- Passenger survival was strongly influenced by **gender**, **passenger class**, and **age**
- Feature engineering significantly improves model performance
- Simple machine learning models can achieve strong predictive accuracy on structured data

---

## ⚠️ Disclaimer
This project is for **educational and analytical purposes only** and does not represent real-time decision-making systems.

---

## 👤 Author
**Arifa Farhath**  
Graduate Student – Data Science

## 🗂 Repository Structure
