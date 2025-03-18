# House_Price_Prediction_Boston_Housing_Dataset
This notebook demonstrates how to build a simple Linear Regression model to predict house prices using the Boston Housing Dataset.

# 🏡 House Price Prediction using Linear Regression

## 📌 Introduction  
This repository contains a **Jupyter Notebook** demonstrating how to build a **Linear Regression** model to predict house prices using the **Boston Housing Dataset**.  
We use `RM` (average number of rooms per dwelling) as the **feature** and `MEDV` (median house price in $1000s) as the **target variable**.

---

## 📖 Lesson Notes  

### 1️⃣ Features & Target  
- **Feature (`X`)**: Input variable(s) used to make predictions. (e.g., number of rooms `RM`)  
- **Target (`y`)**: The variable we want to predict. (e.g., house price `MEDV`)  

### 2️⃣ Univariate vs. Multivariate Regression  
- **Univariate Regression**: Model with only **one feature** (`X`). Example: Predicting house prices using only `RM`.  
- **Multivariate Regression**: Model with **multiple features** (`X1, X2, X3...`). Example: Predicting house prices using `RM`, `LSTAT`, `TAX`, etc.  

### 📊 Underfitting vs. Overfitting
- **Underfitting:** Model is too simple & doesn’t learn enough.
-- Example: Using just one feature when more are needed.
- **Overfitting:** Model memorizes training data instead of learning patterns.
-- Example: A student memorizing math problems instead of understanding concepts.
