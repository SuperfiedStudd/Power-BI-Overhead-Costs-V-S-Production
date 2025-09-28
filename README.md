# Power-BI-Overhead-Costs-VS-Production  

[View on Microsoft AppSource](https://appsource.microsoft.com/en-us/product/power-bi/dhyeyconsultingservicespvtltd1584430919382.overhead-costs-power-bi?tab=Overview)  

[![Watch the Demo](https://img.youtube.com/vi/Q9W3qjUr7uw/0.jpg)](https://youtu.be/Q9W3qjUr7uw?si=k9quv1HnynG-M2Ax)  

---

## Overview  

Overhead expenses can quietly erode profit margins if left unmonitored. The **Overhead Costs vs Production Dashboard** equips finance and plant teams with a clear view of how fixed and variable overheads like labor, electricity, fuel, and compliance relate to production volume and value.  

This Power BI app turns monthly cost and output records into actionable insights, enabling smarter cost control, resource optimization, and benchmarking across time and location.  

---

## Technical Framework  

The dashboard is powered by a structured dataset named **Overhead Costs**, which aligns overhead spending with production metrics by plant and time period.  

**Key components:**  
- **Data Source:** Excel or ERP exports with monthly cost and production details by plant  
- **Data Preparation (Power Query):**  
  - Cleaned and transformed cost categories and dates  
  - Calculated cost ratios (e.g., cost per ton or per ₹)  
  - Aggregated by time and location for benchmarking  
  - Normalized visuals for clearer year-on-year comparison  
- **Data Model Dimensions:**  
  - Year, Month, Quarter  
  - Location  
  - Quantity Produced (Tons)  
  - Value Produced  
  - Total Overhead Cost  
  - Breakdown by:  
    - Electricity  
    - Labor  
    - Heating/Fuel  
    - Environmental & Compliance  
    - Safety & Accidental Cover  

This model supports both trend-level and granular component-level cost analysis.  

---

## Interactive Filters  

The dashboard includes filters that allow precise exploration of data:  
- **Location:** Compare plants or units  
- **Time (Year, Quarter, Month):** Detect seasonal or annual cost shifts  
- **Overhead Category:** Focus on specific drivers like fuel or compliance  

These filters enable precision auditing of cost-effectiveness over time and across sites.  

---

## Dashboard Highlights  

**Production & Overhead Summary Table**  
Displays quantity produced, value produced, and associated overheads aggregated across months and years.  

**Overhead Ratio by Category (Line Charts)**  
Tracks cost efficiency over time for each overhead type including electricity, labor, compliance, safety, and fuel, plotted alongside production value to reveal mismatches.  

**Trend Analysis**  
Year-on-year and month-on-month comparisons highlight evolving cost dynamics and their alignment with output.  

---

## Screenshots  

### Dashboard Overview  
![Dashboard Overview](https://github.com/SuperfiedStudd/Power-BI-Overhead-Costs-vs-Production/blob/main/docs/dashboard_overview.png?raw=true)  

### Overhead Breakdown  
![Overhead Breakdown](https://github.com/SuperfiedStudd/Power-BI-Overhead-Costs-vs-Production/blob/main/docs/overhead_breakdown.png?raw=true)  

### Production vs Cost Trends  
![Production vs Cost Trends](https://github.com/SuperfiedStudd/Power-BI-Overhead-Costs-vs-Production/blob/main/docs/trends.png?raw=true)  

---

## How to Use  

This repository is intended as a showcase:  
1. Watch the demo video above for a walkthrough.  
2. Explore the screenshots for dashboard views.  
3. Try the published app directly on [Microsoft AppSource](https://appsource.microsoft.com/en-us/product/power-bi/dhyeyconsultingservicespvtltd1584430919382.overhead-costs-power-bi?tab=Overview).  
   - You can download and play around with the app if you have a school or work account that supports Microsoft apps.  

---

## Why It Matters  

This Power BI app empowers teams to manage cost structures proactively, ensuring overheads remain aligned with output and value. The result: improved profitability, smarter resource allocation, and more strategic spending.  

---

## Author  

Developed by **Jasjyot Singh**  
Contact: jasjyotsingh.work@gmail.com  
