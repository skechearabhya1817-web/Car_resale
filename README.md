📊 Regression Analysis Project
📌 Project Overview
This project focuses on building and evaluating multiple regression models using a structured machine learning workflow. The goal is to analyze the dataset, apply different regression techniques, and compare their performance using standard evaluation metrics.

🧠 Workflow Followed

The project was completed using the following steps:
Data Collection
Dataset collected from a reliable source (CSV format).
Data Cleaning
Handled missing values
Removed inconsistencies and duplicates
Data Wrangling & Preprocessing
Feature selection
Data transformation
Train–test split
Regression Models Implemented
Linear Regression (LR)
Polynomial Regression (PR)
Lasso Regression (LA)
Evaluation Metrics Used
Mean Absolute Error (MAE)
Mean Squared Error (MSE)
Root Mean Squared Error (RMSE)
Coefficient of Determination (R² Score)

📈 Model Performance Results
Model	MAE	MSE	RMSE	R²
Polynomial Regression (PR)	1.98	4.76	2.18	0.86
Lasso Regression (LA)	6.90	7.45	8.63	1.00
Linear Regression (LR)	1.98	4.76	2.18	0.86

🏆 Best Regression Model
Based on error metrics (MAE, MSE, RMSE):
👉 Polynomial Regression and Linear Regression performed better with lower error values.
Based on R² Score:
👉 Lasso Regression achieved the highest R² score (1.00), indicating a perfect fit on the dataset.

✅ Final Conclusion:
While Lasso Regression shows the highest R² value, Polynomial and Linear Regression provide more balanced and reliable performance considering error metrics. The choice of the best model depends on whether minimizing error or maximizing variance explanation is the priority.

🛠️ Technologies Used
Python
Pandas
NumPy
Scikit-learn
Matplotlib / Seaborn

📂 Repository Structure
├── dataset/
│   └── data.csv
├── notebook/
│   └── regression_analysis.ipynb
├── README.md

👤 Author
Abhinandan Khot
BCA – Semester 1
Machine Learning Project
