# ShopPulse — Retail Customer Intelligence

**End-to-end retail analytics project combining Python, SQL, and Power BI to turn raw shopping data into customer-level business insight.**

---

## Overview

A retail company wants to understand its customers' shopping behavior to improve sales, satisfaction, and long-term loyalty. Management needs visibility into purchasing patterns across demographics, product categories, discounts, reviews, seasons, and payment preferences — and, beyond that, a way to tell which customers actually drive the business.

**Core question:** *How can the company use its shopping data to identify trends, improve customer engagement, and optimize marketing and product strategy?*

ShopPulse answers this in two layers:
1. **Shopping Behavior Analysis** — demographics, categories, discounts, seasonality, payments.
2. **Customer Intelligence** — a rule-based customer value segmentation framework that groups customers by purchase value and purchase history, then compares segment performance.

---

## Objectives

- Analyze customer shopping behavior and purchasing patterns
- Identify trends across customer demographics and product categories
- Examine how discounts, reviews, seasonality, and payment method relate to purchasing
- Perform business-oriented analysis in SQL
- Build an interactive Power BI dashboard
- Develop a customer value segmentation framework
- Compare segments by size, purchase value, ratings, and revenue contribution
- Translate findings into actionable business recommendations

---

## Tech Stack

| Technology | Purpose |
|---|---|
| **Python / Pandas** | Data cleaning and exploratory analysis |
| **PostgreSQL** | Database management |
| **SQL** | Business analysis and insight generation |
| **Power BI** | Interactive dashboard and visualization |
| **DAX** | Customer segmentation logic and analytical measures |

---

## Workflow

```
Raw Customer Dataset
        │
        ▼
Python / Pandas  ──▶  Data Cleaning & Exploration
        │
        ▼
PostgreSQL  ──▶  SQL Business Analysis
        │
        ▼
Power BI  ──▶  Customer Intelligence  ──▶  Business Insights
```

---

## Customer Intelligence: Segmentation Framework

Customers are segmented on two dimensions — **purchase amount** and **previous purchase history** — using DAX in Power BI.

| Segment | Definition |
|---|---|
| **VIP** | High purchase value + high purchase history |
| **Growth** | High purchase value + lower purchase history |
| **Loyalist** | Lower purchase value + high purchase history |
| **Low Engagement** | Lower purchase value + lower purchase history |

> **Note:** These are rule-based analytical groupings derived from purchase value and purchase history within this dataset — not predictive or lifetime-value models.

---

## Dashboard

The Power BI dashboard is built around two views:

**Shopping Behavior**
- Customer demographics
- Purchase behavior and product performance
- Category-level analysis
- Seasonal purchasing patterns
- Payment preferences and subscription behavior
- Discount usage and customer ratings

**Customer Intelligence**
- Customer base distribution across VIP / Growth / Loyalist / Low Engagement
- Average purchase amount by segment
- Segment performance comparison — customer count, average purchase amount, average review rating, and revenue contribution %

---

## Key Analytical Questions

**Shopping Behavior**
- Which products and categories perform best?
- How does purchasing behavior differ across customer demographics?
- How do discounts relate to purchasing behavior?
- How do customer ratings vary across products and categories?
- How do purchasing patterns differ across seasons?
- What payment and subscription patterns exist?

**Customer Intelligence**
- How can customers be segmented by purchase value and purchase history?
- What proportion of customers falls into each segment?
- Which segments show the highest average purchase value?
- How do segments compare on volume, value, ratings, and revenue contribution?

---

## Repository Structure

```
ShopPulse-Retail-Customer-Intelligence/
│
├── README.md
│
├── data/
│   └── customer_shopping_behavior.csv
│
├── notebooks/
│   └── ShopPulse_Analysis.ipynb
│
├── sql/
│   └── ShopPulse_Analysis.sql
│
├── powerbi/
│   └── ShopPulse_Dashboard.pbix
│
├── documentation/
│   └── Business_Problem_Statement.pdf
│
└── images/
    ├── dashboard_overview.png
    └── customer_intelligence.png
```

---

## Key Takeaway

ShopPulse pairs Python-based data preparation with PostgreSQL/SQL analysis and Power BI visualization to build a complete retail analytics workflow — from raw data to dashboard. It goes beyond general behavior analysis by layering in a customer value segmentation framework that distinguishes customer groups and quantifies their relative contribution to the business.

---

## Author

**Arkajyoti Sarkar**

Tools: Python · SQL · PostgreSQL · Power BI · DAX
