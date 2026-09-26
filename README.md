# Retail-sales-performance-and-customer-demographics
An end-to-end executive Power BI analytics solution designed to evaluate revenue metrics, product profitability, customer demographics, and regional sales distribution. Built with a star-schema data model, custom DAX measures, and a high-contrast dark-mode executive UI/UX.
Executive Summary and key insights:
**Gross Revenue:** Achieved a gross revenue of $3.0M in Total Sales across core retail categories.
* Cost-Benefit Analysis:** Total Cost stood at $2.17M, yielding a Net Profit of approximately $932K.
* **Product Performance:** product groups that generated the highest total financial return were driven by high-margin electronics and accessories, with distinct profit variances across major brands.
* **Customer Demographics:** Maintained a stable active customer base of **~250 buyers/month**, with strong buying power concentrated across medium-to-high income brackets.

  Data Architecture & Modeling
The project uses a **Star Schema** relational design connecting the central Fact table with normalized Dimension tables to optimize performance and slicer filtering:

* **Fact Table:** `Sales` (SalesID, ProductID, CustomerID, Quantity, SalesDate, SalesAmount, UnitCost, Total cost, Profit, Total customers, Total Sales.)
* **Dimension Tables:** `Products` (Brand, Category, Color, Product ID, Product Name, Weight.), `Customers` (Region, Income Level, signupDate, Customer ID, Customer Name.)

  Interactive Features
Multi-Page Executive Layout:

Overview: High-level executive summary featuring core KPIs, regional performance, brand profit donut charts, and monthly revenue trends.

Product & Customer Details: Granular breakdown of sales by product color, profit by income level, and monthly active customer trends.

Custom Navigation & Tooltips: Embedded custom report-page hover tooltips providing instant on-demand product breakdowns without cluttering the main canvas.

Synced Slicers: Global Region and Category filters synced seamlessly across all pages.

<img width="1920" height="1080" alt="Screenshot (47)" src="https://github.com/user-attachments/assets/c84b89d7-8c78-471a-9971-3213554e0b25" />

