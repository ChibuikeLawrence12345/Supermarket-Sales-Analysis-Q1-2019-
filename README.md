# Supermarket Sales Analysis Q1 2019

## Project Goal
To use sales transaction data to uncover key insights and provide actionable recommendations for optimizing sales performance and profitability across three supermarket branches (A, B, and C) during the first quarter of 2019.

---

## Introduction & Problem Statement
This project explores three months (Jan–Mar 2019) of point-of-sale transaction data.

The management team sought to answer crucial questions regarding product performance, customer behavior, and branch-specific improvements. The core challenge was transforming the raw data into an interactive dashboard to drive strategic business decisions, despite the limited three-month scope.

---

## Dataset Details
Source: Simulated client data challenge (Downloaded from Kaggle)

Rows: 1,001

Columns: 17

Key Fields: Invoice ID, Branch, Gender, Product Line, Unit Price, Quantity, Total, Date, Time, Payment Method, COGS, Gross Margin, Gross Income, Rating.

---

##  Tools Used
- **Excel**: Data Cleaning, Formatting
- **Power BI**: Power Query, DAX, Interactive Dashboards
- **Techniques**: Time Series Analysis, Customer Segmentation, Profitability Analysis

---

## Technical Implementation
- **Excel: Data Cleaning & Formatting**

Removed duplicate rows and checked for inconsistencies.

Ensured data types were correctly set for Dates, Times, and Currencies.

Handled minor null values and corrected time stamps for accurate hourly analysis.

- **Power BI: Data Transformation (Power Query)**

Reshaped the Time column to extract hourly values for peak hour analysis.

Created new calculated columns to group and segment data by Month, Branch, Hour, and Product Line.

- **Power BI: Data Modeling (DAX)**

Applied DAX to create dynamic KPIs and metrics for visual storytelling, including:

Monthly Profit Growth/Decline percentage.

Total Revenue, Average Transaction Value-ATV, and Gross Income measures.

- **Dashboard Creation**

Built an interactive Power BI dashboard featuring key analysis views.

---

## Project Structure

supermarket-sales-analysis/
├── datasets/
│ └── supermarket_sales_Q1_2019.csv
├── excel/
│ └── cleaned_sales_data.xlsx
├── powerbi/
│ └── supermarket_sales_dashboard.pbix
├── visuals/
│ ├── dashboard_overview.png
│ ├── monthly_sales_trend.png
│ └── peak_hours_chart.png
└── README.md

---

## Business Questions

1. **Product Performance**: What are the unique product lines, and how do they perform in terms of sales and profit across the three branches?
2. **Sales Trends**: What are the monthly sales trends for Q1, and how did profitability fluctuate between January and March?
3. **Peak Hours**: At what times of the day does the supermarket experience the highest volume of transactions?
4. **Profitability vs Satisfaction**: Which product lines are the most profitable, and how does their profitability correlate with their average customer ratings?
5. **Untapped Potential**: Are there specific categories—like Sports & Travel—that have low satisfaction scores but high profit, indicating a major opportunity for growth?
6. **Branch Payment Profiles**: How do payment preferences (Cash, Ewallet, Credit Card) differ across Branch A, B, and C, and what does this tell us about local customer behavior?
7. **Transaction Value**: What is the Average Transaction Value (ATV) for each payment method, and which method brings in the highest spend per visit?
8. **Customer Segmentation**: Who are our primary customers in terms of gender and membership status?
9. **Actionable Strategy**: Based on these findings, what specific operational changes can be made to improve staffing, marketing, and inventory management?
    
---

## Key Findings & Business Insights
1. **Branch-Specific Profit Leaders**: The dataset comprises 6 unique Product Lines: Food & Beverages, Sports & Travel, Electronic Accessories, Fashion Accessories, Health & Beauty, and Home & Lifestyle.
Each branch has a unique top-performing product line: Branch A is led by Home & Lifestyle, Branch B by Sports & Travel, and Branch C by Food & Beverages.

2. **High Profit, Low Satisfaction**: Sports & Travel and Electronic Accessories are the 2nd and 3rd most profitable lines despite having the lowest satisfaction ratings (~6.92); closing the quality gap to match Food & Beverages (7.11) could unlock enough growth to make them the store's overall profit leaders.

