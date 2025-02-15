# 📊 CPI Prediction Using Regression Techniques

## 🔍 Overview  
This project focuses on predicting the **Consumer Price Index (CPI)** using multiple regression techniques, including:  
- **Linear Regression**  
- **Polynomial Regression**  
- **Gradient Descent Methods (Batch, Stochastic, Mini-Batch)**  
- **Regularization (Ridge, Lasso, Elastic Net)**  
- **Normal Equation & SVD Equation**  
- **Early Stopping for Optimization**  

## 📂 Dataset  
The dataset includes CPI values for different sectors from **2013 to 2024**, categorized into **Rural, Urban, and Combined** data.  

## 📌 Key Features  
- **Data Cleaning & Preprocessing:**  
  - Handling missing values using **Iterative Imputer & RandomForestRegressor**  
  - Checking for **multicollinearity & linearity**  
  - Removing outliers using **IQR-based filtering**  
- **Exploratory Data Analysis (EDA):**  
  - **Pair plots** for linearity checking  
  - **Heatmaps** for correlation analysis  
- **Model Implementation:**  
  - **Multiple Regression Techniques** implemented and compared  
  - **Gradient Descent Variants** for optimized performance  
  - **Regularization Methods** to prevent overfitting  
  - **Early Stopping** to avoid unnecessary computations  

## 📈 Performance Metrics  
Each model was evaluated using:  
✅ **Mean Squared Error (MSE)**  
✅ **Mean Absolute Error (MAE)**  
✅ **R-Squared Score (R²)**  

## 🛠 Technologies Used  
- **Python** 🐍  
- **Pandas, NumPy** for data handling  
- **Scikit-Learn** for regression models  
- **Matplotlib, Seaborn** for data visualization  

## 🚀 Results & Findings  
- **Polynomial Regression (Degree 4)** showed the highest accuracy with **R² ≈ 0.9997**  
- **Gradient Descent-based models** performed well but required tuning for optimal convergence  
- **Regularized models (Ridge, Lasso, Elastic Net)** helped in handling multicollinearity  

## 📌 How to Run  
1. Clone the repository:  
   ```sh
   git clone https://github.com/Avirup221/CPI-Regression-Project.git
   cd CPI-Regression-Project
