Credit Card Fraud Detection Dashboard (Excel)

This project demonstrates an interactive Excel dashboard to analyze credit card transactions and identify fraud patterns. Using a balanced dataset (equal number of fraud and legitimate transactions), the dashboard provides insights into fraud trends by transaction amount and type. It’s designed to be both informative and visually intuitive, helping users quickly understand key fraud metrics.

Dataset

Name: Credit Card Transactions (Balanced)

Features used:

Amount: Transaction amount

FraudFlag: Fraud (1) / Legit (0)

AmountBin: Categorized transaction ranges (Low, Medium, High, Very High)

Class: Transaction type (if available)

Note: The dataset is balanced for demonstration purposes, meaning fraud and legitimate cases are equally represented.

Steps Performed
1. Data Cleaning

Removed null values and duplicates to ensure clean analysis.

Created Amount Bins (Low, Medium, High, Very High) for better categorization.

2. KPI Calculations

Key performance indicators were calculated using Excel formulas:

Total Transactions: COUNTA()

Fraud %: COUNTIF(FraudFlag,"Fraud") / COUNTA(FraudFlag)

Average Fraud Amount: AVERAGEIF(FraudFlag,"Fraud",Amount)

Average Legit Amount: AVERAGEIF(FraudFlag,"Legit",Amount)

3. PivotTable Analysis

PivotTables were used to summarize and explore the data:

Fraud vs Legit distribution across Amount Bins

Fraud rate across different transaction types (Class)

4. Visualization

Charts were created to make insights visually clear and interactive:

100% Stacked Column Chart: Fraud vs Legit by Amount Bin

Bar Chart: Average transaction amount (Fraud vs Legit)

Pie/Bar Chart: Fraud share by Class

5. Dashboard Layout

The dashboard is designed for easy interpretation:

KPI Cards (Top):

Total Transactions

Fraud %

Avg Fraud Amount

Avg Legit Amount

Charts:

Chart 1: 100% Stacked Column → Fraud vs Legit by Amount Bin

Chart 2: Bar Chart → Avg Transaction Amount (Fraud vs Legit)

Chart 3: Pie/Bar → Fraud share by Class

Interactive Slicers: Filter by AmountBin or Class for dynamic exploration

Professional formatting ensures clarity and usability

Key Takeaways

Higher transaction amounts can show different fraud trends compared to lower amounts.

Certain transaction types may have a higher incidence of fraud, which can inform risk monitoring.

Interactive filters allow users to drill down and explore patterns in detail.
