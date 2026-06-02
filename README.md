# Credit Wise - Loan Approval Prediction

Credit Wise is a machine learning project that predicts whether a loan application will be approved based on applicant, financial, and demographic features.

The project includes data cleaning, exploratory data analysis, feature engineering, model training, and evaluation using multiple classification algorithms.

## Project Overview

This notebook-based project works with a structured loan dataset containing features such as:

- Applicant and co-applicant income
- Employment and marital status
- Age, dependents, and credit score
- Existing loans, debt-to-income ratio, and savings
- Collateral value, loan amount, and loan term
- Property area, education level, gender, and employer category

The target variable is `LoanApproved`.

## Features

- Data preprocessing and missing value handling
- Exploratory data analysis with visualizations
- Correlation analysis
- Feature encoding for categorical variables
- Feature engineering
- Train/test split and scaling
- Model training and comparison
- Evaluation using accuracy, precision, recall, F1 score, and confusion matrix

## Models Used

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Gaussian Naive Bayes

## Results

The notebook evaluates multiple models and compares their performance on the test set.  
Based on the notebook outputs, Naive Bayes performs strongly on precision and overall balance for this dataset [file:1].

## Repository Structure

```text
.
├── credit_wise.ipynb
├── README.md
├── requirements.txt
└── loanapprovaldata.csv
```

## Dataset

The notebook reads from `loanapprovaldata.csv`.  
If you include the dataset in the repo, place it inside a `data/` folder and update the notebook path if needed [file:1].

## Installation

1. Clone the repository.
2. Create and activate a virtual environment.
3. Install dependencies:

```bash
pip install -r requirements.txt
```

## Usage

Open the notebook and run it step by step:

```bash
jupyter notebook credit_wise.ipynb
```

Or open it in JupyterLab / VS Code.

## Notes

- Missing numerical values are imputed using the mean.
- Missing categorical values are imputed using the most frequent value.
- Categorical variables are encoded before model training.
- Standard scaling is applied to the feature set before classification.

## Metrics

The notebook uses the following evaluation metrics:

- Accuracy
- Precision
- Recall
- F1 score
- Confusion matrix



## Author
KRISHNA YADAV
Data Scientist Intern
