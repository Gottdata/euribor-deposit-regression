# Interest Rate Modeling: Linear Regression between Euribor and Bank Deposit Rates

## 📌 Objective

This project analyzes the relationship between the 3-month Euribor rate and the deposit rates offered by banks.  
The goal is to understand how market reference rates influence deposit pricing strategies, using linear regression and exploratory data analysis.

## 📊 Project Overview

The notebook includes the following steps:

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Correlation analysis
- Linear regression modeling
- Model evaluation using R², MAE, and RMSE
- Visualization of the fitted model
- Business interpretation of results

## 🔧 Tools Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## 📁 Data

The dataset includes monthly records of:
- **3M Euribor reference rates**
- **Bank deposit rates offered to clients**

📌 *Data was collected from the official website of the European Central Bank (ECB):*  
[https://www.ecb.europa.eu/home/html/index.en.html](https://www.ecb.europa.eu/home/html/index.en.html)

## 📈 Key Findings

- A strong linear relationship exists between Euribor and deposit rates historically.
- From mid-2022, this relationship weakened as deposit rates lagged behind the sharp increase in Euribor.
- The model achieved an R² of ~0.87, indicating good explanatory power.
- Higher RMSE compared to MAE suggests some larger deviations, mainly during periods of market instability.
- In recent months, the relationship appears to realign with the historical trend.

## 💡 Conclusion

This project demonstrates how predictive modeling can help understand pricing behavior in the banking sector.  
It highlights the value of combining data analysis with domain knowledge to support strategic decisions around interest rate sensitivity.

---

📂 This repository is part of my Data Science portfolio.  
Feel free to explore the code or connect with me on [LinkedIn](https://www.linkedin.com/in/paula-gottert/).