3. **Localized Payment Cultures**: Branch B is a hub for high-value Credit Card transactions, and Branch C is dominated by Ewallet users, while Branch A shows a perfectly balanced demand across all payment types.

4. **Peak Performance Window**: Most sales activity and customer volume occur consistently during the afternoon and evening hours between 1:00 PM and 8:00 PM.

5. **Sales Volatility**: Profitability dropped by 5.9% in February but showed a healthy recovery of 3.8% in March.
Food & Beverages generated the highest overall profit.

6. **The Power of ATV**: Branch Insights
Branch A (Balanced Consumption): ATV is consistent across all payment types, indicating a general-purpose shopping behavior where no single payment group outspends the others.

Branch B (The "Big Spender" Hub): Credit Card users show the highest ATV despite lower transaction frequency, confirming that "high-ticket" purchases (like Sports & Travel) are tied to credit use.

Branch C (The "High-Frequency" Hub): Lower ATV paired with high volume in Ewallet/Cash reveals a customer base focused on frequent, smaller "daily necessity" trips (primarily Food & Beverages).

---

## Summary & Actionable Recommendations
Based on the analysis, the following recommendations are made to management:

**Localized Inventory & Marketing**: Tailor promotional displays and stock levels to match branch strengths (e.g., Home & Lifestyle in Branch A) to maximize revenue where demand is already highest.

**Targeted Quality Audits**: Perform deep-dive reviews of top-selling items in Sports and Electronics to resolve friction points, as converting current dissatisfaction into loyalty is the fastest path to exceeding current profit ceilings.

**Branch-Specific Checkout Optimization**: Tailor lane configurations by branch: deploy Ewallet-only express lanes in Branch C to accelerate digital volume, introduce Priority Member lanes in Branch B to enhance the experience for high-spend Credit Card users, and maintain Flexible Universal lanes in Branch A to prevent bottlenecks across its evenly split payment methods.

**Optimized Staffing**: Shift more staff and restocking activities to the 1:00 PM – 8:00 PM window to improve customer service and conversion rates during peak traffic.

**Seasonal Slump Mitigation**: Launch aggressive "February-Only" bundling offers or loyalty incentives to counteract the identified mid-quarter dip in profit.

**ATV-Driven Upselling**: Branch specific
Branch A (Volume Growth): Since spending is balanced, implement "Multi-Buy" promotions (e.g., Buy 3 Get 1 Free) to increase the average basket size across the entire branch.

Branch B (Premium Upselling): Leverage the high-spend credit demographic by bundling premium accessories with the top-performing Sports & Travel gear to push the ATV ceiling higher.

Branch C (Impulse Merchandising): To raise the lower ATV, place high-margin "add-ons" (batteries, snacks, or small travel items) near Ewallet-heavy registers to encourage "basket-building" during quick daily runs.

---

## What I Learned

- Data cleaning and transformation in **Excel** and **Power Query**  
- Building dynamic KPIs using **DAX** in Power BI  
- Designing interactive dashboards for **business storytelling**  
- Extracting actionable insights to guide marketing and operations decisions

---

## Project Links

- [Interactive Power BI Dashboard](https://app.powerbi.com/Redirect?action=openreport&context=Annotate&ctid=47d41471-806d-482c-8d78-5451c5f2cbd5&pbi_source=mobile_android&groupObjectId=6c9c919a-2234-4e67-9354-bcbba25aca17&reportObjectId=e5ef80cb-8edb-4ed2-84ae-368df69b9146&reportPage=ReportSection&bookmarkGuid=fb087f24-0518-46f8-a380-529b876b6eff&fullScreen=0
)  
- [Excel Data File](https://1drv.ms/x/c/e1781590a66dcd43/EW0huXw_s9dNntqoIoGSEXcBiV9FotwW8QvDIXOCrTCKgw?e=eWXYWj&nav=MTVfezAwMDAwMDAwLTAwMDEtMDAwMC0wMDAwLTAwMDAwMDAwMDAwMH0)    
- [Visuals/Charts](https://drive.google.com/drive/folders/1NdGgWc8J6n9fVjZZmmMhK7lARYIoeWqA?usp=drive_link)

---

## Contact
**Email** [lawchibuike12345@gmail.com]

**LinkedIn** [https://www.linkedin.com/in/chibuike-lawrence-2348b01b6]

**GitHub** [https://github.com/ChibuikeLawrence12345]
