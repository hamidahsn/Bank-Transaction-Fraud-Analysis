# Bank Transaction Fraud Analysis

Analysis of bank transaction fraud using data sampling and Looker Studio.

## Interactive Dashboard

[View Interactive Dashboard on Looker Studio](https://datastudio.google.com/reporting/bae8e8eb-7722-485c-a263-96116fc1e99e)

## Project Overview

This project analyzes bank transaction data to identify fraud patterns and provide insights into transaction risk.

The analysis uses a stratified sample of 250,000 transactions prepared from the original dataset.

## Dataset

The original dataset was obtained from Kaggle.

The data was prepared and sampled before being connected to Looker Studio for dashboard development.

The final analysis dataset contains:

- 250,000 transactions
- 13,813 fraud transactions
- 5.53% fraud rate
- $51.17 million total transaction amount
- $3.17 million fraud amount

## Sampling

Sampling was part of the data preparation process.

The project included learning and applying sampling concepts such as:

- Stratified sampling
- Quota sampling
- Other sampling approaches discussed during the project

A stratified sample of 250,000 transactions was used for the dashboard analysis.

## Dashboard Analysis

The dashboard provides several views of transaction fraud, including:

- Fraud overview
- Fraud trend over time
- Fraud by country
- Fraud by merchant category
- Fraud by city
- Fraud vs. non-fraud transactions
- Payment method analysis
- Device type analysis

## Key Findings

- From 250,000 transactions, 13,813 were identified as fraudulent, resulting in a fraud rate of 5.53%.
- The total transaction amount reached $51.17 million, with approximately $3.17 million associated with fraudulent transactions.
- Fraudulent transactions were most frequently observed in several merchant categories, particularly Crypto Exchange, Jewelry, and ATM Withdrawal.
- Fraud transactions were concentrated in several countries and cities, indicating geographic patterns in fraudulent activity.
- Fraud patterns can also be explored based on payment method and device type.

## Recommendations

- Strengthen fraud detection and monitoring for high-risk merchant categories, particularly Crypto Exchange, Jewelry, and ATM Withdrawal.
- Increase transaction monitoring in geographic areas with high concentrations of fraudulent transactions.
- Use transaction patterns across merchant category, location, payment method, and device type as supporting indicators for fraud monitoring.

## Tools

- Looker Studio
- Microsoft Excel
- Sampling Techniques
- Data Visualization

## Project Structure

```text
Bank Transaction Fraud Analysis/
│
├── README.md
│
├── dashboard/
│   └── Hamida_Bank_Transactions_Fraud.pdf
│
├── data/
│   └── README.md
│
└── images/
    └── dashboard_overview.png
