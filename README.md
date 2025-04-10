# MammoScanAI 🧠🔬

**MammoScanAI** is a machine learning-based diagnostic tool for early breast cancer detection, using data science to assist healthcare professionals in classifying tumors as benign or malignant.

## 📌 Project Overview
Breast cancer is one of the most common cancers in women worldwide. Early diagnosis can drastically improve treatment outcomes. This project uses various supervised learning techniques to build a classification model that automates breast cancer diagnosis.

## 🧪 Dataset
- **Source:** [UCI Breast Cancer Wisconsin (Diagnostic) Dataset](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic))
- **Instances:** 569
- **Features:** 30 numeric, 1 target (`diagnosis`: M = Malignant, B = Benign)

## 🔍 Techniques Used
- Exploratory Data Analysis (EDA)
- Feature Selection (Chi-Squared Test)
- Min-Max Normalization
- Model Comparison across:
  - Random Forest 🌲
  - Logistic Regression 📉
  - Support Vector Machine (SVM) ⚙️
  - k-Nearest Neighbors (kNN) 👥
  - Naive Bayes 🧮

## 📊 Evaluation Metrics
- **Accuracy**
- **F1 Score**
- **Precision** (most important in medical diagnosis)
- **Recall**

## 🧠 Best Performing Model
✅ **Random Forest Classifier** achieved the best results across all major metrics and is recommended for use in real-world diagnostic scenarios.


## 👩‍⚕️ Author
Trupti Vithal Shriyan

---

> _“Early detection saves lives — let’s make that faster, smarter, and scalable.”_
