# 🧣 Looms of Ladakh – Production & Resource Optimization

This project develops an optimization model for Looms of Ladakh (LL) to determine the optimal product mix for an upcoming online launch.

Objective:  
Maximize profit while satisfying raw material, labor, and minimum SKU constraints.

---

## 📌 Business Context

Looms of Ladakh is a women-led cooperative producing luxury pashmina products including:

- Shawls
- Stoles
- Scarves
- Sweaters
- Mufflers
- Caps
- Gloves

For the Okhai launch, LL faces:

- Limited raw materials (23 kg knit, 15 kg woven)
- Limited workforce (13 knitters, 5 weavers)
- Minimum SKU requirements
- 60% dyed production cap

Management must decide whether to:
- Optimize raw material utilization,
- Minimize production time,
- Or maximize profitability.

---

## 🎯 Optimization Model

### Objective
Maximize total profit from woven and knitted products.

Profit per product = Selling Price − (Raw Material + Labor + Dyeing Cost)

---

### Constraints

1️⃣ Raw Material Limits  
- 23 kg knit  
- 15 kg woven  

2️⃣ Labor Capacity  
- 13 knitters  
- 5 weavers  

3️⃣ Minimum Units Required for Launch  
- Shawl: 2  
- Stole: 5  
- Scarf: 10  
- Sweater: 2  
- Muffler: 4  
- Cap: 5  
- Gloves: 5  

4️⃣ Dyed Production Cap  
- Maximum 60% dyed products  

---

## ✅ Optimal Results (Base Model)

Optimal Total Profit: ₹65,689.16  

Higher-margin products such as:
- Shawls
- Scarves
- Sweaters  

are prioritized in the optimal mix.

However, meeting only Okhai’s demand leaves raw material underutilized.

---

## 📈 Extended Production Analysis

When production is extended beyond minimum launch demand:

- Profit increases steadily until Day 36.
- At Day 36, all raw materials are fully utilized.
- Maximum Profit: ₹167,010.73
- Beyond 36 days → No further profit increase (resource exhaustion).

Key Insight:
Instead of producing only for the launch, LL should continue production for retail sales (Leh store) until materials are fully utilized.

---

## 🔍 Sensitivity Analysis

### 1️⃣ Profit Margin Sensitivity

Increasing margins from 5% to 20% significantly increases total profit:

| Margin | Total Profit (₹) |
|--------|------------------|
| 5%     | 200,533 |
| 10%    | 234,056 |
| 15%    | 267,580 |
| 20%    | 301,103 |

Conclusion:
Higher margins (especially via B2C sales) dramatically improve profitability.

---

### 2️⃣ Dyed vs Natural Mix

Reducing dyed cap from 60% to 50%:

- Changes product mix significantly
- Profit drops slightly (₹167,010 → ₹165,369)

Dyed product mix has strong influence on profitability.

---

### 3️⃣ Workforce Sensitivity (Full Process Model)

Without assuming spinning, plying, and dyeing are complete:

- Minimum 49 days required to meet demand under base staffing
- With 20 spinners & 14 plyers → Demand met in 20 days

Conclusion:
Production bottlenecks exist upstream in spinning & plying.

---

## 💡 Key Recommendations

- Increase profit margins, especially in B2C channels.
- Continue production beyond launch minimums to fully utilize raw material.
- Prioritize scarves and mufflers for optimal resource efficiency.
- Invest in building in-house dyeing capability.
- Expand spinning & plying workforce to reduce lead time.
- Leverage GI tagging and government schemes (NHDP, TRIFED) for branding and scale.

---

## 🛠 Techniques Used

- Linear Programming
- Resource Allocation Modeling
- Capacity Planning
- Sensitivity Analysis
- Scenario Planning

---

## 🎯 Skills Demonstrated

- Production optimization under resource constraints
- Multi-resource bottleneck analysis
- Profit sensitivity modeling
- Capacity planning
- Strategic pricing analysis
- Operations strategy alignment

---

This project demonstrates how structured optimization modeling can support sustainable, artisan-led manufacturing businesses in scaling operations while maximizing profitability.
