# 📊 Sales Report Dashboard (Power BI)

**1. Project Title :** _Sales Performance Analysis Dashboard_

An interactive Power BI report designed to explore global sales trends, analyze customer behavior, track YoY growth, and compare performance across products, categories, and regions.

**2. Purpose:**

- The Sales Dashboard provides deep, visual insights into total sales, prior year performance, customer driven revenue patterns, and regional market contributions.
- It helps business teams monitor performance, identify top contributors, track monthly trends, and compare current vs. previous year sales instantly.

**3. Tech Stack:**

The dashboard was built using the following tools and technologies:

- Power BI Desktop : Main platform for dashboard development

- Power Query : Data cleaning, transformation & aggregation

- DAX (Data Analysis Expressions) : Used for KPIs, YoY calculations, and trend analysis

- Data Modeling : Fact tables and dimension tables linked for smooth filtering

- File Formats : .pbix for development, .png for dashboard preview


**4.Data Source:**

Microsoft Sample Sales Dataset 

The dataset consists of:

Key Tables

Fact Sales – Sales Amount, Order Date, Product Key, Customer Key

Dim Customer – Customer name, occupation, location

Dim Product – Category, subcategory, product name

Dim Date – Calendar hierarchy


**5. Features:**

**Business Problem:**

Businesses struggle to analyze multi-dimensional sales data and quickly answer:

1. Which countries generate the highest revenue?

2. Which products drive most sales?

3. How does current year performance compare to prior year?

4. Who are the top customers and top products?

5. What trends appear over the months?


**Goal of the Dashboard:**

To create a single-screen analytical tool that:
- Tracks total yearly sales & YoY change
- Highlights top countries, categories, and customer segments
- Compares current vs. prior-year trends
- Shows monthly seasonal patterns
- Helps sales teams make data-driven decisions


**Walkthrough of Key Visuals:**

**i) KPI Tiles (Top Panel)**

- Total Sales

- Sales Prior Year

- YoY Sales Change

- YoY % Change

These KPIs update dynamically based on slicer selections.

**ii) Total Sales by Country (Bar Chart):**

Compares performance across major markets such as United States, Australia, United Kingdom helps identify high-value regions.

**iii) Total Sales by Category:**

Visual breakdown of revenue contribution from Bikes, Accessories, Clothing. Bikes usually dominate total sales.

**iv) Top Customers Table:**

Displays:

Customer Name

Total Sales contributed

Useful for customer relationship & target strategy.

**v) Sales Trend (Current vs Prior Year):**

Line chart comparing current year performance against previous year. Shows growth patterns, seasonality, and performance gaps.

**vi) Total Sales by Occupation (Donut Chart):**

Reveals spending behavior across: Professional, Skilled Manual, Management, Clerical, Manual workers which helps in customer segmentation.

**vii) Top Products Table:**

Shows high-performing models such as: Road-150 Red, Mountain-200 Silver, Mountain-200 Black which is useful for inventory, marketing, and forecasting.


**Business Impact & Insights**

1. Strategic Sales Planning: Identify high-profit regions & product lines

2. Marketing Decisions: Target high-value customer occupations

3. Inventory Optimization: Understand product demand trends

4. Revenue Growth Tracking: YoY comparison drives performance insights

5. Customer Strategy: Recognize top customers to improve loyalty


**6. Screenshot:**
![Sales Dashboard]([<your-dashboard-image-path>](https://github.com/Janhavilele/Sales-Dashboard/blob/main/Sales%20Dashboard.PNG))
