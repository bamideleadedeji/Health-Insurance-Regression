# Health Insurance Cost Prediction: Linear Regression Analysis 

![Python](https://img.shields.io/badge/Language-Python-blue)
![Scikit-Learn](https://img.shields.io/badge/Library-Scikit--Learn-orange)
![Accuracy](https://img.shields.io/badge/R--Squared-0.99-green)

##  Project Overview
This project uses **Linear Regression** to predict individual medical insurance charges. By analyzing factors such as age, BMI, and smoking status, I developed a model that explains **99% of the variance** in insurance costs, providing a clear mathematical framework for risk-based pricing.

##  Data Engineering & Modeling
* **One-Hot Encoding:** Transformed categorical variables (Smoker status, Region) into numerical values using `pd.get_dummies` while avoiding the Dummy Variable Trap.
* **Algorithm:** Implemented Scikit-Learn's `LinearRegression` to identify the specific "weights" of health risk factors.

##  Business Insights (The Coefficients)
My model identified the exact cost drivers for insurance premiums:
1. **The Smoker Tax:** Being a smoker increases charges by approximately **$19,799**.
2. **The Aging Factor:** For every single year of age, the premium increases by **$248.64**.
3. **The BMI Impact:** Each point of BMI adds roughly **$95.21** to the annual cost.



##  Model Performance
* **R-Squared Score:** 0.99 (The model captures 99% of pricing logic).
* **Mean Absolute Error (MAE):** $806.51 (High precision in cost estimation).

##  Files in this Repo
* `insurance_regression.ipynb`: Complete code for encoding, training, and evaluation.
* `actual_vs_predicted.png`: Visualization confirming the model's accuracy.
