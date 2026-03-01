# 📊 Turning Event Logs into Business Metrics  
### E-Commerce Conversion Funnel & Cohort Retention Analysis

---

## 📌 Project Overview

As a Junior Business Analyst, I was tasked with transforming raw transaction event logs into actionable business metrics for an e-commerce company.

Each row in the dataset represented a user event (product view, shopping cart open, or purchase). The objective was to:

- Build a 3-stage conversion funnel
- Perform cohort analysis based on first purchase month
- Calculate month-over-month retention rates
- Deliver stakeholder-ready insights and recommendations

The analysis was conducted using advanced spreadsheet techniques including pivot tables, lookup functions, cohort modeling, and retention calculations.

---

## 📂 Dataset Overview

The raw dataset included:

- `user_id`
- `event_type` (view, shopping_cart, purchase)
- `category_code`
- `brand`
- `price`
- `event_date`

The analysis used 6 months of user activity data for cohort grouping (as noted in the Executive Summary sheet :contentReference[oaicite:0]{index=0}).

---

# 🔄 Part 1: Conversion Funnel Analysis

The funnel was built using unique user counts across three stages:

1️⃣ Product View  
2️⃣ Shopping Cart  
3️⃣ Purchase  

### 📊 Funnel Results

From the conversion visualization :contentReference[oaicite:1]{index=1}:

| Stage | Unique Users | Conversion Rate to Next Step | Total Conversion Rate |
|--------|--------------|-----------------------------|-----------------------|
| View | 10,453 | — | 100% |
| Shopping Cart | 3,036 | 29.04% | 29.04% |
| Purchase | 1,081 | 35.61% | 10.34% |

### 🔎 Key Insights

- Only **29.04%** of viewers added items to cart.
- Of those, **35.61%** completed a purchase.
- Overall, only **10.34% of viewers converted to buyers.**
- Nearly **60% of users drop off after viewing a product page.**

### 📌 Recommendation

- Investigate friction in checkout flow
- Review payment processing usability
- Simplify cart-to-purchase steps
- Optimize product page clarity and call-to-action placement

---

# 👥 Part 2: Cohort Analysis & Retention Modeling

To analyze retention behavior:

- Filtered purchase events only (4,845 purchase records)
- Identified each user’s **first_purchase_date**
- Created:
  - `event_month`
  - `first_purchase_month`
  - `cohort_age` (0–4 months using DATEDIF)

Cohorts were grouped by **first purchase month**, resulting in 6 acquisition cohorts :contentReference[oaicite:2]{index=2}.

---

# 📉 Part 3: Retention Rate Analysis

Retention rates were calculated month-by-month for each cohort :contentReference[oaicite:3]{index=3}.

### 📊 Observed Retention Patterns

| Cohort | Month 1 | Month 2 | Month 3 | Month 4 |
|--------|----------|----------|----------|----------|
| 2020-09 | 12.50% | 6.25% | 0.00% | 3.13% |
| 2020-10 | 7.49% | 3.74% | 0.53% | 0.53% |
| 2020-11 | 5.46% | 2.94% | 0.42% | 0.00% |
| 2020-12 | 4.43% | 2.96% | 0.00% | 0.00% |
| 2021-01 | 6.87% | 0.00% | 0.00% | 0.00% |
| 2021-02 | 0.00% | 0.00% | 0.00% | 0.00% |

### 🔎 Key Insights

- Retention drops sharply after first purchase.
- Most cohorts approach near-zero repeat purchases by month 3 or 4.
- Strongest retention was observed in the earliest cohort (2020-09).
- Customer lifetime engagement is very short.

---

# 💡 Strategic Business Conclusions

## 🚨 Major Funnel Drop-Off

The biggest issue is at the **top of the funnel**:
- 70% of users do not move past product viewing.

## 🔁 Weak Customer Retention

- Repeat purchase rates decline rapidly.
- Most customers purchase once and do not return.

---

# 📈 Business Recommendations

### 1️⃣ Improve Product Page Conversion
- Test pricing clarity
- Optimize call-to-action buttons
- Improve trust signals (reviews, guarantees)

### 2️⃣ Optimize Checkout Flow
- Reduce friction in payment steps
- Offer guest checkout
- Address potential UX barriers

### 3️⃣ Strengthen Post-Purchase Strategy
- Launch targeted email campaigns
- Offer return discounts for first-time buyers
- Introduce loyalty incentives

---

# 🛠 Tools & Techniques Demonstrated

- Excel Pivot Tables
- COUNTUNIQUE analysis
- VLOOKUP()
- TEXT() for month formatting
- DATEDIF() for cohort aging
- Funnel modeling
- Retention rate calculations
- Executive reporting & structured documentation

---


---

# 🧠 What This Project Demonstrates

- Ability to convert raw event logs into structured KPIs
- Understanding of funnel performance analysis
- Knowledge of cohort-based retention modeling
- Spreadsheet-based analytical rigor
- Executive-ready reporting

---

## 👤 Author

**Preston Long**  
Business Intelligence Analyst  
LinkedIn: [[Preston Long](https://www.linkedin.com/in/preston-long-05555539b/)]  

---

