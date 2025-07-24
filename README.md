# Credit-Risk-Analysis

# Credit Risk Analysis Dashboard – Default of Credit Card Clients

## Overview

This BI project analyzes credit card default behavior using the "UCI Default of Credit Card Clients Dataset" (via Kaggle). The analysis was performed in Power BI and explores the relationship between customer attributes and default risk, helping companies understand behavioral and demographic patterns linked to credit defaults.

The resulting dashboard and report offer insights into payment behavior, credit limits, education level, marital status, and gender, all visualized with interactive elements and summarized in a report format.

---

## Key Business Questions

- How do marital status, education level, and gender influence credit default risk?
- Do credit limits differ significantly between defaulters and non-defaulters?
- What payment behavior patterns can be seen among defaulters vs. non-defaulters?

---

## Dataset

*Source*: [Kaggle - Default of Credit Card Clients Dataset](https://www.kaggle.com/datasets/uciml/default-of-credit-card-clients-dataset)

*Summary*:
- 30,000 credit card clients from Taiwan
- Variables include demographic info, past payment history (6 months), and default status
- Target variable: `default.payment.next.month` (1 = default, 0 = no default)

---

## Tools Used

- Power BI Desktop: for dashboard creation and DAX calculations
- Excel: for initial data formatting and upload
- DAX Measures: used to calculate default rates, averages, and category summaries

---

## Dashboard Insights & Highlights

### 1. Clients by Marital Status
- Married clients had a lower default rate (20.8%) than single clients (23.2%).
- Clients categorized as “Other” or “Unknown” showed more variance and may benefit from deeper segmentation.

### 2. Clients by Education Level
- Level 2 (likely mid-education) was the largest group and had a 24% default rate.
- Levels 4 and 5 had the lowest default rates (6%), while Level 6 and above showed higher risk again.

### 3. Clients by Gender
- Females had a lower default rate (20.78%) compared to males (24.17%).
- Gender-based financial behavior and risk tolerance may contribute to the difference.

### 4. Credit Limits Behavior
- Non-defaulters had a significantly higher average credit limit ($178K vs $130K).
- This may reflect creditworthiness scoring based on past repayment behavior.

### 5. Monthly Payment Behavior
- Non-defaulters maintained consistently early payments (negative values).
- Defaulters were often late, but showed a gradual improvement over the months.

---

## Files Included

| File | Description |
|------|-------------|
| `/Dashboards/Credit Risk Visualization Dashboard.pbix` | Power BI file |
| `/Images/Dashboard_overview.png` | Screenshots of visuals |
| `/Reports/Credit Risk Visualization Report.pdf` | Summary report explaining key insights |

---

## How to Use

1. Clone this repository.
2. Open the `.pbix` file in Power BI Desktop.
3. Explore insights interactively using filters and slicers.
4. (Optional) Read the full stakeholder report in `/reports/`.

---

## Contact

Name: Maria Agualimpia  
Email Address: mariaagualimpia24@gmail.com  
LinkedIn: (https://www.linkedin.com/in/maria-agualimpia-11a535129/)
