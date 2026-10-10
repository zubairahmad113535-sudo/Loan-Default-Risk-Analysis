
# Loan Default Risk Analysis

## 📊 Project Overview

This project analyzes loan application data to identify customer segments with a higher risk of loan default and to help the credit team identify applications that may require manual review.

The project combines *Python for data analysis and feature engineering* with *Power BI for interactive business visualization*.

---

## 🎯 Business Problem

The main business questions are:

- Which customer segments have the highest loan default rates?
- What factors are associated with higher default risk?
- Which loan applications should the credit team manually review?
- How can data analysis support better credit-risk decisions?

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Power BI
- DAX
- GitHub

---

## 🔎 Project Workflow

1. Loaded and explored the loan application dataset.
2. Cleaned and prepared the data using Python.
3. Renamed columns for easier analysis.
4. Created customer segments using age and income.
5. Calculated loan-to-income ratios.
6. Created credit score groups.
7. Analyzed default rates across different customer segments.
8. Developed a ReviewScore to identify potentially risky applications.
9. Created Manual Review and High Priority Review categories.
10. Exported the prepared dataset for Power BI.
11. Built an interactive Power BI dashboard to communicate the findings.

---

## 📈 Key Findings

### Overall Default Rate

- *Default:* 11.61%
- *Non-Default:* 88.38%

### Default Rate by Employment Type

- *Unemployed:* 13.55%
- *Part-time:* 11.96%
- *Self-employed:* 11.46%
- *Full-time:* 9.40%

### Default Rate by Age Group

- *18–25:* 20.70%
- *26–35:* 16.07%
- *36–45:* 11.53%
- *46–55:* 8.44%
- *57+:* 5.50%

The analysis shows that younger applicants had higher observed default rates in this dataset.

### Default Rate by Income Group

- *Low Income:* 17.38%
- *Lower-Middle Income:* 10.54%
- *Upper-Middle Income:* 9.51%
- *High Income:* 9.02%

---

## 🚨 Manual Review Analysis

A ReviewScore was created using several risk-related customer characteristics.

The observed default rate increased as the ReviewScore increased:

| Review Score | Default Rate |
|--------------|--------------|
| 0 | 7.00% |
| 1 | 9.83% |
| 2 | 14.70% |
| 3 | 22.14% |
| 4 | 30.50% |
| 5 | 42.60% |

Applications were categorized into:

- *Standard*
- *Manual Review*
- *High Priority Review*

This scoring approach helps prioritize applications that may deserve additional attention from the credit team.

---

## 📊 Power BI Dashboard

The prepared dataset was imported into Power BI to create an interactive dashboard.

The dashboard focuses on:

- Overall default rate
- Default rate by customer segment
- Employment type
- Age group
- Income group
- Loan purpose
- Credit score
- Review categories
- Manual review applications

### Dashboard Preview

Add your Power BI dashboard screenshot here.

Example:

![Loan Default Risk Dashboard](power_bi_dashboard.png)

---

## 💡 Business Recommendations

Based on the analysis:

- Give additional attention to younger applicants with higher observed default rates.
- Closely review applications from lower-income segments.
- Prioritize applications with higher ReviewScores.
- Use the dashboard to identify customer segments requiring additional credit-risk assessment.
- Combine automated risk indicators with human review rather than relying on a single factor.

---

## 📁 Project Files

- Loan_Default_Risk_Analysis.ipynb — Python analysis and feature engineering
- loan_default_risk_powerbi.csv — Power BI-ready dataset
- power_bi_dashboard.png — Power BI dashboard screenshot
- README.md — Project documentation

---

## ⚠️ Disclaimer

This project is created for *learning and portfolio purposes*. The analysis identifies patterns in the dataset and should not be treated as a production credit-scoring system or a substitute for professional credit-risk assessment.

---

## 👤 Author

*Zubair Ahmad*

Aspiring Data Analyst | Python | SQL | Power BI | Excel

This project demonstrates my ability to transform raw data into meaningful business insights and interactive dashboards.
