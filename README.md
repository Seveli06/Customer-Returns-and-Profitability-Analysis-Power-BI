# Retail Returns & Profitability Analysis (Power BI)  
**Data-Driven Insights for Smarter Retail Decisions | 2014–2017**

> **Data-Driven Insights for Smarter Retail Decisions | 2014–2017**

> “How can we reduce product returns and boost profit margins across regions, shipping methods, and customer segments?”

---

##  Project Overview

This Power BI project analyzes a 4-year US retail dataset to uncover trends in returns, profitability, and customer behavior. The goal: **optimize operations, reduce losses, and drive data-backed decisions.**

🔧 **Skills Demonstrated**  
- Data cleaning & modeling in Power Query  
- DAX for dynamic KPIs and time intelligence  
- Advanced dashboards with bookmarks and drillthroughs  
- Business storytelling with insights and recommendations  

---



##  Data Preparation (Power Query)

- Cleaned financial columns: removed $ symbols and converted text to numeric type for Profit, Sales, Discount.  
- Ensured correct data type for date fields → used to build Calendar Table for time intelligence.
- Optimized relationships for one-to-many filtering  
- Removed unnecessary columns for model performance  

---

##  Executive Summary

###  Business Highlights

- **Total Revenue**: $2.30M  
- **Total Profit**: $286.4K  
- **Return Rate**: 5.91%  
- **Total Orders**: 5,000+  

While the business maintains positive margins, profit distribution is uneven across product lines and customer segments — indicating opportunities for strategic tuning.



###  Category Performance

- **Technology** leads with **$145.45K** in profit on **$836K** in sales — the most profitable and scalable category.  
- **Furniture** generates similar revenue (**$742K**) but contributes just **$18K** in profit, reflecting low margins and operational inefficiencies.  
- **Office Supplies** shows healthy returns: **$122K** in profit from **$719K** in sales.

 *Insight:* Strategic focus should remain on Technology and Office Supplies, while Furniture may require cost optimization or SKU rationalization.



###  Return Behavior by Segment & Ship Mode

Returns vary significantly based on **shipping mode** and **customer segment**:

- **Home Office + First Class** has the highest return rate (**7.8%**)  
- **Consumer + Same Day** peaks at **8.28%**, raising concerns over impulsive buying or failed delivery experience  
- **Corporate** customers show elevated return rates across all modes, averaging ~6.6–7.2%

 *Insight:* High-return combinations suggest a need for better expectation setting (e.g., delivery timing, product clarity) and possible return policy segmentation.



###  Regional Patterns & Profitability

- **West Region** has the highest return rate (**11.73%**), over 2× the average — indicating a regional fulfillment or customer satisfaction issue.  
- **Top Profit States**: Washington, New York, Minnesota, Georgia  
- **Low-Profit States**: California, Texas, Florida, Ohio — despite high sales volume

 *Insight:* Regional disparity in profit contribution calls for a review of logistics partnerships, customer behavior, and competitive presence in low-performing states.



###  Strategic Summary

This analysis highlights where the business is earning and where it is leaking — both in profit and product returns. High returns and low margins often overlap, especially in Furniture and select shipping segments. By aligning return policies, optimizing discounts, and focusing on profitable categories, the business can boost bottom-line performance without sacrificing top-line growth.




![Screenshot 2025-05-14 114905](https://github.com/user-attachments/assets/a54735da-b7c6-4c62-a898-08c15db523e2)

---

##  Return Behavior Analysis

Returns aren’t evenly distributed across products, customers, or time — they reveal patterns that, when understood, can directly inform operations, customer experience strategies, and vendor management.

###  Top Returned Sub-Categories

- **Binders** (108 returns), **Paper** (99), and **Phones** (71) account for the highest number of returned items.  
- Notably, these are also high-volume or fragile items — pointing to either quality, usability, or fulfillment issues.

 *Insight:* High-return subcategories should be audited for packaging quality, user experience (e.g., lack of setup guidance), or supplier-related inconsistencies.



###  Return Rate by Customer Type & Product Category

| Customer Type | Furniture | Technology | Office Supplies |
|---------------|-----------|------------|------------------|
| Consumer      | **8.18%** | **8.16%**   | 6.19%            |
| Corporate     | 7.59%     | 7.71%       | 6.65%            |
| Home Office   | 6.51%     | 6.41%       | 5.75%            |

- **Consumers** return Furniture and Technology at the highest rate.
- **Office Supplies** consistently show lower return rates across all segments.

 *Insight:* Consider improving product guidance, reviews, or even trial offers for **Furniture & Tech items** purchased by Consumers — this segment is likely more experience-sensitive and prone to post-purchase dissonance.



###  Return Rate by Month: No Strong Seasonal Pattern

While **January** shows higher return rates in some years (e.g., 2015, 2016), and **June** records the lowest in 2014, 2015, and 2017 — overall, the data does **not show a consistent seasonal return pattern** across all four years.

 *Insight:* This suggests that returns may be influenced more by **product-level or customer-segment factors** rather than time of year. It also indicates that **return mitigation strategies** should focus on **root causes like product category, shipping method, or user expectations** — rather than seasonality alone.



###  Strategic Takeaways

- Prioritize **quality checks and better customer guidance** for high-return subcategories like **Binders** and **Phones**.
- Tailor return reduction strategies by combining insights from **customer segments and product categories** (e.g., Corporate + Furniture).
- Instead of relying on seasonal trends, focus on **continuous monitoring** of return behavior to optimize **reverse logistics** and **resource planning**.





![Screenshot 2025-05-14 115502](https://github.com/user-attachments/assets/dcac19a7-d027-4bb7-9942-5387fecdf569)

---
##  Dashboard 3: Profitability & Discount Analysis


###  Insights  
- **Standard Class** = most profitable ship mode ($164K)  
- Discounts >20% lead to negative margins  
- **0% discount** = 29.5% margin, **15% discount** = 5.1%

###  Recommendations  
- Set discount cap at **15%** for profitability  
- Encourage **Standard shipping** via customer incentives  
- Use **discount what-if tool** for sales vs. profit trade-offs

![Screenshot 2025-05-14 142810](https://github.com/user-attachments/assets/dc15fe40-baec-4cc9-b573-4050e53834e9)

---
##  Drillthroughs & Interactivity

- Drill-through filters by **Ship Mode**, **Customer Segment**, **Product Category**
- Bookmark navigation between **Return View** and **Profitability View**


---

##  Key Business Recommendations

| Focus Area       | Insight                             | Recommendation                            |
|------------------|-------------------------------------|------------------------------------------|
|  Region (West)   | Return rate 2× higher               | Review logistics & packaging processes   |
|  Furniture       | Low profit + high returns           | Reduce SKUs or replace vendors           |
|  Shipping        | Same Day = high returns, low margin | Restrict to loyal customers              |
|  Discounting     | >20% discount = negative margin     | Implement max discount policy            |

---



##  Let’s Connect!

📧 **sevelikaur167@example.com**  
💼 [LinkedIn](https://linkedin.com/in/sevelikaur)  
🐙 [GitHub](https://github.com/sevelikaur)





