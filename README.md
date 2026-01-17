<h1 align="center">🏬 OmniMart Sales & Customer Analytics Project (Excel, Power Query)</h1>

An end-to-end Excel and Power Query analytics project analyzing OmniMart’s sales performance, customer segmentation, and churn patterns.  
This project demonstrates how Excel can be used as a complete analytics tool. From data transformation to insight generation and storytelling through dashboards.                
##
### OVERVIEW -  
The OmniMart dataset contained over **60,000 transactional records** across **four relational tables** — Customer, Product, Sales Territory, and Fact_Internet_Sales — covering the period **2005 to 2008**.

The goal was to transform raw data into actionable insights that would help OmniMart:
- Understand sales performance and profitability across regions and products  
- Identify customer churn and behavioral patterns  
- Improve retention through targeted strategies  
- Build interactive dashboards for decision-making  

### BUSINESS CONTEXT -
OmniMart is a multinational retail supermarket dealing in a wide range of consumer goods, from groceries and electronics to household essentials.  
Despite generating over **$50 million annually** and expanding its customer base by **1,023%** between 2005–2008, the company faced a significant **customer retention problem**.

- Only **21%** of customers were active  
- **39%** were at risk of churning  
- **40%** were about to churn  

This project explores how data analytics can help OmniMart increase its active customer base, reduce churn, and sustain long-term revenue growth.

### PROJECT GOAL -  
To perform a complete **data transformation, analysis, and visualization** workflow in Excel to:
1. Identify churn patterns and customer risk levels  
2. Discover top-performing countries, products, and customer groups  
3. Visualize key sales and retention KPIs using dynamic dashboards  
4. Recommend data-driven strategies to boost revenue and customer engagement  

### DATA PREPARATION & TRANSFORMATION (Power Query) -
The raw dataset was cleaned, merged, and enhanced in **Power Query** using four tables:
- **Customer Table:** demographic details (name, gender, education, income, etc.)  
- **Product Table:** product name, cost, and price details  
- **Sales Territory Table:** geographic information of customers  
- **Fact_Internet_Sales:** sales transactions, order quantity, and foreign keys  

### Key Transformations:
- Merged all tables using primary keys  
- Removed duplicates and trimmed extra spaces  
- Created calculated columns:  
  - **Total Revenue** = `Order Quantity × Unit Price`  
  - **Total Cost** = `Order Quantity × Product Cost`  
  - **Profit** = `Total Revenue – Total Cost`  
  - **Days Since Last Purchase** using `MAXIFS` and `DAYS` functions  
  - **Customer Status** (Active, At Risk, About to Churn) via **Percentile Analysis**  
  - **Age Group** and **Income Category** using nested `IF` logic  
##
### 📊 DASHBOARD DESIGN

### 🧾 Sales Dashboard
Focused on performance metrics:
- Total Revenue, Profit, Quantity, and Cost  
- Top-selling products  
- Revenue by Country and Quarter  
- Month-over-Month (MoM) and Year-over-Year (YoY) Revenue Trends  

### 👥 Customer Dashboard
Focused on customer behavior:
- Customer segmentation by status (Active, At Risk, About to Churn)  
- Revenue by Gender, Education, and Income Group  
- Customer population by Country  
- Interactive slicers for deeper exploration  

Both dashboards were styled for clarity and usability, featuring **BANS/KPIs**, color-coded visuals, and dynamic slicers.
##
### KEY INSIGHTS

### 🔹 Sales Insights
- OmniMart generated **$307.1M** in revenue and **$126.3M** in profit between 2005–2008.  
- **United States and Australia** accounted for **62%** of total revenue.  
- **Mountain-200** product line contributed **22%** of total revenue.  
- **Q2** had the highest revenue ($94.7M), while **Q1** had the highest profit ($78.4M).  

### 🔹 Customer Insights
- Only **21%** of customers are active.  
- **49%** are at risk of churning, while **30%** are about to churn.  
- **Bachelor’s degree holders** had the highest average revenue per customer ($19.2K).  
- Customers aged **30–39** generated the most revenue (26%).  
- **Married customers** contributed slightly higher revenue (+2.4%) than singles.  
##
### CHURN ANALYSIS MODEL
Churn risk was determined using **percentile segmentation** on the “Days Since Last Purchase” metric.

| Percentile | Days Since Last Purchase | Category        | Description |
|-------------|--------------------------|-----------------|--------------|
| ≤ 25th      | ≤ 73 days                | Active          | Engaged customers |
| 25th–75th   | 74–241 days              | At Risk         | Irregular buyers |
| > 75th      | > 241 days               | About to Churn  | Dormant customers |

This helped classify each customer and identify segments needing re-engagement or loyalty strategies.
##
### BUSINESS RECOMMENDATIONS
- Introduce **loyalty and reward programs** to increase repeat purchases.  
- Use **personalized marketing** (emails, discounts) to re-engage at-risk customers.  
- Conduct **customer satisfaction surveys** to identify pain points.  
- Offer **tier-based incentives** for consistent buyers.  
- Continuously monitor churn metrics via dashboards.  

If OmniMart can increase active customers from 21% to 50%, revenue could grow by **25%** within the next 12 months.
##
### 📈 METRICS TO TRACK
- Active Customer Rate  
- At-Risk Customer Rate  
- Churn Rate  
- Retention Rate  
- Average Revenue per Customer  
- Monthly and Yearly Revenue Growth  
##
### TOOLS & SKILLS USED
- Microsoft Excel  
- Power Query  
- Pivot Tables  
- Data Cleaning & Transformation  
- Percentile Analysis  
- Dashboard Design & Visualization  
- Business Storytelling  
##
### 📂 REPOSITORY CONTENT
| Folder | Description |
|--------|-------------|
| `/datasets` | Raw and cleaned data files |
| `/dashboard` | Excel dashboards (Sales & Customer) |
| `/documentation` | PDF report and methodology explanation |
| `/images` | Dashboard and insight screenshots |
##
### 📊 RESULT IMAGES
 🧾 Sales Dashboard  
*(Insert Screenshot Here)*  

 👥 Customer Dashboard  
*(Insert Screenshot Here)*  
##
### CONCLUSION
This project demonstrates how Excel, when combined with Power Query and structured thinking, can uncover meaningful business insights beyond just numbers.  
It highlights that **revenue growth doesn’t always come from new customers — it often lies in keeping the ones you already have.**

---

### Author
👤 **Okoli Ebuka Francis**  
💼 Data Analyst | Excel | SQL | Power BI | Storytelling  
🔗 [LinkedIn](https://linkedin.com/in/ebukaokoli)

