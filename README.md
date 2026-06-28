# Fraud Transaction Analysis

## Project Overview
This project analyses a synthetic fraud transaction dataset to identify key indicators of fraudulent transactions and build a benchmark fraud classification model.

The goal is to understand which variables are most strongly associated with fraud and how they can support fraud detection decisions.

## Dataset
The dataset contains 10,000 synthetic transactions, including:
- Fraud / non-fraud label
- Transaction amount
- Device risk score
- IP risk score
- Country
- Hour
- Transaction type
- Merchant category

This dataset is synthetic and used for educational and portfolio purposes only.

## Methods Used
- Descriptive analysis
- Categorical fraud-rate analysis
- Chi-square tests
- Welch t-tests
- ANOVA
- Targeted post-ANOVA follow-up tests
- Random Forest classification model
- Confusion matrix and precision/recall evaluation

## Key Findings
- Fraud transactions had higher average transaction amount, device risk score and IP risk score.
- Country and hour bucket were significantly associated with fraud.
- NG transactions showed higher average device and IP risk scores than other countries overall.
- Night transactions showed higher average device and IP risk scores than other hour buckets overall.
- Device risk score and IP risk score were the strongest model drivers.

## Tools Used
- Python
- pandas
- NumPy
- SciPy
- scikit-learn
- matplotlib
- PowerPoint

## Files
- `Fraud_Analysis_Su.ipynb` — Python notebook
- `Fraud_Analysis_Su_pdf` — PDF version of presentation
- `synthetic_fraud_dataset.xlsx/` — Dataset

## Limitations
This project uses a synthetic dataset. Real-world fraud data may be noisier and may require stronger validation, leakage checks and monitoring over time.
