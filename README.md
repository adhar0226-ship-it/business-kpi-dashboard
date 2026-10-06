# Business KPI Dashboard: Churn, Retention & Revenue Risk

## Executive Summary & Key KPIs

This interactive KPI dashboard provides executive visibility into customer retention dynamics, revenue at risk, and segment behavior using the synthetic customer churn dataset ($N=15$).

| Metric | Value | Context & Business Impact |
| :--- | :--- | :--- |
| **Churn Rate** | **46.67%** | 7 out of 15 total customers lost in the observation window |
| **Retention Rate** | **53.33%** | 8 active long-term customers remaining |
| **Revenue at Risk (MRR)** | **₹409.93 / mo** | 32.3% of total monthly recurring revenue (₹1,269.85) lost |
| **Avg Tenure (Retained)** | **29.13 months** | Retained accounts stay ~4x longer than churned accounts |
| **Avg Tenure (Churned)** | **7.00 months** | Key drop-off occurs early in the customer lifecycle |

---

## Written Visual Insights (Portfolio Upgrade)

### 1. Churn vs. Retention Breakdown
* **Visual**: Donut Chart showing 53.3% Retained vs. 46.7% Churned.
* **Written Insight**: Retention is heavily skewed by contract structure. Long-term retained accounts provide sustainable baseline revenue, whereas early-stage accounts drop off before reaching month 15.

### 2. Revenue Risk by Contract Type
* **Visual**: Stacked Bar Chart of Monthly Recurring Revenue (MRR) by Contract Type.
* **Written Insight**: 100% of revenue churn (₹409.93/mo) originates from **Month-to-Month** contracts. One-Year and Two-Year contracts generate ₹859.92 in completely protected, zero-churn MRR.

### 3. High-Risk Payment Segments
* **Visual**: Grouped Bar Chart comparing Payment Method vs. Churn Status.
* **Written Insight**: Customers utilizing **UPI** and **Debit Card** exhibit severe churn vulnerability (100% churn on UPI), whereas **Bank Transfer** customers exhibit a 100% retention rate.

### 4. Support Ticket Volume Trigger Threshold
* **Visual**: Bar Chart of Support Tickets in past 90 days by Churn Outcome.
* **Written Insight**: Every single churned customer logged **$\ge 3$ support tickets** in the prior 90 days (averaging 4.29 tickets). Zero customers with $\le 2$ tickets churned, identifying high support interaction as the primary early warning indicator for churn.
