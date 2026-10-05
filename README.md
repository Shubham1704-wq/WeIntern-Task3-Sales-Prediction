# Task 3 – Sales Prediction Model
**WeIntern Pvt Ltd | Data Science Week 2 Internship**

## Project Overview
This repository contains a complete **Machine Learning pipeline** to predict Sales using the cleaned Superstore dataset.

Two models were built and compared:
- Linear Regression (Baseline)
- Random Forest Regressor (with Hyperparameter Tuning)

---

## Files Included

| File | Description |
|------|-------------|
| `Task3_Sales_Prediction_Model.ipynb` | Full ML pipeline notebook |
| `cleaned_superstore_sales.csv` | Cleaned dataset used for modeling |

---

## Full Pipeline

1. Feature Engineering  
   - Date components (Year, Month, Day of Week, Quarter)  
   - Shipping Delay  
   - Category Average Sales  

2. Train-Test Split (80/20)

3. Model Training  
   - Linear Regression  
   - Random Forest Regressor  

4. Evaluation Metrics  
   - RMSE  
   - MAE  
   - R² Score  

5. Feature Importance Analysis

6. Actual vs Predicted + Residuals Plot

7. Hyperparameter Tuning using `RandomizedSearchCV`

8. Business Interpretation & Limitations

---

## How to Run

1. Open `Task3_Sales_Prediction_Model.ipynb`
2. Make sure `cleaned_superstore_sales.csv` is uploaded
3. Run all cells in order (the tuning cell may take 1–2 minutes)

---

## Key Takeaways

- Random Forest significantly outperforms Linear Regression
- Top features driving sales: **Unit Price**, **Order Quantity**, **Category Average Sales**, and **Discount**
- The model can be used for order-level sales forecasting with good accuracy

---

**Complete end-to-end ML solution – ready for presentation.**
