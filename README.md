# Chronic Kidney Disease (CKD) Prediction Using Ensemble Techniques

This project focuses on predicting Chronic Kidney Disease (CKD) using machine learning techniques, specifically an ensemble approach for better accuracy. The goal is to create a reliable and efficient system for early diagnosis of CKD using medical data.

---

## 🎯 Project Objective
The primary objective of this project is to develop a machine learning model capable of accurately predicting chronic kidney disease. The project uses an ensemble technique by combining multiple classifiers to improve the accuracy and reduce overfitting issues.

---

## 📊 Dataset Information
- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/chronic_kidney_disease)
- **Data Size:** 400 patient records
- **Attributes:** 24 (11 numeric and 14 nominal attributes)
- **Class Label:** Binary classification (`CKD` or `Not CKD`)

---

## 📈 Methodology
### ✅ Data Preprocessing
- Handling missing values using collaborative filtering.
- Feature extraction and selection through correlation analysis.
- Data normalization and transformation.

### ✅ Machine Learning Models Used (Ensemble Technique)
The project leverages a **voting classifier** approach using the following base models:
- **Support Vector Machine (SVM)**  
- **Decision Tree Classifier**  
- **Random Forest Classifier**  
- **Logistic Regression**  
- **K-Nearest Neighbors (KNN)**  

### ✅ Voting Classifier
The ensemble approach combines the predictions of multiple models and selects the class with the majority vote, improving prediction accuracy and reducing overfitting.

---

## 🧪 Results
- **Accuracy:** 99.33%  
- **Precision:** 99%  
- **Recall:** 99%  
- **F1-Score:** 99%  

### 📊 Comparative Study:
| **Model**               | **Accuracy** | **Precision** | **Recall** | **F1-Score** |
|------------------------|-------------|--------------|------------|------------|
| Paper [24] (Gradient Boosting) | 97%         | 99%          | 99%        | 99%        |
| Paper [37] (Boosting)         | 98%         | 99%          | 99%        | 99%        |
| **Proposed Model (Voting)**   | **99.33%**  | **99%**      | **99%**    | **99%**    |

---

## 📈 Workflow Steps:
1. **Data Collection:** Chronic Kidney Disease dataset from UCI repository.  
2. **Data Cleaning:** Handling missing values and normalization.  
3. **Feature Selection:** Correlation and dimensionality reduction.  
4. **Model Selection:** SVM, Decision Tree, Random Forest, Logistic Regression, KNN.  
5. **Training:** Ensemble technique using Voting Classifier.  
6. **Evaluation:** Compared with benchmark papers for accuracy and performance metrics.


