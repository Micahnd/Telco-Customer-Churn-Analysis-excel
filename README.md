# Understanding Telco Customer Churn: Trends, Patterns and  Revenue impact

## 📊 Introduction
Customer churn is a major threat to growth in Telecom companies, not just in lost numbers but in lost revenue and relationships. This project using Microsoft Excel, explores churn patterns, uncovers risk customers and point out behaviors that may be driving customers away.
The goal is not to predict churn but to understand it clearly enough to guide better decisions.

## 📷 Dashboard Snapshots

<img src="https://github.com/Micahnd/customer-churn-dashboard-excel/blob/main/customer-churn-all-customers.png" alt="Dashboard Overview" width="800">

*Fig 1: Customer Churn Overview: All customers*

<img src="https://github.com/Micahnd/customer-churn-dashboard-excel/blob/main/customer-churn-senior-citizen.png" alt="Dashboard Overview: Senior Citizens" width="800">

*Fig 2: Customer Churn Overview: Senior citizens*

<img src="https://github.com/Micahnd/customer-churn-dashboard-excel/blob/main/customer-churn-non-senior-citizens.png" alt="Dashboard Overview: Non-Senior Citizens" width="800">

*Fig 3: Customer Churn Overview: Non-Senior citizens*

## 📌 Project Overview
This project presents a **data-driven exploration of customer churn** for a fictional telecom company. Built entirely in **Microsoft Excel**, the dashboard is a practical tool to **understand customer behavior**, highlight **revenue risks** and guide **further business investigation**.

## 📘 Definitions
- **Senior citizens**: These are customers above the age of 49.
- **Tenure**: Refers to how long the customer has patronized the business.
- **Living Situation**: Refers to customer's household structure.
- **Payment Method**: Refers to the way customers pay for their subscriptions.
- **Subsription Type**: Refers to customers billing commitment.

## 🎯 Business Purpose
Customer churn is one of the most pressing issues for subscription-based services like telecoms. It directly impacts revenue and often reflects deeper service or experience issues.

The aim of this analysis is to: 
- Reveal **who is churning**.
- Uderstand **why they might be churning**.
- Highligh **where revenue is most at risk** and **how churn affects revenue**.
- Guide teams towards **areas worth deeper investigation** and where **retention efforts should be focused**.

## 🔍 Why Excel?
While tools like Python, SQL, and Power BI would offer automation and scalability, I chose Excel here for its:
- **Accessibility**: MS Excel is widely used across departments, especially in non-technical teams.
- **Transparency**: Formulas, calculations and pivots are easily auditable.
- **Speed**: Enabled quick exploration.

## 🔑 Findings

#### 1. ❌ Short-Term Subscribers Are driving Churn.
- **67.3%** of churned users are on month-to-month plans, this is by far the highest churn rate in the category.
- Among **senior citizens** that figure rises to **79.1%**.
- In contrast, **one year contracts** show **23.6%** churn and only **9.1%** of churners have **two-year contracts**.
- This suggests **longer commitments esnure loyalty** and may reflect  stronger satisfaction especially among senior citizens.

#### 2. 📉 Tenure Impacts Retention.
- Churn is **significantly higher in the first 12 months** of subscription.
- Customers with longer tenure (especially over **3 years**) show **much lower churn rates**, this also agrees with the finding that **short-term subscribers churn more**.
- This insight is visible in the main dashboard and across both filtered dashboards (senior and non-senior citizens), confirming **tenure as a stable churn indicator**.
- This suggests retention efforts should focus on **customers in their first years and customers on short-term contracts**.

#### 3. 💸 Revenue Risk in Customer Churn.
- Churned customers have a **higher average monthly cost** **(₦74.44)** than those **retained (₦61.31)**.
- Among senior citizens, this figure rises further to **₦79.82**, indicating they are the most valuable but most vulnerable customers in this class.
- ⚠️ This means the company is **losing its most valuable customers**, not just the most dissatisfied.
- This raises the quesion; **why senior citizens and other high-spenders churn**, are they not getting value for money?

#### 4. 🧍 Living Situation Affects Loyalty.
- Customers who **live alone(No partner or dependents)** are more likely to churn than those in **shared living situations.**
- This behavioral trend might reflect **less brand loyalty** or **higher price sensitivity** in customers with no dependents.

#### 5. 💳 Churn by Payment Method
- **Electronic check** users have the highest churn rate overall, especially among **senior citizens** most of whom are seen to rely on this payment method.
- This suggests issues like **payment friction**, **digital literacy challenges** or **lack of trust in automated bills**.
- This questions the **electronic payment experience** especially for senior citizens.

#### 6. 📦 Add-on Services Influence Loyalty.
- Many customers do not subscribe to any add-on services.
- However, customers who subscribe to **multiple add-on services** (e.g. streaming, backup, security) tend to **stay longer**.
- This suggests that **educating customers about value-added services** and making them readily available might improve retention.

#### 7. 🌐 Internet Type Churn.
- **Fiber Optic** users have **41.9%** churn rate, the highest among internet types, **this figure is seen to rise among senior citizens (47.3%)**.
- Meanwhile, **DSL** users generally show lower churn **(19%)** which significantly rises to **30.1%** among **senior citizens.**
-  **"No internet users"** have the lowest churn.
- ⚠️This could suggest **service quality concerns** among Fiber Optic users, despite its premium cost. Also, difficulty managing internet technical issues is suspected among senior citizens.

## 🧭 Recommendations for Business Teams. 
These findings do not offer final answers, rather **they suggest where teams should look deeper**.

#### 1. 🎯 Retention Strategy.
- Focus on users in their **first year** and on **month-to-month** subscriptions, they churn the most.
- Prioritize **high-value segments like senior citizens**, who:
  - Pay the most monthly **(₦79.82)**.
  - Churn the most **(41.7%)**.
  - Are largely on **month-to-month plans**.
- Suggest launching **targeted retention programs for seniors**, including loyalty perks and simplified service options.

#### 2. 👥 User Segmentation 
- Explore why **users living alone churn more**, are they less engaged? Are offers not personalized enough?

#### 3. 🧾 Payment Experience Audit
- Investigate the electronic check payment experience, especially for senior citizens.
- Offer improved digital onboarding or **simplified billing options**.

#### 4. 📦 Bundle Optimization
- Analyze which combination of services reduce churn without overwhelming the customer.
- **Offer customizable bundles** and **encourage customers to take up more added services**.

#### 5. 🧾 Subscription Strategy
- Encourage **longer-term contracts** during onboarding, especially for senior citizens.
- Consider incentives or onboarding plans that **promote annual commitments**.

#### 6. 🌐 Check Internet Product Quality
- Review possible complaints or satisfaction data for **fiber optic subscribers**.
- Explore whether churn is due to **expectation gaps** or **technical service issues**.
- Offer **simplified, affordable internet plans with dedicated support** tailored to senior citizens to reduce churn.


## 🛠 Techincal Summary
- **Tools**: Microsoft Excel
- **Dataset**: Telco customer churn. IBM
- **Features Used**: Pivot Tables, Slicers, Currency Formatting, Bar Charts, Donut Charts, Combo charts.
- **Sheets**: DataSheet, ChartSheet, Backend.
- **Data source**: [Kaggle](https://www.kaggle.com/datasets/yeanzc/telco-customer-churn-ibm-dataset)

## 📚 Author
#### Micah Ndubuisi Ezirim
Data Analyst | Lagos, Nigeria.

[LinkedIn](https://www.linkedin.com/in/ezirim-micah-268955241)











