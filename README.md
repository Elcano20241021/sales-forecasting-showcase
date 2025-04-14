# sales-forecasting-showcase
This repository summarizes a confidential project developed as part of the **Business Cases with Data Science** course at **NOVA IMS (2024/2025)**.

We built a robust pipeline to forecast **monthly sales** across multiple product groups using **machine learning techniques** and **domain-specific features**.

> Due to company data sensitivity, the full code and dataset are not shared publicly.  
> If you'd like to know more, feel free to reach out on [LinkedIn](www.linkedin.com/in/elcanogaspar).

---

## Project Highlights

### Objective
Forecast future sales for a product catalog based on:
- Historical sales volume and seasonality
- Rolling averages, lags, and volatility indicators
- External economic indicators (e.g., production and export data)

---

## Techniques Used

- **Time Series Modeling:**
  - Expanding Window Cross-Validation
  - XGBoost Regressor
  - Prophet

- **Feature Engineering:**
  - Lag variables, rolling mean/std
  - “Month Since First Sale”
  - Group-specific log transformations
  - Time-based features (lag 1, 3, 6, rolling std, mean, 6, 12)

- **Model Tuning & Validation:**
  - Bayesian Optimization
  - RMSE and MAPE evaluation
  - Holdout test vs cross-validated folds

---

## Tools & Stack

- Python (pandas, numpy, XGBoost, CatBoost, Prophet)
- Scikit-learn, optuna
- Jupyter Notebook
- VS Code, GitHub

---

> This is a professional showcase of a private project. Code walkthrough and demo available upon request.
