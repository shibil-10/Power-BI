Global E-Commerce Sales Dashboard

An interactive Power BI dashboard analyzing 2,000 orders from a global e-commerce dataset (Jan 2023 – Dec 2025), covering sales performance, profitability, and customer/product trends across 5 regions.

<img width="1307" height="733" alt="image" src="https://github.com/user-attachments/assets/e293aa30-74fa-478a-9642-bc6f934270c1" />


Overview

This dashboard turns raw order-level transaction data into a decision-ready view for sales, regional, and product performance — built end-to-end in Power BI, from data modeling to DAX measures to visual design.

Dataset: 2,000 orders | Jan 2023 – Dec 2025 | 15 fields (Order ID, Date, Customer, Segment, Country, Region, Category, Product, Quantity, Unit Price, Discount %, Sales, Shipping Cost, Profit, Payment Method)

Tools & Skills


Power BI Desktop — data modeling, DAX, report design
Power Query (M) — data import and type transformation
DAX — custom measures (Profit Margin, Average Order Value)
Excel — Clean dataset
Kaggle — Source dataset 


Key Insights


Total sales of $484,559 across the period, with an overall profit margin of ~33%
Furniture is the leading category by revenue ($256K), more than double Technology, the next closest category
Consumer segment drives over half of total sales ($256K of $484K), ahead of Corporate and Home Office
Europe and North America are neck-and-neck as the top two regions by sales, with Asia Pacific close behind
Mexico, Canada, and the United States are the top three countries by individual sales volume
Credit Card is the dominant payment method (~40% of orders), followed by PayPal
13.6% of all orders (272 of 2,000) were sold at a loss — a segment worth a closer look for pricing or discount strategy


Dashboard Features


KPI summary cards: Total Sales, Total Profit, Profit Margin, Total Orders, Average Order Value
Sales trend over time (monthly)
Sales breakdown by Region, Category, Country (Top 10), Segment, and Payment Method
Profit by Category
Order-level detail table with customer, product, and payment information
Interactive slicers: Order Date, Region, Category, Segment


Repository Structure

Gloabl ecommerce-sales-dashboard/
├── README.md
├── E-Commerce_Sales_Project.pbix
└── global_ecommerce_sales_power_bi.xlsx


How to Use

Download E-Commerce_Sales_Project.pbix and open it in Power BI Desktop (free).
The data is embedded in the file, so it opens and displays immediately — no setup needed to view it.
To refresh the data with your own source file: in Power BI Desktop, go to Transform Data → Data Source Settings, and repoint it to your local copy of global_ecommerce_sales_power_bi.xlsx.


About Me

I'm transitioning into data analytics from a background in English Literature — a path that's shaped how I approach this kind of work: not just building charts, but framing the story a dataset is telling. This project reflects that — translating raw transaction data into a narrative a business stakeholder can act on.

LinkedIn: www.linkedin.com/in/muhammed-shibil-k-7039ba399

⭐ If you found this project useful, consider giving it a star!
