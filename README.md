# Predicting the Co-Use of Marijuana and Alcohol Among U.S. Adolescents
Master's thesis, NYU MPH in Biostatistics (2026). Advisor: Dr. Shu (Violet) Xu

## Data
2023 National Survey on Drug Use and Health (NSDUH), youth sample aged 12-17.

## Methods
- Survey-weighted logistic regression (svyglm, quasibinomial) to identify predictors of co-use
- XGBoost model compared against logistic regression using AUC, sensitivity, and specificity
- Final analytic sample: 7,889 adolescents after listwise deletion

## Key Findings
- Peer and parental disapproval of marijuana were strongly protective (aOR 0.08)
- High perceived peer marijuana use and suicidal ideation increased odds of co-use
- Logistic regression and XGBoost showed comparable discrimination (AUC 0.928 vs. 0.921)

## Files
- 'FINAL_THESIS_RM.RMD' = full data cleaning, modeling, and evaluation code
