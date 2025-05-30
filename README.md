# Inventory-Aging-Stock-
🌼 **Inventory Management Dashboard**
A comprehensive Power BI dashboard designed to streamline inventory management by tracking stock levels, aging analysis, and product-level insights across multiple warehouses and distribution centers. This dynamic reporting solution empowers supply chain and operations teams to make data-driven decisions and optimize inventory planning.

📌 **Short Description / Purpose**
The Inventory Management Dashboard is a decision-support tool that visualizes key inventory metrics, including aging analysis, stock distribution, and product-level details. It enables quick identification of slow-moving and aged inventory, ensuring timely replenishment and efficient stock management.

⚙️ **Tech Stack**
The dashboard was built using the following tools and technologies:
📊 **Power BI Desktop** – Core platform for interactive data visualization and analysis.
📂 **Power Query** – ETL tool for cleaning and transforming data sources.
🧠 **DAX (Data Analysis Expressions)** – Used for creating measures, KPIs, and advanced calculations.
🧱 **Data Modeling** – Established relationships across warehouse, product, and aging data to enable seamless filtering.
📁 **File Format** – .pbix (Power BI file) and .png for dashboard previews.

🗂 **Data Source**
Data was structured to reflect real-world operational needs using the following datasets:

* **Warehouse Data**: Stock levels, aging buckets, and warehouse location.
* **Product Data**: Product ID, group, brand, and stock levels by aging.
* **Inventory Aging Data**: Historical inventory movement and status.

🌟 **Features / Highlights**
• **Business Problem**
Inefficient inventory tracking and lack of visibility into aged stock can result in stockouts, excess holding costs, or obsolete items. This dashboard addresses these issues by providing real-time insights into inventory health and product movement.

• **Goal of the Dashboard**
To empower the operations team with actionable insights that:

* Highlight stock aging across multiple time buckets (1-3 months, 4-6 months, etc.).
* Track warehouse-level stock distribution.
* Identify slow-moving and overstocked products.
* Support data-driven decisions for reordering and stock optimization.

• **Walkthrough of Key Visuals**
🟣 **Warehouse-Level Stock Overview (Left Side)**
Circular visuals display total stock by warehouse (e.g., Apsis Logistic, Basalt Distribution, Ceres Warehouse) for quick comparative analysis. Each visual is color-coded by product group.

🟧 **Aging Analysis (Top Center)**
Inventory aging buckets highlight stock levels across different time frames:

* 1-3 Months
* 4-6 Months
* 7-9 Months
* 10-12 Months
* Beyond 12 Months
  This helps identify slow-moving and obsolete stock.

🔗 **Sankey Diagram (Middle)**
Visualizes the flow of stock across aging groups, product groups, and brands, illustrating where most inventory is concentrated and helping identify bottlenecks.

📈 **Detailed Product Inventory Table (Bottom Right)**
Displays product-level details such as:

* Inventory Quantity
* Safety Stock & Reorder Point
* Next Order Delivery Date
* Status (e.g., Below Safety Stock, Above Reorder Point)
  This table enables granular analysis for precise replenishment decisions.

📊 **Interactive Filters (Top Left)**
Allow users to drill down by:

* Location
* Brand
* Product Group
* Product

📌 **Stock Trend Visualization (Top Right)**
Shows sales or stock trends over the past 12 months, helping identify seasonal fluctuations and trends.

• **Forecast Analysis**
The dashboard integrates aging-based analysis with reorder points, ensuring timely restocking and reducing risk of stockouts. DAX measures ensure dynamic recalculation as users filter by warehouse, brand, or product group.

• **Business Impact & Insights**
✅ **Proactive Inventory Planning**: Identify slow-moving products and plan for clearance or marketing.
✅ **Warehouse Optimization**: Allocate resources effectively by analyzing warehouse-level stock.
✅ **Reduced Obsolescence Risk**: Clear insights into aged stock allow for timely action.
✅ **Operational Efficiency**: Improve reorder planning and avoid overstocking.
![Stock](https://github.com/user-attachments/assets/be9fd010-5624-4527-8272-245c128e160f)
![Aging](https://github.com/user-attachments/assets/dd87c7a4-4096-41e7-954d-6876f24ffe45)
