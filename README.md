# Customer Churn Analysis – Power BI Dashboard

Interactive Power BI dashboard analysing why telecom customers leave,
built on 7,043 customers (26.5% churn rate).

## Business Question
Which customers are most likely to churn, and what drives it?

## Tools
Power BI, DAX, Power Query

## Dataset
Telco Customer Churn dataset (IBM sample data, available on Kaggle)

## What I Built
- KPI cards: total customers, churned customers, churn rate, avg tenure, avg monthly charges
- Slicers: gender, senior citizen, contract, internet service, payment method
- DAX measures, calculated columns (tenure segments, add-on count, billing type, churn segments)
- Churn driver ranking using Cramér's V
- Churn risk score with risk buckets

## Key Findings
- Month-to-month contracts churn at 42.7% vs 2.8% on two-year plans and make up 88.6% of churners
- Customers in their first 12 months churn at 47.4%
- Highest-risk segment: month-to-month + fiber optic + first year = 70.2% churn
- Electronic-check payers churn at 45.3% vs 15–19% for other payment methods
- Customers without Tech Support or Online Security churn at ~42% vs ~15%
- Highest risk-score band churned at 73.6% vs 7.2% in the lowest

## Recommendations
- Offer discounts to move month-to-month customers onto 1- or 2-year contracts
- Add extra onboarding and check-ins during the first 12 months
- Encourage automatic payment methods over electronic check
- Bundle Tech Support and Online Security for fiber optic customers

## Dashboard Preview
![Overview](images/overview.png)

## How to Open
Download the .pbix file and open it in Power BI Desktop.
Update the data source path to the CSV in the `data` folder.
