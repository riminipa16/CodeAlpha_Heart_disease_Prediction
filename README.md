# CodeAlpha_Heart_disease_Prediction
# 🩺 Disease Prediction Using Machine Learning

## 📌 Project Overview
This project focuses on predicting the **possibility of diseases based on patient medical data** using **machine learning classification techniques**.  
Structured healthcare datasets are used to classify whether a patient is likely to have a disease or not.

The current implementation uses the **Heart Disease dataset from the UCI Machine Learning Repository** and evaluates multiple classification models to compare performance.

---

## 🎯 Objectives
- Predict disease presence using patient health records  
- Apply and compare multiple machine learning classifiers  
- Evaluate model performance using standard metrics  
- Enable disease prediction for new patient inputs  

---

## 🧠 Machine Learning Approach
The project follows a **supervised classification approach**:
1. Data preprocessing and cleaning  
2. Feature scaling  
3. Train–test split  
4. Model training  
5. Model evaluation  
6. New patient prediction  

---

## 📊 Dataset
- **Name:** Heart Disease Dataset  
- **Source:** UCI Machine Learning Repository  
- **Type:** Structured medical dataset  

### Target Variable
- `0` → No disease  
- `1` → Presence of disease  

### Sample Features
- Age  
- Sex  
- Chest pain type  
- Resting blood pressure  
- Cholesterol level  
- ECG results  
- Maximum heart rate  
- Exercise-induced angina  

---

## 🤖 Algorithms Used
The following classification models are implemented and compared:

- Logistic Regression  
- Support Vector Machine (SVM)  
- Random Forest Classifier  
- XGBoost Classifier  

---

## 🛠️ Technologies & Libraries
- Python 3  
- NumPy  
- Pandas  
- Scikit-learn  
- XGBoost  

---

## 📁 Project Structure

---

## ⚙️ How to Run the Project

### 1️⃣ Install Required Libraries
```bash
pip install numpy pandas scikit-learn xgboost
python disease_prediction.py
