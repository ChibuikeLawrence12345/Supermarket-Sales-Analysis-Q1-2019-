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
**Excel: Data Cleaning & Formatting**

Removed duplicate rows and checked for inconsistencies.

Ensured data types were correctly set for Dates, Times, and Currencies.

Handled minor null values and corrected time stamps for accurate hourly analysis.

**Power BI: Data Transformation (Power Query)**

Reshaped the Time column to extract hourly values for peak hour analysis.

Created new calculated columns to group and segment data by Month, Branch, Hour, and Product Line.

**Power BI: Data Modeling (DAX)**

Applied DAX to create dynamic KPIs and metrics for visual storytelling, including:

Monthly Profit Growth/Decline percentage.

Total Revenue, COGS, and Gross Income measures.

**Dashboard Creation**

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

1. Which product lines are most profitable?
2. What is the monthly sales trend in Q1?
3. When are peak shopping hours?
4. Which branches excel in specific product categories?
5. Which customer segment (member vs normal) drives the most sales?
6. How can management use this insight to increase revenue?

---

## Key Findings & Business Insights
1. **Product Performance & Profitability**
The dataset comprises 6 unique Product Lines: Food & Beverages, Sports & Travel, Electronic Accessories, Fashion Accessories, Health & Beauty, and Home & Lifestyle.

Food & Beverages generated the highest overall profit.

Branch-Specific Top-Sellers:

Branch A: Home & Lifestyle

Branch B: Sports & Travel

Branch C: Food & Beverages

2. **Temporal Analysis (Sales Trends)**
Peak Shopping Hours: Most purchases occurred in the afternoon/evening, specifically between 1:00 PM and 8:00 PM.

Monthly Trend:

February saw a significant 5.9% drop in profit compared to January.

March showed a recovery with a 3.8% increase in profit over February.

3. **Customer Segmentation**
Majority Customers: Female customers and Members accounted for the largest volume of transactions.

---

## Summary & Actionable Recommendations
Based on the analysis, the following recommendations are made to management:

**Localized Marketing**: Promote the branch-specific best-selling product lines (e.g., Home & Lifestyle in Branch A) to maximize local revenue streams.

**Staff Scheduling Optimization**: Focus staffing, restocking, and promotions during the peak hours (1 PM – 8 PM) for improved customer service, reduced wait times, and higher conversion rates.

**Seasonal Planning**: Proactively address the identified February sales slump by implementing loyalty incentives, targeted promotions, or bundling offers during that month.

**Customer Feedback**: Conduct short, branch-specific surveys to gather qualitative data on the shopping experience, helping to refine product mix and service.

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
