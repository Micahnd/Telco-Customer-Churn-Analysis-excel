# Understanding Telco Customer Churn: Trends, Patterns and  Revenue impact
<img src="https://github.com/Micahnd/customer-churn-dashboard-excel/blob/main/customer-churn-all-customers.png" alt="Dashboard Overview" width="650">

*Fig 1: Customer Churn Overview: All customers*

<img src="https://github.com/Micahnd/customer-churn-dashboard-excel/blob/main/customer-churn-senior-citizen.png" alt="Dashboard Overview: Senior Citizens" width="650">

*Fig 2: Customer Churn Overview: Senior citizens*

<img src="https://github.com/Micahnd/customer-churn-dashboard-excel/blob/main/customer-churn-non-senior-citizens.png" alt="Dashboard Overview: Non-Senior Citizens" width="650">

*Fig 3: Customer Churn Overview: Non-Senior citizens*

## 📌 Project Overview
This project presents a **data-driven exploration of customer churn** for a fictional telecom company. Built entirely in **Microsoft Excel**, the dashboard is a practical tool to **understand customer behavior**, highlight **revenue risks** and guide **further business investigation**.

## 🎯 Business Purpose
Customer churn is one of the most pressing issues for subscription-based services like telecoms. It directly impacts revenue and often reflects deeper service or experience issues.

The aim of this analysis is not to predict churn, but to: 
- Reveal **who is churning**.
- Uderstand **why they might be churning**.
- Highligh **where revenue is most at risk** and **how churn affects revenue**
- Guide teams towards **areas worth deeper investigation** and where **retention efforts should be focused**

## 🔍 Why Excel?
While tools like Python, SQL, and Power BI would offer automation and scalability, I chose Excel here for its:
- **Accessibility**: MS Excel is widely used across departments, especially in non-technical teams.
- **Transparency**: Formulas, calculations and pivots are easily auditable.
- **Speed**: Enabled quick exploration.

## 📊 Key Findings

#### 1. Short-Term Subscribers Are driving Churn
- **67.3%** of churned users were on month-to-month plans, this was by far the highest churn rate in the category.
- Among senior citizens that figure rises to **79.1%**
- In contrast, **one year contracts** showed 23.6% churn and only 9.1% of churners had **two-year contracts**.
- This suggests **longer commitments anchor loyalty** and may reflect  stronger satisfaction especially among senior citizens.

#### 2. Tenure Impacts Retention
- Churn is **significantly higher in the first 12 months** of subscription.
- Customers with longer tenure (especially over 3 years) show **much lower churn rates**, this also agrees with the finding that **short-term subscribers churn more**.
- This insight was visible in the main dashboard and across both filtered dashboards (senior and non-senior citizens), confirming tenure as a stable churn indicator.
- Retention efforts should focus on **customers in their first years and customers on short-term contracts**.

#### 3. Revenue Risk in Customer Churn
- Churned customers had a **higher average monthly cost** (₦74.44) than those retained (₦61.31).
- Among senior citizens, this figure rises further to ₦79.82, indicating they are the most valuable but most vulnerable customers in this class.
- ⚠️ This means the company is **losing its most valuable customers**, not just the most dissatisfied.
- Consider **investigating why senior citizens and other high-spenders churn**, are they not getting value for money?

#### 4. Living Situation Affects Loyalty
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

#### 7. Internet Type Churn
- **Fiber Optic** users had **41.9%** churn rate, the highest among internet types, this figure is seen to rise among senior citizens **(47.3%)**.
- Meanwhile, **DSL** users generally showed lower churn **(19%)** which significantly rose to **30.1%** among senior citizens.
-  **No internet users** had the lowest churn.
- ⚠️This could suggest **service quality concerns** among Fiber Optic users, despite its premium cost. Also, difficulty managing internet technical issues is suspected among senior citizens.




-



