# Customer Churn Analysis Dashboard (Power BI)

An end-to-end analysis of telecom customer churn: raw data cleaning in Power Query, KPI measures in DAX, and an interactive Power BI dashboard that shows who is leaving and why.

## Business Problem

A telecom company is losing customers and wants to know **which customers churn, when, and what they have in common**, so retention offers can be targeted instead of being sent to everyone.

## Key Findings

- **Contract type is the biggest driver.** Month-to-month customers churn at 42.7%, versus 11.3% on one-year and 2.8% on two-year contracts. Month-to-month contracts account for 1,655 of the 1,869 churned customers (about 88%).
- **New customers leave fastest.** Churn is 52.9% in the first 6 months, 35.9% at 6 to 12 months, and 17.1% after 12 months.
- **Fiber optic users churn more.** 41.9% churn, compared with 19.0% for DSL users.
- **Payment method matters.** Electronic check users churn at about 45%, against roughly 15% to 20% for other methods.
- **No online security means higher churn.** 41.8% churn without it, versus 14.6% with it.
- **Churned customers pay more.** Average monthly charge is about $74 for churned customers versus $61 for retained ones.

## Recommendations

1. Offer discounts or upgrades to move month-to-month customers onto longer contracts.
2. Run an onboarding and check-in program for customers in their first 6 months.
3. Investigate service quality and pricing for fiber optic plans.
4. Encourage automatic payment methods over electronic checks.
5. Bundle online security with new internet plans.

## Dashboard Features

- KPI cards for total customers, churn rate and churned customers
- Churn by contract type, tenure band and customer segment
- Retention overview with a normal vs high-risk split of retained customers
- Charges analysis by customer type and online services

## Tools Used

Power BI Desktop, Power Query, DAX

