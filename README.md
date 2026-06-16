# Model Fitness — Customer Churn Analysis

## About the Project

A complete churn analysis for a fictional gym chain, aimed at predicting which customers are most likely to cancel in the following month and developing data-driven retention strategies.

## Project Structure

- **Step 1** — Data loading and inspection
- **Step 2** — Exploratory Data Analysis (EDA): descriptive statistics, histograms, and correlation matrix
- **Step 3** — Predictive modeling: Logistic Regression vs Random Forest
- **Step 4** — Customer clustering with K-Means (5 clusters)
- **Step 5** — Conclusions and retention recommendations

## Key Results

- Overall churn rate: **26%**
- Best model: **Logistic Regression** (Accuracy: 91.7% | Recall: 85.4%)
- Highest-risk clusters identified: clusters 2 and 3 (churn rates of 51.8% and 44.4%)
- Main churn predictors: remaining contract time, customer lifetime, and current visit frequency

## Tech Stack

- Python 3
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- SciPy

## How to Run

```bash
git clone https://github.com/msitta/model-fitness-churn-analysis.git
```

Open `churn_analysis_en.ipynb` in any Jupyter environment.

## Author

Marco Aurélio Martins Sitta
[LinkedIn](https://www.linkedin.com/in/seu-perfil) | [GitHub](https://github.com/msitta)