# Understanding Telco Customer Churn: Trends, Patterns and  Revenue impact
<img src="https://github.com/Micahnd/customer-churn-dashboard-excel/blob/main/customer-churn-all-customers.png" alt="Dashboard Overview" width="650">

*Fig 1: Customer Churn Overview: All customers*

<img src="https://github.com/Micahnd/customer-churn-dashboard-excel/blob/main/customer-churn-senior-citizen.png" alt="Dashboard Overview: Senior Citizens" width="650">

*Fig 2: Customer Churn Overview: Senior citizens*

<img src="https://github.com/Micahnd/customer-churn-dashboard-excel/blob/main/customer-churn-non-senior-citizens.png" alt="Dashboard Overview: Non-Senior Citizens" width="650">

*Fig 3: Customer Churn Overview: Non-Senior citizens*

## 📌 Project Overview
This project presents a **data-driven exploration of customer churn** for a fictional telecom company. Built entirely in **Microsoft Excel**, the dashboard is a practical tool to **understand customer behavior**, highlight **revenue risks** and guide **further business investigation**.

## 🎯 Business Context
Customer churn is one of the most pressing issues for subscription-based services like telecoms. It directly impacts revenue and often reflects deeper service or experience issues.

The goal here was not to model churn prediction but to **diagnose patterns and behaviors** of customers who churned using the **available structured data**.

## 🔍 Why Excel?
While tools like Python, SQL, and Power BI would offer automation and scalability, I chose Excel here for Accessibility, transparency and flexibilty.
Excel’s flexibility allowed for **step-by-step exploration** of churn behaviors while maintaining transparency in calculations, making it ideal for teams who might not be technical but still need insights.

## 📊 Key Findings

#### 1.  Senior Citizens High risk
- The senior customers have a higher churn rate (41%) than the general population and pay more monthly at ₦79.82 average.

#### 2. Tenure Impacts Retention
- Churn is **significantly higher in the first 12 months** of subscription.
- Customers with longer tenure (especially over 3 years) show **much lower churn rates**.
- This insight was visible in the main dashboard and across both filtered dashboards (senior and non-senior citizens), confirming tenure as a stable churn indicator.

#### 3. Revenue Risk in Customer Churn
- Churned customers had a **higher average monthly cost** (₦74.44) than those retained (₦61.31).
- ⚠️ This means the company is **losing its most valuable customers**, not just the most dissatisfied.
- This pattern is also held across both filterd dashboards showing it is not age specific though non-senior customers showed slightly more stability in monthly cost patterns.

#### 4. Living Situation Tells a Story
- Customers who live **alone**(No partner or dependents) are more likely to churn than those in shared living situations.
- This behavioral trend might reflect **less brand loyalty** or **higher price sensitivity** in single-user households.

#### 5. Churn by Payment Method
- **Electronic check** users have the highest churn rate overall, especially among **senior citizens** most of whom are seen to rely on this payment method.
- This suggests issues like **payment friction**, **digital literacy challenges** or **lack of trust in automated bills**.
- A review of the **electronic payment experience** especially for senior citizens may help reduce churn in this group.

#### 6. Add-on Services Influence Loyalty
- Many customers do not subscribe to any add-on services.
- However, customers who subscribed to **multiple add-on services** (e.g. streaming, backup, security) tend to **stay longer**.
- This suggests that educating customers about value-added services and making them readily available might improve retention.

#### 7. Subscription Type Is a Major Driver of Customer Churn
- Month-to-month users account for 67.3% of overall customer churn.


-



