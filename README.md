# CodeAlpha_Machine-Learning
# 🧠 Machine Learning Projects Repository
> **A collection of machine learning projects including Credit Scoring, Handwritten Character Recognition, and Disease Prediction.**

---

## 💡 Project Highlights

| Area         | Focus                          | Tools / Libraries               |
|--------------|-------------------------------|---------------------------------|
| **Finance**   | Credit Scoring & Risk Analysis | RandomForest, SMOTE, sklearn    |
| **Computer Vision** | Handwritten Character Recognition | CNN, CRNN, TensorFlow    |
| **Healthcare** | Disease Diagnosis Prediction  | SVM, XGBoost, seaborn            |
---

## 📊 **Credit Scoring Model (Task 1)**

### **Objective:**  
Predict individual creditworthiness based on financial and transactional history.

### **Features:**

- **Dataset:** UCI Credit Card Default Dataset
- **Algorithms:**  
  - Logistic Regression  
  - Decision Tree  
  - Random Forest
- **Techniques:**  
  - Feature Scaling (StandardScaler)  
  - Imbalanced data handling (SMOTE)
- **Metrics:**  
  - Precision, Recall, F1-Score, ROC-AUC

### **Results:**  

| Metric      | Score |
|-------------|-------|
| **Accuracy** | 85%   |
| **ROC-AUC**  | 0.75  |

**Use case:** Can be integrated into banking systems for automated credit risk analysis.

---

## ✍️ **Handwritten Character Recognition (Task 3)**

### **Objective:**  
Identify handwritten characters and extend to word-level recognition.

### **Features:**

- **Dataset:** EMNIST Letters
- **Models:**  
  - **CNN** for isolated character recognition  
  - **CRNN + CTC Loss** for sequence/word prediction
- **Technologies:** TensorFlow, TensorFlow Datasets

### **Results:**  

| Model | Validation Accuracy |
|--------|--------------------|
| **CNN**  | 91%                |
| **CRNN** | Suitable for text sequences |

---

## 🩺 **Disease Prediction (Task 4)**

### **Objective:**  
Predict disease outcomes (Breast Cancer: benign or malignant).

### **Features:**

- **Dataset:** Breast Cancer (UCI Repository)
- **Algorithms:**  
  - Logistic Regression  
  - Support Vector Machine (SVM)  
  - Random Forest  
  - XGBoost
- **Evaluation Metrics:** Accuracy, Confusion Matrix, Classification Report

### **Results:**

| Model | Accuracy |
|--------|----------|
| **SVM** | 98.25%   |
| Logistic Regression | 97.37% |
| Random Forest | 95.61% |
| XGBoost | 95.61% |
--

### 👥 Contributors
Project Lead: Rubaika Akhtar

Intern Team: Code Alpha
