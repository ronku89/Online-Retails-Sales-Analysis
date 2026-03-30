# Online Retail Sales Analysis

This project performs a deep-dive Exploratory Data Analysis (EDA) on an Online Retail dataset to uncover key business insights, customer behavior patterns, and sales trends. The goal is to provide actionable recommendations for marketing and inventory management.

## 🛠️ Technical Toolkit
* **Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn (Custom Heatmaps & Bar Charts)
* **Environment:** VS Code / Jupyter Notebook

## 🔍 Key Business Insights

1. **Data Cleaning & Integrity:** Applied **99th percentile capping (Winsorization)** on Quantity and Price to handle extreme outliers and ensure realistic analysis.
2. **Segmentation Logic:** Separated **Guest and Registered customers** to better understand loyalty and repeat purchase behavior.
3. **Data Accuracy:** All business insights were derived strictly from **Completed/Sold orders** by filtering out cancellations.
4. **Market Dominance:** Identified the **United Kingdom (UK)** as the primary revenue generator and dominant market.
5. **Revenue Milestone:** The business achieved a total sales volume of approximately **£1.74 Crore**.
6. **Seasonal Trends:** Observed a massive sales surge during the **Q4 peak season (Sept-Nov)**, driven by Christmas shopping.
7. **Weekly Performance:** Identified **Tuesday and Thursday** as the highest traffic days, while weekends showed significantly lower engagement.
8. **Peak Shopping Hours:** Customer activity peaks daily between **12:00 PM and 3:00 PM**, suggesting the best window for marketing campaigns.
9. **Customer Loyalty:** Strong retention was noted, with **80% of total users being Registered** members.
10. **Pricing Strategy:** Most top-selling products are budget-friendly, falling within the **£0.1 to £4** price range.
11. **Order Profile:** The typical order size (**Median**) is **132 units** per invoice, with an **Average Order Value (AOV) of £416**.
12. **Sales Distribution:** The data shows a **Right-Skewed Distribution**, where frequent mid-sized orders drive the bulk of the volume.
13. **Operational Health:** Maintained an impressive **3% Cancellation/Return rate**, which is very healthy for the retail industry.
14. **Correlation Insight:** Found a strong positive correlation between Quantity and Total Sales, confirming that volume is the primary revenue driver.

## 🚀 Conclusion
The analysis highlights a stable business with high customer loyalty in the UK. Focusing on Q4 inventory and mid-day marketing during weekdays can further optimize revenue.

