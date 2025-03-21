Financial Risk Analysis

Overview

This project analyzes financial risk using Tableau by exploring key factors such as credit score, loan amount, loan status, and default rates. The goal is to identify trends, outliers, and potential risk factors that influence loan defaults.

Dataset

The dataset contains loan-related details such as:

- Loan ID
- Credit Score
- Loan Amount
- Loan Purpose
- Loan Status (Defaulted, Fully Paid, Active, etc.)
- Income
  
Data Preparation

Data Cleaning
- Handled missing values in Income (replaced with median)
- Removed outliers in Loan Amount (capped at $1M)
- Filtered Credit Score range (500-850)

Feature Engineering
- Created categories for Loan Purpose
- Converted Loan Status into a numerical format

Visualizations & Insights

Credit Score vs. Loan Amount (Scatter Plot)
- Showed the relationship between credit scores and loan amounts.
- Identified potential risk zones for high loan amounts with low credit scores.

Loan Default Rate by Credit Score (Bar Chart)
- Revealed higher default rates in lower credit score brackets.
- Suggested risk mitigation strategies for lenders.

Loan Purpose Breakdown (Pie Chart/Bar Chart)
- Analyzed the distribution of loan purposes.
- Identified high-risk categories.

Loan Amount Distribution (Box Plot)
- Highlighted loan amount variations and outliers.
- Provided insights into lending trends.

Key Findings
- Low credit scores significantly increase default risk.
- Certain loan purposes have higher default rates.
- Loan amounts above a certain threshold correlate with increased defaults.
- Income level plays a role in loan approval but is not the sole determinant of default risk.

Tools Used
- Tableau (Data Cleaning & Visualization)
- Excel/Google Sheets (Initial Data Review)

Next Steps

- Apply predictive modeling to forecast loan defaults.
- Further segment data by demographics for deeper insights.
- Optimize lending decisions using advanced analytics.

This project showcases expertise in financial data analysis, risk assessment, and interactive visualization using Tableau.

Feel free to reach out for insights, collaborations, or improvements!
