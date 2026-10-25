# Customer Churn Analysis and Prediction using Logistic Regression

**IDS Case Study | Data Analysis using R**
**Name:** Boyina Abhinav | **Roll No.:** 160124771032

## Overview
This case study analyzes telecom customer data to find the factors associated with customer churn and predicts whether a customer is likely to churn using Logistic Regression in R.

## Objectives
1. Analyze customer demographic and service-related factors associated with churn.
2. Clean, preprocess, and explore the customer churn dataset using R.
3. Identify patterns and factors that may influence customer churn.
4. Develop a Logistic Regression model to predict customer churn.

## Dataset
- **Name:** Telco Customer Churn (IBM sample dataset, also available on Kaggle)
- **Size:** 7,043 records and 21 columns (7,032 rows after removing 11 rows with a blank TotalCharges value)
- **Target variable:** Churn (Yes / No)

## Project Files
| File | Description |
|---|---|
| `IDS_Customer_Churn_Implementation.Rmd` | R Markdown file with the full analysis (code, output and interpretation) |
| `IDS_Customer_Churn_Case_Study.ipynb` | Notebook version of the same analysis |
| `WA_Fn-UseC_-Telco-Customer-Churn.csv` | Dataset |

## Methodology
Dataset → Data Cleaning → Preprocessing → EDA & Visualization → Logistic Regression → Model Evaluation

## Key Results
- Overall churn rate: 26.6% (1,869 of 7,032 customers)
- Train / test split: 70% / 30% (4,924 / 2,108 rows)
- Test accuracy: 0.814
- Precision: 0.670
- Recall: 0.591
- Specificity: 0.895
- F1 score: 0.628
- Significant predictors (p < 0.05): tenure, contract type (one year and two year), TotalCharges, paperless billing and electronic check payment

## How to Run
1. Install R and RStudio.
2. Keep the dataset file in the same folder as the `.Rmd` file.
3. Open `IDS_Customer_Churn_Implementation.Rmd` in RStudio and click **Knit**.
4. The required packages (tidyverse, caret, pROC, scales, car) install automatically if missing.

## Version Control
The work was uploaded in stages: dataset, R Markdown analysis, notebook, and final results. The commit history shows each stage.
