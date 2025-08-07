# Heart Failure Mortality Risk Analysis

This data science project explores early mortality risk factors in heart failure patients using clinical records. By combining exploratory data analysis with supervised machine learning, we identify key predictors of death and evaluate the performance of classification models. The project is based on a real-world dataset and includes visualizations, statistical insights, and predictive modeling.

## Project Structure
```bash
├── codes/
│ └── Heart_Failure_Analysis.ipynb
├── data/
│ └── heart_failure_clinical_records_dataset.csv
├── figures/ # Generated graphs and plots
│ ├── Q1_Age_vs_DeathEvent.png
│ ├── Q1_Sex_vs_DeathEvent.png
│ ├── Q2_anaemia_vs_DeathEvent.png
│ ├── Q2_diabetes_vs_DeathEvent.png
│ ├── Q2_high_blood_pressure_vs_DeathEvent.png
│ ├── Q2_smoking_vs_DeathEvent.png
│ ├── Q3_ejection_fraction_vs_DeathEvent.png
│ ├── Q3_serum_creatinine_vs_DeathEvent.png
│ ├── Q3_serum_sodium_vs_DeathEvent.png
│ ├── Q3_platelets_vs_DeathEvent.png
│ ├── Q3_creatinine_phosphokinase_vs_DeathEvent.png
│ ├── Q4_Logistic_Regression_Confusion_Matrix.png
│ ├── Q4_Gradient_Boosting_Confusion_Matrix.png
│ └── Q4_GradientBoosting_FeatureImportance.png
├── report/
│ └── Individual_Project_Heart_Failure_Report.pdf
└── README.md
```

## Dataset

- **Source**: [Kaggle - Heart Failure Clinical Records Dataset](https://www.kaggle.com/datasets/andrewmvd/heart-failure-clinical-data)
- **Size**: 299 samples, 13 features
- **Target Variable**: `DEATH_EVENT` (1 = died, 0 = survived)

Features include demographic info (age, sex), clinical measurements (serum creatinine, sodium, ejection fraction), and lifestyle/comorbidities (smoking, diabetes, anaemia).

## Research Questions

1. How do demographic factors like age and sex affect mortality?
2. What impact do comorbidities and lifestyle habits have on death rates?
3. Which lab biomarkers are most associated with early mortality?
4. Can machine learning models predict patient survival effectively?

## Visualizations & Analysis

All visualizations answering the above questions are implemented and rendered in the Jupyter Notebook:

**[codes/Heart_Failure_Analysis.ipynb](codes/Heart_Failure_Analysis.ipynb)**

This notebook includes:
- Data cleaning and standardization
- EDA (boxplots, bar charts)
- Feature evaluation
- Classification models (Logistic Regression, Gradient Boosting)
- Model performance metrics and feature importance

## Tools & Libraries

- Python 3.9+
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## How to Run

1. Clone this repo
2. Navigate to the project directory
3. Launch Jupyter Notebook
4. Open `codes/Heart_Failure_Analysis.ipynb`

```bash
pip install
jupyter notebook
```

## Report
The final written report following an IEEE-style structure is available at:

```bash
Heart_Failure_Report.pdf
```
It contains detailed findings, figures, discussion, and references.

References
Davide Chicco, Heart Failure Clinical Data, Kaggle

Scikit-learn documentation

WHO Heart Failure Factsheet

