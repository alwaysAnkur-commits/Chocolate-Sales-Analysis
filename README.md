# Chocolate-Sales-Analysis
Aim to analyse data and retrieve information in the form of business insights as well as create easy to understand dashboards.

## Overview
This project analyzes international chocolate sales transaction data using Microsoft Excel to identify revenue patterns and compare market performance across countries. The focus of the analysis is on data validation, aggregation and deriving meaningful business insights from raw sales data.

---

## Dataset
The dataset consists of transactional sales records containing:

- Sales person
- Country
- Product
- Date
- Revenue amount
- Boxes shipped

The data represents chocolate sales across multiple countries and customer segments.

---

## Tools Used
- Microsoft Excel
- Excel Tables and structured references
- Formulas and functions:
  - `COUNTIF`, `COUNTA`, `SUMIF`
  - `UNIQUE`
  - `SUBSTITUTE`
- Sorting and basic tabular analysis

---

## Data Preparation
The dataset was reviewed and prepared prior to analysis:

- Verified that no null or blank values were present
- Ensured country values were consistent using dynamic arrays
- Revenue values were converted from text to numeric format due to embedded currency symbols and delimiters
- Transaction counts and revenue totals were cross-validated to confirm accuracy

---

## Analysis Summary

### Country-Level Transactions and Revenue
Sales transactions and total revenue were aggregated at the country level to compare market activity and value contribution.

| Country        | Transactions | Revenue |
|----------------|--------------|---------|
| Australia      | 205          | 1,137,367 |
| UK             | 178          | 1,051,792 |
| India          | 184          | 1,045,800 |
| USA            | 179          | 1,035,349 |
| Canada         | 175          |   962,899 |
| New Zealand    | 173          |   950,418 |

---

### Revenue Efficiency Comparison
A comparison of revenue generated per transaction highlights differences in market behavior across countries.

| Country     | Revenue per Transaction |
|-------------|------------------------|
| UK          | 5,908.94 |
| USA         | 5,784.07 |
| India       | 5,683.70 |
| Australia   | 5,548.13 |
| Canada      | 5,502.28 |
| New Zealand | 5,493.75 |

---

## Observations
- Countries contribute differently to overall business value despite similar transaction volumes.
- Australia generates the highest total revenue, driven by higher transaction frequency.
- The UK leads in revenue per transaction, indicating stronger value generation per sale.
- India shows high transaction activity with comparatively moderate revenue per transaction.
- Market performance varies between volume-driven and value-driven contributions.

---

## Repository Structure
- Excel workbook containing cleaned data and analysis
- README documentation

---

## Author
**Prep Ankur**  
Aspiring Data Analyst | Excel | Data Analysis | Business Insights
