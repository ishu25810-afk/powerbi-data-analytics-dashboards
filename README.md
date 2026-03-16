The Telecom Churn Analysis project is a dual-page Power BI solution designed to help telecommunications providers visualize customer retention, identify high-risk segments, and understand the drivers behind subscriber turnover.

The analysis focuses on correlating service types, contract structures, and support interactions with churn probability to drive data-driven retention strategies.

📊 Phase 1: Customer Profile & Churn Drivers
Focus: Understanding the demographics and behaviors of the 1,869 customers currently identified as "At Risk."

Key Metrics (KPIs)
Customers at Risk: 1,869

Support Volume: 2,173 Technical Tickets vs. 885 Administrative Tickets.

Monthly Charges: $139.13K (Current monthly revenue at risk).

Critical Insights
The "First Year" Risk: 55.48% of churned customers leave within their first 12 months.

Contract Vulnerability: 88.55% of those who churn are on Month-to-Month contracts.

Service Correlation: Customers using Fiber Optic internet and Electronic Check payments represent the highest concentration of churned users.

📊 Phase 2: Risk & Revenue Analysis
Focus: A high-level view of the entire 7,043-customer base to identify systemic risks.

Key Metrics (KPIs)
Global Churn Rate: 26.54%

Total Yearly Revenue: $16.06M

Revenue Distribution: Significant revenue is tied to Fiber Optic users, yet this group has a 41.89% churn rate.

Risk Correlation
Contractual Loyalty: Moving a customer from a Month-to-Month to a Two-year contract reduces churn probability from 42.7% down to 2.8%.

Payment Sensitivity: Customers using automated payment methods (Credit Card/Bank Transfer) show significantly higher retention than those using manual Electronic or Mailed checks.

🛠️ Data Model & DAX Formulas
Churn Rate %: Calculated as DIVIDE([Total Churned], [Total Customers], 0)

Customer Risk Level: A calculated column categorizing users based on tenure (<12 months) and contract type (Month-to-Month).

Total Revenue Impact: Sum of MonthlyCharges for customers where Churn = 'Yes'.

💡 Executive Recommendations
Retention Campaigns: Launch targeted discounts for Month-to-Month users to migrate them to 1-year contracts.

Fiber Optic Audit: Investigate the high churn in Fiber Optic services. The data suggests a possible disconnect between high pricing and service reliability/satisfaction.

Support Optimization: With Technical Tickets outnumbering Admin Tickets 2.5:1, improving first-call resolution for technical issues is a primary lever for retention.

Auto-Pay Incentives: Offer a small monthly credit for customers who switch from Electronic Checks to Auto-pay via Credit Card/Bank Transfer.
