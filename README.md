# Logistic-Regression

# 🧠 Logistic Regression - Binary Classification (Breast Cancer Detection)

## 📘 Overview
This project demonstrates how to build a **binary classification model** using **Logistic Regression** in Python.  
We use the **Breast Cancer Wisconsin dataset** to predict whether a tumor is **malignant (M)** or **benign (B)** based on several cell nucleus features.

---

## 🎯 Objective
To understand and implement the **Logistic Regression algorithm** for binary classification,  
evaluate its performance using standard metrics, and visualize important concepts such as the **ROC Curve** and **Sigmoid Function**.

---

## 🧰 Tools & Libraries
- **Python**
- **Pandas** – for data loading and preprocessing  
- **NumPy** – for numerical operations  
- **Scikit-learn** – for model training and evaluation  
- **Matplotlib / Seaborn** – for data visualization  

---

## 📂 Dataset
Dataset used: **Breast Cancer Wisconsin (Diagnostic) Data Set**  
File: `data.csv`  
Target column: `diagnosis` (M = 1, B = 0)

If you don’t have it yet, you can download from [Kaggle](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data).

---

## ⚙️ Steps Involved

1. **Import Libraries**  
   Load essential Python libraries for data science.

2. **Load and Explore Data**  
   Read the dataset using Pandas and check for null values, data types, and basic statistics.

3. **Data Cleaning & Preprocessing**  
   - Dropped unnecessary columns like `id`.  
   - Encoded target variable (`M` → 1, `B` → 0).  
   - Filled missing values using column mean.  
   - Scaled features using `StandardScaler`.

4. **Train-Test Split**  
   Split the data into training (80%) and testing (20%) sets.

5. **Model Training**  
   Trained a `LogisticRegression` model using the scaled features.

6. **Model Evaluation**  
   Computed the following metrics:
   - Accuracy  
   - Precision  
   - Recall  
   - F1-Score  
   - ROC-AUC  

7. **Visualization**
   - **Confusion Matrix** using Seaborn heatmap  
   - **ROC Curve** to evaluate model performance  
   - **Sigmoid Curve** to understand Logistic Regression’s probability output

---

## 📊 Results

| Metric | Score |
|--------|--------|
| Accuracy | ~97–99% |
| Precision | ~96–98% |
| Recall | ~97–99% |
| F1 Score | ~97–98% |
| ROC-AUC | ~0.99 |

*(Values may vary slightly depending on random state and preprocessing method)*

---

## 📈 Visualizations
- Confusion Matrix  
- ROC Curve  
- Sigmoid Function Graph  

---

## 💡 Key Learnings

- Logistic Regression is used for **binary classification** problems.
- The **Sigmoid Function** maps values between 0 and 1 to represent probability.
- The **ROC Curve** and **AUC** help visualize the tradeoff between true positives and false positives.
- Proper feature scaling and preprocessing significantly improve model performance.


---
