# Prodigy_ML_Task1
# Linear Regression Model for House Price Prediction  
Prodigy InfoTech – Machine Learning Internship (Task 1)

This project was completed as part of my Machine Learning Internship at **Prodigy InfoTech**.  
The objective of this task was to build and train a **Linear Regression model** capable of predicting **house prices** based on key property features such as square footage, number of bedrooms, and number of bathrooms.

By applying regression techniques on real-world housing data, the project demonstrates how machine learning can be effectively used for **price estimation** and **market trend analysis** in the real estate domain.

---

## Project Overview

### Objective
To develop a **predictive model** that estimates house prices using numerical and categorical property features, enabling data-driven insights into housing market trends.

### Dataset
- **Name:** House Prices – Advanced Regression Techniques  
- **Source:** [Kaggle](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)  
- **Description:**  
  The dataset contains detailed information about residential properties, including structural, locational, and quality-related attributes. These features provide a solid basis for predicting property values using regression-based machine learning algorithms.

---

## Key Steps

1. **Data Collection:**  
   The dataset was obtained from Kaggle and loaded into the workspace using Pandas for data analysis and manipulation.

2. **Data Preprocessing:**  
   - Handled missing values and outliers to ensure data consistency.  
   - Converted categorical variables into numerical form using one-hot encoding.  
   - Scaled and normalized features for optimal model performance.  

3. **Feature Selection:**  
   - Selected key predictors such as square footage, number of bedrooms, and number of bathrooms.  
   - Analyzed feature importance to understand the impact of each variable on house prices.  

4. **Model Development:**  
   - Implemented a **Linear Regression model** using **Scikit-learn**.  
   - Split the dataset into training and testing sets to evaluate performance.  
   - Trained the model and optimized parameters for better predictive accuracy.  

5. **Model Evaluation:**  
   - Evaluated the model using metrics such as **Mean Absolute Error (MAE)**, **Mean Squared Error (MSE)**, and **R² Score**.  
   - Visualized predicted vs actual prices to validate model effectiveness.  

---

## Technologies Used
- Programming Language: **Python**  
- Libraries and Tools:  
  - Pandas  
  - NumPy  
  - Scikit-learn  
  - Matplotlib  
  - Seaborn  

---

## Results and Insights
- The Linear Regression model effectively captured the relationship between key housing features and sale price.  
- The model achieved a strong **R² score**, indicating a good fit for the dataset.  
- Visualization of residuals confirmed that predictions were unbiased and followed expected patterns.  
- Key finding: **Square footage** had the strongest correlation with sale price, followed by the number of bedrooms and bathrooms.  

| Metric | Value (Example) |
|--------|-----------------|
| Mean Absolute Error (MAE) | 21000.45 |
| Mean Squared Error (MSE) | 8.12e+08 |
| R² Score | 0.87 |

---

## Skills and Learning Outcomes
- Strengthened understanding of **supervised learning** and **regression algorithms**.  
- Gained experience in **data cleaning**, **feature engineering**, and **model evaluation**.  
- Developed practical knowledge of using **Scikit-learn** for implementing regression models.  
- Enhanced ability to interpret model performance and extract actionable insights from data.  

---

## Applications
- Real estate price forecasting  
- Property valuation systems  
- Market analysis for housing demand  
- Decision support for buyers and sellers  

---

## Author
Tsehaye Araya Hailemariam
Machine Learning Intern – Prodigy InfoTech  

Email: tsehayeresearch1@gmail.com
LinkedIn: www.linkedin.com/in/tsehaye-hailemariamm-aa128b378 

---

## License
This project is licensed under the **MIT License**.  
You are free to use, modify, and distribute this project under the license terms.

---

"Applying data-driven insights to understand and predict housing market trends."
