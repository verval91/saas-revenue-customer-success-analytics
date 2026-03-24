# saas-revenue-customer-success-analytics
Tableau portfolio project: Strategic RevOps &amp; Customer Success dashboard analyzing NRR, Churn, and Product Usage for a B2B SaaS company.

# 📈 SaaS Revenue & Customer Success Control Center

![Dashboard Preview](main/Dashboard.png)

### 🚀 Project Overview
This portfolio project presents a strategic analytics solution for **EchoGuard Solutions**, a fictional B2B SaaS company. The dashboard bridges the gap between financial performance (RevOps) and product engagement (Customer Success) to drive sustainable growth.

**Target Roles:** Revenue Operations, Customer Success Manager, Strategic Account Management.

---

### 📊 Key Dashboards & Insights

#### 1. Revenue Waterfall (Net Revenue Momentum)
Visualizes how the company moves from Beginning ARR to Ending ARR through New Business, Expansions, Contractions, and Churn.
* **Key Insight:** While we acquired $365k in New Business, our **Expansion ($210k)** is the real engine of our 135% NRR.
* **Technical Detail:** Implemented using **Table Calculations (Running Total)** and Gantt Bar sizing to map complex subscription lifecycles.

#### 2. Customer Health Scatter Plot (Proactive Churn Prevention)
Correlates financial value (ARR) with customer satisfaction (NPS) and usage trends.
* **Key Insight:** Identified a "High Churn Risk" Enterprise account ($250k+ ARR) with a dropping NPS (4.0). This enables the CS team to intervene before the renewal date.
* **Technical Detail:** Utilized **Level of Detail (LOD - {FIXED})** expressions to isolate the latest month's health metrics and calculate H1 usage growth.

#### 3. Monthly Engagement Trends
Tracks API Usage Calls, Active Users, and Support Ticket volume over 6 months.
* **Key Insight:** A sharp drop in API calls often precedes a spike in support tickets, serving as an early warning system for the GTM team.

---

### 🛠 Tech Stack & Metrics
* **Tool:** Tableau Desktop / Tableau Public
* **Data Prep:** SQL-style relational modeling of Customers, Subscriptions, and Usage logs.
* **Core Metrics:** * **NRR (Net Revenue Retention):** 135.07%
    * **ARR (Annual Recurring Revenue):** $657,000
    * **Customer Health Score:** Segmented by NPS & Usage Growth.

---

### 🔗 Live Interactive Dashboard
**[👉 Click here to view the interactive dashboard on Tableau Public]**

---

### 📂 How to Navigate this Repo
* `/data`: Raw CSV datasets used for the analysis.
* `/screenshots`: High-resolution captures of the dashboard components.
* `/tableau`: The `.twbx` workbook file for technical review.

---
*Created by [A TE NEVED] - Connecting data insights to business outcomes.*
