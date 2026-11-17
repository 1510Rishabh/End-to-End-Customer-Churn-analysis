# Customer Churn: Key Insights

Summary of what the data shows. Based on 7,043 unique customers, of whom 1,869 churned (**26.54%**).

## 1. Contract type is the strongest signal

| Contract | Churn rate |
|---|---|
| Month-to-month | 42.7% |
| One year | 11.3% |
| Two year | 2.8% |

Month-to-month customers are 55% of the base but account for **1,655 of 1,869 churned customers (about 88%)**.

## 2. The first months are the riskiest

| Tenure | Churn rate |
|---|---|
| 0 to 6 months | 52.9% |
| 6 to 12 months | 35.9% |
| 12+ months | 17.1% |

The median tenure of churned customers is 10 months, versus 38 months for retained customers.

## 3. Service and billing patterns

| Factor | Higher churn | Lower churn |
|---|---|---|
| Internet service | Fiber optic: 41.9% | DSL: 19.0% |
| Payment method | Electronic check: about 45% | Other methods: about 15 to 20% |
| Online security | No: 41.8% | Yes: 14.6% |
| Tech support | No: 41.6% | Yes: 15.2% |
| Billing | Paperless: 33.6% | Paper: 16.3% |
| Senior citizen | Yes: 41.7% | No: 23.6% |
| Partner | No: 33.0% | Yes: 19.7% |

## 4. Revenue impact

- Churned customers pay more on average: about **$74 per month vs $61** for retained customers.
- Churned customers account for roughly **$139K of $456K in total monthly charges (about 30%)**.

## Recommendations

1. **Move customers to longer contracts.** Offer discounts or perks for switching from month-to-month to a one-year plan.
2. **Support new customers.** Run onboarding calls and check-ins during the first 6 months.
3. **Review fiber optic plans.** Check pricing and service quality, as this group churns at more than twice the DSL rate.
4. **Promote automatic payments** to move customers off electronic checks.
5. **Bundle online security and tech support** with new internet plans, since customers with them churn far less.

## Notes and Limitations

- These are correlations, not proven causes. For example, customers with security and support add-ons may also be more engaged to begin with.
- Figures were calculated after cleaning duplicates, inconsistent labels and missing values in `telco_churn_unclean.csv`.
- The dataset has no information on why customers left (price, competitor offers, service issues), so the recommendations are hypotheses to test.
