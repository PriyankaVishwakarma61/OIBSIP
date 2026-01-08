# 📊 Sales Prediction Using Machine Learning (Python)

## 📌 Project Overview
Sales prediction means estimating how much of a product people will buy based on factors such as:
- Advertising budget
- Target audience segment
- Advertising platform

In this project, we use **Machine Learning with Python** to predict product **Sales** based on advertising expenditure on **TV, Radio, and Newspaper**.

This type of prediction helps businesses make better decisions about how much to spend on advertising to maximize sales.

---

## 🎯 Objectives
- Analyze the relationship between advertising budget and sales
- Build a Machine Learning model to predict future sales
- Evaluate model performance using standard metrics

---

## 📂 Dataset
The dataset used in this project is the **Advertising dataset**, which contains the following columns:

| Column Name | Description |
|------------|-------------|
| TV | Advertising budget spent on TV |
| Radio | Advertising budget spent on Radio |
| Newspaper | Advertising budget spent on Newspaper |
| Sales | Sales of the product |

---

## 🛠️ Technologies Used
- Python 🐍
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📈 Machine Learning Model
- **Algorithm Used:** Linear Regression
- **Type:** Supervised Learning
- **Target Variable:** Sales
- **Features:** TV, Radio, Newspaper

---

## 🚀 Project Workflow
1. Import required libraries  
2. Load and explore the dataset  
3. Perform Exploratory Data Analysis (EDA)  
4. Split the dataset into training and testing sets  
5. Train the Linear Regression model  
6. Evaluate the model using MAE, MSE, RMSE, and R² Score  
7. Predict sales for new advertising budgets  

---

## 📊 Model Evaluation Metrics
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## 🧪 Sample Prediction
```python
TV = 150
Radio = 20
Newspaper = 30
Predicted Sales ≈ 14.5 units

