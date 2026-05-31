Overview
This project analyzes a retail sales dataset of 2024 orders to identify which products and regions perform best and how sales change throughout the year. The goal is to turn raw transaction data into clear, actionable business insights.# Retail-Sales-Analysis
<img width="329" height="183" alt="Screenshot 2026-06-01 004037" src="https://github.com/user-attachments/assets/5f95d7a7-1df1-428c-9302-f9d6e478296d" />
Dataset Details
 .Period: January 2024 – December 2024
 .Total Orders: 168
 .Fields: Order ID, Order Date, Customer, Segment, Region, Category, Product, Quantity, Discount, Sales, Profit, Month
Customer Segments
 .Consumer
 .Corporate
 .Home Office
Regions
 .North, South, East, West
Product Categories
 .Furniture – Bookcase, Desk, Office Chair, Sofa, Table Lamp
 .Technology – Headphones, Keyboard, Laptop, Monitor, Smartphone
 .Office Supplies – Binder, Notebook, Pens (Pack), Printer Paper, Stapler
 <img width="401" height="208" alt="image" src="https://github.com/user-attachments/assets/4e95a033-0611-4de8-8e54-effa1bc7fae0" />
.Furniture generated the highest total sales.
.Office Supplies had the strongest profit margin (22.4%) due to smaller discounts.
.Technology had the lowest margin, likely affected by heavy discounting on items like Laptops and Keyboards.
<img width="393" height="182" alt="image" src="https://github.com/user-attachments/assets/c3f051bc-484f-434a-be8f-d7368f0a5669" />
.East was the most profitable region across all metrics.
.North lagged behind with the lowest sales and the weakest profit margin.
<img width="231" height="422" alt="image" src="https://github.com/user-attachments/assets/c9327c78-47fd-42de-897e-b55a190ba5ef" />
.Sales were lowest in February and June.
.May and November were the peak months, pointing to a strong festive/end-of-year sales period.
.A clear seasonal pattern exists with a dip mid-year and a strong Q4 recovery.
4. Discount Impact
 Heavy discounts on items like Laptops (25% discount) resulted in negative profit on several orders.
 High discounting is a key profitability risk and should be reviewed, particularly in the Technology category.
 Methodology
  Collected a transactional sales dataset (orders, customers, regions, categories, sales, and profit).
  Cleaned and prepared the data: checked for duplicate orders, blank values, and ensured dates, sales, and profit were in   correct numeric/date formats.
  Built summary tables using SUMIF and AVERAGEIF formulas to total sales and profit by category, region, and month.
  Created bar and line charts to visualize the findings as a simple dashboard.
Tools Used
 Microsoft Excel / Google Sheets – data cleaning, SUMIF/AVERAGEIF formulas, pivot-style summary tables, and charts.
How to Use This File
 Open the Sales Data tab to explore or update the raw transaction data.
 Open the Analysis tab to view summary tables and charts — these update automatically if the data changes.
 Refer to the Summary tab for a quick project overview and the top-level findings.
