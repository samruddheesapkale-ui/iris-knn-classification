# 🌸 Iris Flower Classification using K-Nearest Neighbors (KNN)

## 📌 Project Overview
This project is part of **Task 6 of the AI & ML Internship**.  
The goal is to build a **multi-class classifier** to predict the species of Iris flowers using the **K-Nearest Neighbors (KNN)** algorithm.  

The notebook covers:
- Data loading & exploration  
- Train/Test split  
- Feature standardization  
- KNN training & evaluation  
- Confusion matrix visualization  
- Accuracy comparison for different `k` values  
- Decision boundary visualization  

---

## 🚀 Run in Google Colab
Click below to open and run the notebook in Google Colab:  

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1Kz15bQZGuwrQiNfN6rgRbGerAgXADaqk?authuser=1#scrollTo=4sCgJC-OH1ly)

---

## 📂 Repository Contents
- `Iris.csv` → Dataset used (Iris flower dataset)  
- `KNNClassification.ipynb` → Main Colab notebook with step-by-step implementation  
- `README.md` → Project documentation  
- `screenshots/` → Screenshots showing the results

---

## 🔎 Steps Performed
1. **Data Exploration**
   - Checked dataset structure, summary statistics, and class distribution  

2. **Data Preprocessing**
   - Removed `Id` column  
   - Standardized features using `StandardScaler`  

3. **Model Training**
   - Used KNN classifier with `k=3`  
   - Compared accuracy scores with different `k` values  

4. **Evaluation**
   - Accuracy score  
   - Confusion matrix  
   - Classification report (Precision, Recall, F1-score)  
   - Visualized decision boundaries (using first 2 features)  

---

## 📊 Results
- **Accuracy:** `0.9333` (~93.3%)  

### Classification Report:
             precision    recall  f1-score   support

Iris-setosa       1.00      1.00      1.00        10

Iris-versicolor 0.83 1.00 0.91 10
Iris-virginica 1.00 0.80 0.89 10

   accuracy                           0.93        30
  macro avg       0.94      0.93      0.93        30
weighted avg 0.94 0.93 0.93 30


- **Setosa:** Perfectly classified  
- **Versicolor:** Sometimes misclassified as Virginica  
- **Virginica:** Occasionally misclassified as Versicolor  

---

## 🛠️ Tools & Libraries
- Python 3  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  
- Google Colab  

---

## 🧾 Key Learnings
- KNN works by comparing distances to nearest neighbors and taking majority vote  
- Feature scaling is essential for KNN to work correctly  
- Choosing the right `k` is crucial: small `k` can overfit, large `k` can underfit  
- KNN naturally supports **multi-class classification**  

---

👩‍💻 **Author**  
Samruddhee Sapkale  
📅 *October 2025*  


