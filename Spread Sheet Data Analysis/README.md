# 🏙️ Manhattan Vacation Rental Market Analysis  
### Business Intelligence Project | Spreadsheet Data Analysis

---

## 📌 Project Overview

This project analyzes the **Manhattan vacation rental market** to determine:

1. Which neighborhoods are most attractive for vacation rentals
2. Which property sizes (number of bedrooms) are most popular
3. How much revenue the most attractive listings generated

The analysis was conducted using cleaned listing and calendar datasets with pivot tables, revenue modeling, and structured documentation of data preparation steps.

---

## 🎯 Business Questions

- Which 10 neighborhoods are most attractive based on rental activity?
- What bedroom sizes are most popular?
- Do different neighborhoods prefer different property sizes?
- How much revenue did the top-performing listings generate?

---

## 🧹 Data Cleaning Process

All cleaning steps were documented in a separate sheet (see Project Status Report :contentReference[oaicite:0]{index=0}).

### Listings Data Cleaning
- Standardized inconsistent capitalization and spacing in `neighborhood`
- Created `neighborhood_clean` column
- Cleaned `bedrooms` column (empty cells treated as 0 bedrooms → studio)
- Created `bedrooms_clean` column
- Added `top_listing` column (1 = meets top criteria)
- Added `revenue_earned` column using `SUMIF()`

### Calendar Data Cleaning
- Cleaned availability values (`t` / `f`)
- Standardized date and currency formats
- Created `revenue_earned` column:
  - If `available = "f"` → revenue = adjusted_price
  - Else → $0
- Calculated monthly and annualized revenue (30-day revenue × 12)

---

## 📊 Key Findings

---

### 🏘️ Top 10 Most Attractive Neighborhoods

Attractiveness was measured using **number_of_reviews_ltm** (reviews in last 12 months).

According to the pivot table and visualization :contentReference[oaicite:1]{index=1}:

| Neighborhood        | Reviews (LTM) |
|---------------------|---------------|
| Lower East Side     | 6,242 |
| Harlem              | 5,157 |
| Midtown             | 4,128 |
| Upper West Side     | 3,497 |
| Chelsea             | 2,913 |
| East Village        | 2,572 |
| East Harlem         | 2,175 |
| West Village        | 1,735 |
| Upper East Side     | 1,696 |

**Insight:**  
The Lower East Side leads significantly in rental activity, followed by Harlem and Midtown.

---

### 🛏️ Most Popular Property Sizes

Based on cleaned bedroom data :contentReference[oaicite:2]{index=2}:

- 1 Bedroom → 56.7% of listings (Most Popular)
- 2 Bedrooms → 23.6%
- Studios (0 Bedrooms) → 19.8%

**Key Insight:**  
1-bedroom units dominate the Manhattan rental market.

---

### 🏘️ Neighborhood Bedroom Preferences

- All top neighborhoods favored **1-bedroom listings**
- **Exception:** Midtown preferred **studio apartments**

This aligns with Midtown’s higher tourist and business traveler traffic.

---

## 💰 Revenue Analysis

After narrowing down:
- Top 10 neighborhoods
- Most popular bedroom size per neighborhood

Revenue was calculated using 30-day rental totals × 12 months.

From the revenue ranking visualization :contentReference[oaicite:3]{index=3}:

### 🔝 Top Annual Earners (Estimated)

- Highest annualized listing: **$359,280**
- Other top performers ranged from **$273,600 to $153,720 annually**

Top earning neighborhoods included:
- Midtown
- Lower East Side
- Chelsea
- East Village

**Important Insight:**
- Lower East Side is strongest in overall popularity.
- Midtown dominates high-income listings.
- West Village had 3 of the 10 most profitable listings despite lower overall review count.

---

## 📈 Business Recommendations

### 1️⃣ Investment Focus
Prioritize:
- Lower East Side
- Harlem
- Midtown

These neighborhoods show strong demand and review frequency.

---

### 2️⃣ Property Type Strategy
Invest primarily in:
- 1-bedroom units
- Studio units in Midtown specifically

---

### 3️⃣ Revenue Optimization
Focus marketing efforts on:
- High-performing 1-bedroom listings
- Midtown studios for short-term premium stays
- Replicating characteristics of top-performing properties

---

## 🧠 Strategic Insights

- Review count is a strong proxy for rental frequency.
- Smaller units generate higher turnover and consistent demand.
- Revenue concentration suggests opportunity for pricing optimization in mid-tier listings.
- Midtown’s studio demand reflects business traveler segmentation.

---

## 🛠 Tools & Skills Demonstrated

- Excel Pivot Tables
- Data Cleaning & Standardization
- IF() Functions
- SUMIF() Revenue Modeling
- KPI Analysis
- Business Recommendation Development
- Structured Documentation

---


---

## 🚀 What I Learned

This project strengthened my ability to:

- Translate raw data into actionable business recommendations
- Connect pivot table findings to strategic investment decisions
- Document data cleaning processes clearly
- Estimate annual revenue using structured modeling logic
- Present stakeholder-ready insights

---

## 👤 Author

**Preston Long**  
Business Intelligence Analyst  
LinkedIn: [[Preston Long](https://www.linkedin.com/in/preston-long-05555539b/)] 

---


