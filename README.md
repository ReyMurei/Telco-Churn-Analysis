# Telco Customer Churn Analysis
### Customer Behaviour & Business Performance | Google Sheets

## Project Overview

Customer churn is a major challenge for telecommunications businesses because losing customers affects recurring revenue and long-term business performance.

This project analyses customer data from a telecommunications company to identify patterns associated with customer churn, understand which customer segments are more likely to leave, and develop data-driven recommendations to support customer retention.

The analysis goes beyond calculating the overall churn rate by exploring customer demographics, tenure, contract types, service subscriptions, payment methods, and monthly charges.

## Business Problem

The business needed to better understand:

- How many customers were leaving the company?
- Which customer segments had the highest churn rates?
- What customer characteristics and behaviours were associated with churn?
- Which areas should the business prioritise to improve customer retention?

## Project Objectives

1. Assess and prepare the customer dataset for analysis.
2. Examine customer behaviour and identify patterns associated with churn.
3. Compare churn rates across different customer segments.
4. Develop descriptive customer risk profiles.
5. Translate findings into practical customer retention recommendations.

## Dataset Overview

| Description | Details |
|---|---|
| Total records | 7,043 customers |
| Total attributes | 21 |
| Unit of analysis | Individual customer |
| Analysis tool | Google Sheets |
| Analysis approach | Descriptive and exploratory analysis |

## Analytical Process

### 1. Data Understanding and Quality Assessment

- Examined the dataset structure, variables, and data types.
- Checked for missing values and duplicate customer records.
- Investigated inconsistencies and invalid values.
- Identified 11 missing values in the `TotalCharges` column, all belonging to customers with zero months of tenure.
- Confirmed that there were no duplicate customer IDs.

### 2. Data Cleaning and Preparation

- Addressed missing `TotalCharges` values.
- Corrected data types to support accurate calculations.
- Created a binary churn indicator for analysis.
- Developed tenure and monthly charge categories using quartiles and median values.
- Prepared the dataset for customer segmentation and comparison.

### 3. Exploratory Data Analysis

Investigated customer churn across:

- Demographics and account characteristics.
- Customer tenure and contract types.
- Monthly charges and revenue patterns.
- Internet services and additional subscriptions.
- Payment methods and billing preferences.

### 4. Customer Segmentation and Risk Profiling

Developed three descriptive customer profiles based on observed churn patterns:

- **Uncommitted Newcomer:** Customers in the early stages of their relationship with the business, particularly those on month-to-month contracts.
- **Settled but Uncommitted:** Customers with longer tenure who remain on month-to-month contracts.
- **Committed Core:** Customers on longer-term contracts with comparatively lower observed churn rates.

These profiles are descriptive and are not outputs of a predictive machine learning model.

## Key Findings

| Customer Segment | Churn Rate |
|---|---:|
| Overall customer base | 26.54% |
| Customers with 0–9 months tenure | 49.78% |
| Month-to-month contract customers | 42.71% |
| Electronic check users | 45.29% |
| Fiber optic customers | 41.89% |

Additional findings:

- Customers within their first nine months had a churn rate of 49.78%.
- Month-to-month customers with 0–9 months of tenure recorded a churn rate of 52.89%.
- Customers on two-year contracts recorded considerably lower churn rates.
- Customers using electronic checks had a churn rate of 45.29%.
- Customers who had churned had an average monthly charge of $74.44, compared with $61.27 for retained customers.

## Business Recommendations

Based on the findings, the analysis proposed the following opportunities:

1. Strengthen customer onboarding and engagement during the early months of the customer lifecycle.
2. Explore targeted initiatives to encourage eligible month-to-month customers to adopt longer-term contracts.
3. Investigate payment preferences and opportunities to encourage alternative payment methods.
4. Review the service experience of fiber optic customers.
5. Evaluate relevant service bundles to improve customer value.
6. Establish ongoing churn monitoring using customer characteristics and observed risk patterns.

## Tools and Skills

**Tool:** Google Sheets

**Skills demonstrated:**
- Data cleaning and preparation
- Data quality assessment
- Exploratory data analysis
- Descriptive statistics
- Customer segmentation
- Churn analysis
- Pattern and trend identification
- Business insight development
- Data-driven recommendations

## Limitations

The dataset represents a snapshot of customer information. Historical marketing campaigns, pricing changes, and customer retention interventions were not available.

Therefore, the analysis identifies associations and patterns rather than establishing the causes of customer churn. The proposed recommendations would require further investigation and monitoring to evaluate their effectiveness.

## Conclusion

This project demonstrates how customer data can be transformed into actionable business insights. By examining customer behaviour, identifying high-churn segments, and translating findings into practical recommendations, the analysis provides a foundation for more informed customer retention decisions.
