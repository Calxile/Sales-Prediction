# Sales Prediction — Rossmann Store Sales

A machine learning project built as part of the **SparkIIT Data Science** internship program.  
This project predicts the number of orders for Rossmann stores using exploratory data analysis and regression modeling.

---

## Project Structure

```
Sales-Prediction/
├── Datasets/
│   └── rossmann-store-sales/
│       ├── train.csv
│       ├── test.csv
│       ├── store.csv
│       └── sample_submission.csv
├── Projects/
│   └── No_of_Orders.ipynb
└── Orders Report.pdf
```

---

## Dataset

**Rossmann Store Sales** — sourced from Kaggle  
Contains historical sales data for 1,115 Rossmann drug stores across Germany.

| File | Description |
|------|-------------|
| `train.csv` | Historical sales data with features |
| `test.csv` | Test set for prediction |
| `store.csv` | Supplemental store metadata |
| `sample_submission.csv` | Submission format |

---

## Tools & Libraries

- **Python** — Core programming language
- **Pandas & NumPy** — Data manipulation and analysis
- **Matplotlib & Seaborn** — Data visualization
- **Scikit-learn** — Machine learning modeling

---

## Methodology

1. **Data Loading** — Loaded Rossmann store sales dataset
2. **Exploratory Data Analysis (EDA)** — Distribution plots, correlation heatmaps, outlier detection
3. **Preprocessing** — Feature scaling using StandardScaler, train-test split (80/20)
4. **Model Training** — Linear Regression baseline model
5. **Evaluation** — R² Score and RMSE metrics

---

## Results

| Metric | Value |
|--------|-------|
| R² Score | 0.60 |
| RMSE | ~0.73 (~$73,000) |
| Train Samples | 16,512 |
| Test Samples | 4,128 |

---

## Key Findings

- **Median Income (MedInc)** is the strongest predictor with a Pearson correlation of **0.69**
- The model performs well for mid-range prices but struggles with high-value properties
- Linear Regression serves as a solid interpretable baseline

---

## Future Improvements

- Explore ensemble methods like **Random Forest** or **XGBoost** to improve R² beyond 0.80
- Apply feature engineering to capture non-linear relationships
- Hyperparameter tuning for improved accuracy

---

## Author

**Ayeshkant Ray**  
SparkIIT Data Science Program — April 2026
