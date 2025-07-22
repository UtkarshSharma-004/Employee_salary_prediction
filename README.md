# 💼 Employee Salary Prediction using Machine Learning

This project was developed as part of the **IBM + Edunet Foundation Internship**, aimed at predicting employee salaries based on various features using a machine learning model. A user-friendly Gradio interface is also built for real-time predictions.

---

## 📊 Dataset Overview

The dataset includes the following features:

- **Age**
- **Gender**
- **Education Level**
- **Job Title**
- **Years of Experience**
- **Salary** *(Target Variable)*

---

## 🛠️ Tech Stack

- **Python**
- **Pandas, NumPy** – Data manipulation
- **Matplotlib, Seaborn** – Data visualization
- **Scikit-learn** – Model training
- **Gradio** – Web interface for prediction
- **Google Colab** – Cloud-based development

---

## 🚀 Project Features

- 📈 Visual exploration of salary distribution and trends
- 📦 Outlier detection and removal using IQR method
- 🔍 Model training using `RandomForestRegressor`
- 🎯 High prediction accuracy with evaluation metrics
- 🌐 Gradio-powered web app for salary prediction

---

## 📊 Data Visualization Samples

- **Histogram of Salary Distribution**
- **Scatter Plot of Salary vs Experience**
- **Boxplots to Detect Outliers by Education and Gender**

---

## 🧠 Model Performance

| Metric | Value |
|--------|-------|
| R² Score | ~0.98 |
| MAE | ₹2,700 approx |
| MSE | ~47,00,000 |

---

## 🖥️ Gradio Web App

Once the model is trained, you can interact with the app using dropdowns and sliders for:

- Age
- Gender
- Education Level
- Job Title
- Experience

The model then predicts and displays the **expected salary**.

---

## 📁 How to Run (Google Colab)

1. Open the notebook in **Google Colab**
2. Upload your dataset (`Salary_Data.csv`)
3. Follow the cells to visualize, train, and launch the app

---

## 📎 File Structure

# Employee_salary_prediction
