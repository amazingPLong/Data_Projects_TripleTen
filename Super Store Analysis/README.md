# 🛍️ Saving SuperStore  
### Data Visualization with Tableau | Profitability, Advertising & Returns Analysis

---

## 📌 Project Overview

The SuperStore is facing declining profitability and potential bankruptcy.  
As a consultant, I was hired to analyze operational performance and identify:

- Major profit centers and loss drivers
- Products and subcategories to discontinue
- Strategic advertising opportunities
- Return rate risks affecting profitability

All findings were supported with individual Tableau visualizations and business-focused recommendations.

---

# 📊 Part 1: Profit & Loss Analysis

(See Profit & Loss dashboard: :contentReference[oaicite:0]{index=0})

## 🔎 Top Profit Centers

Analysis of dimension pairs revealed:

### ✅ Strongest Subcategories
- **Copiers**
- **Phones**
- **Accessories**

These categories consistently generated strong positive margins across regions.

---

## ❌ Largest Loss Drivers

### Bottom Performing Subcategories:
- **Tables**
- **Bookcases**
- **Supplies**

Certain regions (notably Central and East) showed persistent losses in these segments.

---

## 🚫 Products to Stop Selling

The “Products to Stop Selling” visualization identified specific SKUs generating consistent losses.

Examples include:
- StarTech HDMI Adapter Kit
- Bush Saratoga Collection Bookcase
- Chromcraft Rectangular Conference Tables

These products show negative profit across multiple years and regions.

---

## 🎯 Strategic Recommendation

- Double down on **Copiers, Phones, Accessories**
- Discontinue consistently negative-margin SKUs
- Reevaluate pricing or sourcing strategy for Furniture (especially Tables)

---

# 📢 Part 2: Advertising Strategy

(See Advertising Breakdown dashboard: :contentReference[oaicite:1]{index=1})

The SuperStore wants to invest in advertising only where **Return on Ad Spend (ROAS)** justifies it.

### 🏆 Top 3 State + Month Combinations

| State | Best Month | Avg Profit |
|--------|------------|------------|
| Indiana | October | $596 |
| Vermont | November | — |
| Washington | March | $521 |

These combinations show the highest average profit per unit sold.

---

## 💰 Advertising Budget Rule

For this exercise:
> Willing to spend **1/5 (20%) of average profit** on advertising.

Example:
- If avg monthly profit = $596  
- Max recommended ad spend = ~$119

This ensures positive ROAS.

---

## 📈 Strategic Insight

Advertising should:
- Be geographically targeted
- Be seasonally optimized
- Focus only on historically high-margin states

Avoid blanket national campaigns.

---

# 🔁 Part 3: Returned Items Analysis

(See Returns Dashboard: :contentReference[oaicite:2]{index=2})

To assess operational risk:

- Returns table was LEFT JOINED to Orders
- “Returned” converted to binary calculated field (Yes = 1, Null = 0)
- Return rate calculated per product and customer

---

## 🔎 Highest Return Rate Products

Top returned products include:
- Zebra GX420 Printer
- Okidata Printer
- Cisco SPA 501G Phone
- Logitech Wireless Speaker

These products show abnormal return percentages.

---

## 👤 Customers with Highest Return Rates

Several customers show return rates above 80–100%, indicating:
- Potential abuse
- Product quality issues
- Misaligned expectations

---

## 📊 State Profit vs Return Rate

Scatter analysis shows:

- Some states (e.g., Oregon, Tennessee, Colorado) combine **low profit + high return rates**
- Others (e.g., Indiana) maintain high profitability with moderate returns

---

# 💡 Executive Recommendations

## 1️⃣ Remove or Reprice Loss-Making SKUs
Eliminate products with persistent negative margins and high return rates.

## 2️⃣ Optimize Advertising Spend
Focus budget on:
- Indiana (October)
- Vermont (November)
- Washington (March)

Use a capped 20% ROAS model.

## 3️⃣ Reduce Return Risk
- Audit high-return SKUs
- Review supplier quality
- Implement stricter return policies for high-risk customer accounts

## 4️⃣ Focus on High-Margin Categories
Expand:
- Copiers
- Phones
- Accessories

Scale back:
- Tables
- Bookcases
- Supplies

---

# 🛠 Skills Demonstrated

- Tableau Dashboard Development
- Profit & Loss Decomposition
- Dimensional Analysis
- ROAS Modeling
- Return Rate Calculations
- LEFT JOIN Data Modeling
- Calculated Fields in Tableau
- Executive Storytelling with Data

---

# 📂 Repository Structure
---

---

# 🧠 What This Project Demonstrates

- Ability to diagnose financial risk
- Profitability segmentation skills
- Advertising investment modeling
- Return behavior analysis
- Strategic decision-making using visualization
- Business-first thinking

---

## 👤 Author

**Preston Long**  
Business Intelligence Analyst  
LinkedIn: [[Preston Long](https://www.linkedin.com/in/preston-long-05555539b/)]  

---
