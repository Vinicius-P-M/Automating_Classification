# 🧠 AUTOMATED REPORT FOR CLASSIFICATION PROBLEMS  

This project automates the execution and comparison of **four popular classification algorithms**:  
**Logistic Regression**, **Random Forest**, **K-Nearest Neighbors (KNN)**, and **Support Vector Machines (SVM)**.  

I developed mainly to speed up my university projects involving classification models — the script runs all models in sequence and produces a **concise summary report** with performance metrics for each.  

---

## ⚙️ How it works  

1. The user provides a **clean, preprocessed dataset** (in CSV format).  
2. The script automatically:  
   - Loads and splits the data;  
   - Trains the four algorithms;  
   - Evaluates their performance;  
   - Returns a **summary of metrics** (accuracy, precision, recall, F1-score, etc.).  

📝 *Note:* The program currently assumes the dataset contains **no missing values (NaN)** and is **ready for modeling**.  

Example dataset used:  
👉 [Default Forecasting Project](https://github.com/Vinicius-P-M/Default_Forecasting)

---

## 🔢 About KNN Optimization  

The script automatically **optimizes the `n_neighbors` parameter** during KNN training.  
Future updates may include **automatic tuning for `n_estimators`** in the Random Forest model.

---

## 🧩 Required Libraries  

Before running the program, make sure the following packages are installed:


```bash
pip install pandas numpy seaborn scikit-learn matplotlib
