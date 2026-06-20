# Movie Box Office Revenue Prediction

## Overview
This project applies machine learning (Random Forest) to predict global box office revenue based on the TMDb Movie Dataset (Kaggle). Key features include budget, franchise status, runtime, genre popularity, and release year.

## Key Findings
- Budget shows the strongest correlation with revenue (**R² = 0.57**).
- Adventure and Sci-Fi genres generate the highest average revenue.
- Franchise films earn ~1.5x more than standalone movies.

## Model Performance
- **MAE**: $45.3M
- **RMSE**: $102.2M
- **R²**: 0.61
- **Accuracy (within 30% error margin)**: 53.88%

## Technical Stack
- Python (Pandas, NumPy, Matplotlib)
- Scikit-learn (Random Forest)
- Log-transformation & Feature Engineering

## Report
The full project report with complete methodology and results is available in this repository:  
**[STAT1016_Group_Project_Report.pdf](./STAT1016_Group_Project_Report.pdf)**

> *Note: Source code is not included in this repository due to academic group project policy. However, all preprocessing steps, feature engineering logic, and modeling details are thoroughly documented in the report.*
