### **Amazon Sales & Profitability Report: Global Market, Product Category, and Regional Performance**

---

### **1. Project Overview**
**Project Title:** Amazon Global E-Commerce Performance Analysis
**Description:** This Power BI dashboard provides a high-level operational and financial overview of an Amazon seller's portfolio or an internal Amazon retail division. It tracks sales, profit, product variety, and quantities across multiple European and global countries. The dashboard dissects performance based on geography (Country and Region) and product categories, aiming to identify revenue drivers and profit centers across a diverse product mix.

---

### **2. Objective**
The primary objective is to centralize cross-border e-commerce data to support strategic decision-making for the business. Specific goals include:
*   **Global Footprint Assessment:** To understand product distribution and sales penetration across different countries and broad regions (North, South, Central).
*   **Financial Health Monitoring:** To track total sales revenue, total profit, and operational scale (quantity and customer count).
*   **Category Profitability Analysis:** To evaluate which product categories are driving the most sales volume vs. generating the highest profit margins.
*   **International Profitability Diagnosis:** To identify which specific countries are generating healthy profits and which countries are incurring financial losses.

---

### **3. Dashboard Features**
*   **Executive Summary KPI Cards (Top):** Six clearly defined metric cards providing an immediate snapshot: *Count of Product Name (1.488K)*, *Total Sales (2M)*, *Count of Customer Name (4.117K)*, *Sum of Quantity (30K)*, *Sum of Profit (283K)*, and *Count of Sub-Category (17)*.
*   **Product Count by Country (Top Left):** A vertical bar chart showing the *Count of Product Name by Country*. It clearly illustrates that France and Germany have the highest variety of listed products.
*   **Sales by Region (Top Right):** A pie chart breaking down *Sum of Sales by Region*. It highlights three regions: Central, South, and North.
*   **Category Volume vs. Profit (Bottom Left):** A combination (Dual-Axis) chart with a bar representing *Count of Product Name* and a line chart representing *Sum of Profit by Category*. It shows a massive disparity between Office Supplies and the other two categories.
*   **Profit by Country Trend (Bottom Right):** A line chart detailing *Sum of Profit by Country*, showing a severe negative trend as you move down the list from the top-performing countries (UK, Germany) to the bottom-performing ones (Netherlands, Sweden) which show significant losses.

---

### **4. Business Questions**
This dashboard is designed to answer the following critical business questions:
1.  In which countries does our business have the widest product assortment, and does that correlate with higher sales?
2.  Which broad geographic regions (North, South, Central) drive the majority of our total revenue?
3.  Which product category (Office Supplies, Technology, Furniture) is our primary volume driver, and does that volume translate into the highest profit?
4.  Which specific countries are our top profit generators, and conversely, which countries are bleeding money with negative profit margins?
5.  What is the overall scale of our operations in terms of active customers, order quantity, and product sub-categories offered?

---

### **5. Key Insights (Data-Driven)**
*   **Office Supplies Dominates the Portfolio:** The combination chart reveals that *Office Supplies* is the overwhelming dominant category, with **2,776** product names, compared to only 733 for Technology and 608 for Furniture. However, despite this vast product difference, Technology generates almost half as much profit as Office Supplies (79K vs 169K), indicating very high margins in the Tech sector.
*   **Market Concentration in France & Germany:** The top-left bar chart shows that the product variety is heavily concentrated in **France (991)** and **Germany (806)**. As you move down the list to countries like Denmark, Finland, and Netherlands, the product count drops to fewer than 50, suggesting a minimal presence.
*   **The "North" Region is the Revenue King:** The pie chart is highly revealing. The **North** region alone accounts for **56% (1M)** of total sales, completely dwarfing the Central (22%) and South (22%) regions.
*   **A Profitability Cliff in Europe:** The bottom-right line chart is a critical warning. While the **United Kingdom (90K)** and **Germany (85K)** are huge profit centers, the profitability drops off a cliff. By the time you reach **Sweden and the Netherlands**, the company is losing **-18K and -37K in profit**, respectively. 
*   **Inverted Relationship:** There is an interesting dynamic shown in the top-left vs. bottom-right charts. France has the highest number of products (991), yet generates less profit (47K) than the UK, which has fewer products (700) but generates nearly double the profit (90K). This suggests the UK has much higher-value or higher-margin products.

---

### **6. Tools & Technologies**
*   **Primary Tool:** Microsoft Power BI Desktop.
*   **Data Transformation:** Power Query (M Language) – used to aggregate raw e-commerce data into Country, Category, and Region groupings.
*   **Data Modeling:** DAX (Data Analysis Expressions) – used to create the calculated measures for *Sum of Profit*, *Sum of Sales*, *Count of Product Name*, and *Count of Customer Name*.
*   **Visualization Types:** KPI Cards, Vertical Bar Chart, Pie Chart, Combination Chart (Bar + Line), and a Continuous Line Chart.

---

### **7. Skills Demonstrated**
*   **Dual-Axis Charting:** Proficiency in combining two different chart types (bar and line) on the same axes to show the correlation between product volume and profit contribution per category.
*   **Dashboard Layout & UX:** Creating a well-structured, visually appealing layout with a uniform color palette (lavender/purple tones) that clearly separates summary metrics from detailed breakdowns.
*   **Global Data Presentation:** Effectively visualizing cross-border e-commerce performance across multiple countries and regions.
*   **Performance Anomaly Detection:** Using a line chart to clearly highlight the specific countries where the business is operating at a loss.
*   **Executive KPI Design:** Selecting the six most critical metrics to summarize the entire business on a single row of cards.

---

### **8. Business Value**
*   **Crisis Intervention in Northern Europe:** The sharp drop in profit shown in the bottom-right chart is the most valuable insight. It immediately flags **Sweden and the Netherlands** as "bleeding" markets. Management can immediately intervene by investigating shipping costs, import taxes, or localized pricing in these countries to stop the -18K and -37K losses.
*   **Strategic Withdrawal or Adjustment:** Because France has 991 products but only generates 47K profit, it may be an inefficient market. The company could use this data to cull underperforming products in France to streamline operations, freeing up capital to double down on the highly profitable UK and German markets.
*   **Marketing Allocation:** Knowing that the 'North' region generates 56% of all sales, the marketing budget should be overwhelmingly allocated to advertising targeted at the UK, Germany, and France, rather than wasting resources in the low-revenue 'Central' and 'South' regions.
*   **Inventory & Category Strategy:** The dashboard proves that despite having far fewer products, Technology is highly profitable (79K). This provides a clear growth roadmap: rather than flooding the market with thousands of low-margin Office Supplies, the company should focus R&D and sourcing on expanding their high-margin Technology category.
