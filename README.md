# Telco Customer Churn: Multivariate Exploratory Data Analysis

## Project Overview
This project performs an end-to-end exploratory data analysis (EDA) on a dataset of over 7,000 customers to identify critical behavioral and demographic risk factors contributing to attrition. By leveraging statistical visualization, the study quantifies key churn drivers to support data-driven retention strategies in the telecommunications sector.

## Key Technical Insights
The analysis revealed several statistically significant drivers of churn:

* **Contractual Friction:** Customers on **Month-to-Month contracts** exhibit a high churn rate (approx. 42.7%), whereas those on **Two-Year contracts** show the highest loyalty (approx. 2.8% churn).
* **Payment Gateway Volatility:** A significant correlation exists between payment methods and attrition. **Electronic Check users** represent a disproportionate 45% of total churned customers, suggesting potential friction in the digital billing experience.
* **Early-Tenure Risk:** Attrition is most aggressive within the first year of service (approx. 50% churn rate), identifying the "onboarding" phase as the most critical period for customer success intervention.
* **Demographic Vulnerability:** **Senior Citizens** churn at a higher rate compared to younger demographics, pointing toward a need for specialized support or accessibility-focused retention programs.

## Analysis Workflow
1.  **Data Preprocessing:** Handled missing values in `TotalCharges`, corrected data types, and transformed categorical encoding (e.g., mapping binary `SeniorCitizen` values for improved interpretability).
2.  **Univariate Analysis:** Evaluated the distribution of the target variable (`Churn`) to establish a baseline attrition rate of 26.54%.
3.  **Bivariate Exploration:** Leveraged **Matplotlib** and **Seaborn** to visualize the relationship between churn and various features including Gender, Tenure, Contract types, and Internet Services.
4.  **Service Impact Study:** Analyzed how peripheral services like Tech Support and Online Security influence customer stay-rates.

## Tools & Libraries Used
* **Python 3.x**
* **Pandas:** Data manipulation and feature engineering.
* **Matplotlib & Seaborn:** Multivariate statistical visualization.
* **Jupyter Notebook:** End-to-end documentation of the analytical process.

## Strategic Recommendations
* **Incentivize Stability:** Prioritize the migration of month-to-month customers to long-term annual contracts.
* **Digital Payment Optimization:** Investigate the Electronic Check user experience to resolve potential technical or transparency issues.
* **High-Touch Onboarding:** Implement targeted engagement programs within the first 12 months to mitigate high early-tenure churn.

---
**Author- Aryan N K Arya**
