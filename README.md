# 🧠 CSE 574-D: Introduction to Machine Learning – Assignment 1  
### **Classification and Regression Methods from Scratch**

---

## 📝 Description
Implementation of core **machine learning algorithms** — Logistic Regression, Linear Regression, and Ridge Regression — from scratch using Python and NumPy.  
Includes full **data preprocessing**, **visualization**, and **model evaluation** for multiple datasets as part of *CSE 574: Introduction to Machine Learning (Fall 2023)*.

---

## 🎯 Objective
This project focuses on understanding the mathematical foundation of machine learning by manually implementing classification and regression algorithms without external ML libraries such as scikit-learn. You will preprocess datasets, train models, and visualize performance metrics using Python.

---

## 📂 Repository Structure


---

## ⚙️ Technologies Used
- **Python 3.10+**
- **NumPy** – mathematical computations  
- **Pandas** – data manipulation  
- **Matplotlib / Seaborn** – visualization  
- **Pickle** – model serialization  
- **Jupyter Notebook** – experimentation  

> 🚫 ML libraries such as scikit-learn are not used — everything is built manually.

---

## 🧩 Assignment Parts

### **Part 1: Data Preprocessing (10 points)**
- Handle missing values, outliers, normalization, and encoding.
- Generate correlation plots and feature visualizations.
- Save cleaned datasets as:


### **Part 2: Logistic Regression (40 points)**
- Implement logistic regression from scratch using **gradient descent** and the **sigmoid** function.
- Train on the *Penguins dataset* for binary classification.
- Target Accuracy: ≥ 64%.
- Plot **loss vs. iterations**.
- Save model weights to:


### **Part 3: Linear Regression (25 points)**
- Implement **Ordinary Least Squares (OLS)** using:
\[
w = (X^T X)^{-1} X^T y
\]
- Evaluate using **Mean Squared Error (MSE)** and scatter plots.

### **Part 4: Ridge Regression (25 points)**
- Extend OLS by adding **L2 regularization**:
\[
w = (X^T X + λI)^{-1} X^T y
\]
- Compare with linear regression and visualize λ vs. MSE.

### **Bonus (+10 points)**
- Implement **Gradient Descent for Ridge Regression**.  
- Implement **Elastic Net Regularization** (L1 + L2).

---

## 🧪 How to Run
```bash
# 1️⃣ Clone the repository
git clone https://github.com/chanduchallagonda/Pintos-os-project.git
cd Pintos-os-project

# 2️⃣ Run preprocessing notebook
jupyter notebook notebooks/part_1_preprocessing.ipynb

# 3️⃣ Train Logistic Regression
jupyter notebook notebooks/part_2_logistic_regression.ipynb

# 4️⃣ Run Linear and Ridge Regression
jupyter notebook notebooks/part_3_4_linear_ridge_regression.ipynb

