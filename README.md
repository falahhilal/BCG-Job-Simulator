# PowerCo Customer Churn Analysis

Data science case study completed as part of the **BCG X Data Science Job Simulation** (via Forage). The client, PowerCo (a major gas & electricity utility), believed customers were churning primarily due to **price sensitivity**. This project tests that hypothesis end-to-end — from scoping the data with the client to delivering findings to stakeholders.

## Business Question

> Is price sensitivity the primary driver of customer churn, and if not, what is?

## Approach

Followed a 5-step data science methodology:

1. **Business understanding & problem framing** — defined the hypothesis to test, outlined the data needed from the client, and the techniques to investigate it
2. **EDA & data cleaning** — explored client and pricing datasets: data types, descriptive statistics, distributions
3. **Feature engineering** — built price-sensitivity proxies (off-peak price spread, Dec–Jan price difference, peak/off-peak gap), date-derived features (tenure, days to renewal), and consumption/margin ratios
4. **Modeling & evaluation** — trained a Random Forest classifier to predict churn, evaluated with precision/recall/F1 (not just accuracy, given ~10% churn base rate)
5. **Insights & recommendations** — synthesized findings into a stakeholder-ready executive summary

## Key Finding

**Price sensitivity is not the primary driver of churn.** Net margin and 12-month consumption patterns were stronger predictors. Price-related features ranked low in the model's feature importance — the client's assumption didn't hold up under testing.

## Acknowledgments

Case study provided by **BCG X** via **[Forage](https://www.theforage.com/)**.
