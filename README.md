# 📑 Supermarket Sales Data: Executive Summary

---

## 1️⃣ Dataset Overview  
The dataset captures detailed **point-of-sale transactions** for a supermarket chain, including **Unit price**, **Quantity**, **Tax**, **Total**, **COGS**, **Gross income**, **Gross margin percentage**, **Customer Ratings**, and categorical dimensions like **Branch**, **Gender**, and **Payment Method**.

---

## 2️⃣ Numerical Features Snapshot

- **Unit price** and **Quantity** are generally complete with minimal missing values.
- **Tax 5%**, **Total**, **COGS**, and **Gross income** align perfectly — confirming accurate, consistent financial calculations.
- **Gross margin percentage** is constant at ~4.76%, indicating a fixed margin policy.
- **Customer Ratings** span **4–10**, with a mean of ~7, reflecting generally positive sentiment.

---

## 3️⃣ Ratings Analysis  

- **Mean Rating:** ~7.0 — suggests overall customer satisfaction.
- **IQR (5.5–8.5):** Indicates moderate spread — outliers may highlight dissatisfied or exceptionally satisfied customers.
- **Key Insight:** Ratings are **independent of sales metrics**, implying they are driven by service quality, not transaction value.

---

## 4️⃣ Branch Performance  

- **Total Transactions:** 1,003 — stable operational footprint.
- **Top Branch:** **Branch A** leads slightly ahead of B and C.
- **Recommendation:** Minor performance gaps suggest operational fine-tuning can boost Branch B and C to match Branch A’s output.

---

## 5️⃣ Payment Preferences

- **Top Methods:** Ewallet and Cash dominate equally (346 each).
- **Credit Card:** Slightly underutilized (311) — opportunity to incentivize adoption for better transaction security.
- **Strategic Action:** Maintain Ewallet/Cash momentum while promoting credit card use via loyalty perks or discounts.

---

## 6️⃣ Gross Income Analysis

- **By Branch:**  
  - All branches show **similar medians**, but Branch C has a **slightly higher median and wider spread**, indicating pockets of higher income opportunities.
  - Outliers exist across branches, highlighting high-value transactions worth further exploration.

- **By Gender:**  
  - Females exhibit a marginally higher median gross income than males.
  - Both genders display comparable spread and outliers, confirming **gender is not a major income driver**.

- **Temporal Trends:**  
  - Daily gross income shows high volatility.
  - **3-day and 7-day moving averages** reveal no strong upward or downward trend but highlight short-term peaks.
  - **Weekly seasonality:** Income peaks on **Saturdays and Sundays**, dips midweek — suggesting operational or promotional boosts may be timed accordingly.

---

## 7️⃣ Correlation Matrix

- **Strong Clusters:** Unit price, Quantity, Tax 5%, Total, COGS, and Gross income are tightly correlated — all driven by sales volume and pricing.
- **Rating:** Shows **negligible correlation** with financial variables — reinforcing that revenue-focused tactics alone won’t lift customer satisfaction.
- **Implication:** Multicollinearity is likely within revenue fields — dimensionality reduction or feature elimination may be prudent for modeling.

---

## 🗂️ Final Recommendations  

✅ **Grow Revenue:**  
- Focus on **increasing unit price and quantity** through upselling, cross-selling, or targeted promotions.

✅ **Elevate Ratings:**  
- Prioritize **service quality initiatives**, customer care, and loyalty programs to uplift ratings — since financial levers alone won’t shift them.

✅ **Operational Strategy:**  
- Leverage peak days (weekends) for promotions.
- Optimize branch-level operations to balance throughput across locations.
---

## 🔗 Next Steps

1. **Visualize further:** Deploy additional plots for seasonal trends or cohort analysis.
2. **Deep-dive segments:** Examine low-rating clusters to uncover service pain points.
3. **Drive actions:** Build targeted strategies for branches, payment promotions, and loyalty engagement.

---

**📌 Bottom Line:**  
The dataset provides actionable, multi-dimensional insights to **grow revenue**, **enhance service quality**, and **align operational strategy** with data-backed clarity.

---
