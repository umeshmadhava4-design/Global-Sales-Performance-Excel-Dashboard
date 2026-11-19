# Global Sales Performance & Business Analysis Dashboard (MS Excel)

![Dashboard Preview](dashboard_preview.png)

## Project Overview
Analyzed **51,280+ global retail transactions (2011–2014)** across 6 international markets (`APAC`, `EU`, `North America`, `LATAM`, `EMEA`, and `Africa`) to evaluate revenue growth, profit margins, shipping efficiency, and discount impact.

## Key Metrics & Findings
* **Total Sales:** $12,641,151 across **25,035 unique orders**
* **Total Profit:** $1,467,237 (**12% overall profit margin**)
* **Avg. Delivery Lead Time:** 3.97 days
* **Top Category:** **Technology** ($4.74M sales, $663K profit) leads overall profitability, while **Furniture** ($4.11M sales, $285K profit) suffers from heavy discounting (>20%).
* **Top Markets:** **APAC** ($3.59M) and **EU** ($2.94M) generate over 50% of global revenue.

## Excel Tools & Techniques Used
* **Data Cleaning:** Removed 10 duplicate line items, deleted system artifact columns, standardized 27 headers/dates, and cleaned text strings (`TRIM`, `PROPER`).
* **Data Modeling:** Built a relational `Master_Lookup` table using `XLOOKUP` (`IFERROR`) and engineered helper columns (`Order Month`, `Shipping Days`, `Discount Tier`, `Profit Status`).
* **Analytics & Visualization:** Enabled the **Excel Data Model** for `Distinct Count` order tracking, created 5 dynamic Pivot Tables, KPI cards, interactive Slicers, and a Date Timeline.

## Business Recommendations
1. **Cap Furniture Discounts at 20%** to prevent margin erosion and lift overall company profit margin toward **14–15%**.
2. **Scale High-Margin Inventory** for Technology and flagship smartphones in **APAC** and **EU**.
3. **Optimize Regional Logistics** in emerging markets (**EMEA** and **Africa**) to reduce delivery lead times.
