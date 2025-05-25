# ❤️ Cardiac Arrest Prediction Model

This project uses advanced machine learning techniques to predict potential cardiac arrest events before they occur — a step forward in preventive healthcare. By analyzing patient medical data and physiological indicators, the model aims to identify at-risk individuals with greater precision than traditional diagnostics.

---

## 🩺 Problem Statement

Cardiovascular diseases are a leading cause of death globally. Traditional diagnostic methods often fail to detect risk early enough for timely intervention. This project addresses that gap by developing a **predictive model** that flags high-risk patients *before* a cardiac event occurs, enabling earlier, more targeted treatment.

---

## 🎯 Project Objectives

- Predict cardiac arrest likelihood from patient health data
- Improve early intervention and reduce mortality
- Demonstrate the effectiveness of supervised ML models in clinical prediction

---

## 🧠 Machine Learning Models Used

- **Logistic Regression** – for binary classification
- **Decision Tree** – for interpretability and branching logic
- **Support Vector Machine (SVM)** – for high-dimensional decision boundaries
- **Random Forest** – for ensemble accuracy
- **Neural Network** – for deep learning and non-linear relationships

All models were evaluated using **Cross Validation**, **ROC-AUC**, and **GridSearchCV** for hyperparameter tuning.

---

## 📁 Project Timeline

| Week | Focus |
|------|-------|
| 1️⃣ | Data collection, cleaning, and exploratory data analysis (EDA) |
| 2️⃣ | Bivariate analysis and feature selection |
| 3️⃣ | Apply Logistic Regression, tune hyperparameters, evaluate initial metrics |
| 4️⃣ | Train Decision Tree, SVM, Random Forest; finalize model comparisons; compile results |

---

## ⚙️ Tools & Technologies

- **Languages**: Python
- **Libraries**: Scikit-learn, Pandas, NumPy, Matplotlib
- **Techniques**: Feature Engineering, EDA, ROC Curve, GridSearchCV

---

## 📊 Evaluation Metrics

- Accuracy  
- Precision  
- Recall  
- F1-Score  
- ROC-AUC

These metrics helped assess the clinical relevance of each model’s predictions.

---

## ✅ Results

- Models demonstrated strong predictive power, particularly Random Forest and Neural Networks
- GridSearchCV tuning improved AUC and recall for critical class (positive cardiac event)
- Early risk markers were identified, highlighting potential for real-world application in hospital alert systems

---

## 🧠 Key Learnings

- Ensemble models like Random Forest offer robustness in healthcare prediction
- Neural Networks capture complex patterns in physiological signals
- Model interpretability is critical when deploying in clinical settings

---

## 📌 Future Work

- Deploy model via Flask API for healthcare app integration
- Use SHAP values for feature interpretability
- Explore live data streaming for real-time risk monitoring

---

## 👨‍⚕️ Authors

- Vineeth Amsham  
- Sai Reddy Balaiah  
- Tamilkumar Subbarayakgounder

> *“This project demonstrates how data-driven science can save lives before symptoms ever appear.”*

---

## 📚 References

1. Patel B, Sengupta P. *Machine learning for predicting cardiac events: what does the future hold?*  
2. Alpaydin E. *Introduction to Machine Learning*, 4th Ed., MIT Press, 2020  
3. Abdar M et al. *Boosted decision trees for medical diagnostics*, J Med Biol Eng., 2017  
