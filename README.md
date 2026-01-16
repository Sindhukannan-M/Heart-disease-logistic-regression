# Heart Disease Prediction using Logistic Regression

### 🎯 Objective

Classify whether a person has heart disease based on lifestyle, medical history, and demographic factors.

---

### 📂 Dataset

Features include:

* Age group, gender, BMI
* Exercise habits, smoking, alcohol use
* Past medical checkups
* Comorbidities (diabetes, depression, skin cancer)
* Dietary patterns (fruits, vegetables, fried food)

A **sample dataset** is provided in `data/sample_dataset.csv`.
*Full dataset (~31MB) excluded due to size.*

---

### 🔧 Approach

1. Loaded and cleaned dataset
2. Handled categorical features using encoding
3. Exploratory Data Analysis (pairplots, violin plots)
4. Train–test split
5. Trained Logistic Regression model
6. Evaluated model performance

---

### 📊 Result

**Accuracy:** 38.89%
(Logistic Regression baseline)

---

### 🛠️ Tech Stack

* Python
* Pandas, NumPy
* Scikit-learn
* Matplotlib / Seaborn

---

### 🚀 Future Improvements

* Feature engineering
* Model tuning
* Algorithm comparison (Random Forest, SVM, etc.)
