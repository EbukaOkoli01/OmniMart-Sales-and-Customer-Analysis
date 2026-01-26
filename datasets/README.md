# 📊 Dataset Overview

This folder contains the datasets used for the **OmniMart Sales and Customer Analysis** project.  
The data represents transaction and customer information for OmniMart, a global retail store, between **2005–2008**.

### 📁 Files Included
- **OmniMart_Raw_Data.xlsx** – Original dataset containing customer, product, and sales details.  
- **OmniMart_Cleaned_Data.csv** – Transformed dataset after cleaning and merging through Power Query in Excel.  

### 🧩 Key Data Tables
| Table | Description |
|--------|-------------|
| Customer | Demographic data such as name, age, gender, education, income, and marital status. |
| Product | Product details including category, unit price, and standard cost. |
| Sales Territory | Information about customer countries and regions. |
| Fact_Internet_Sales | Transaction-level data with order quantity, dates, and keys linking other tables. |

### ⚙️ Data Preparation Summary
- Duplicates removed and column headers standardized.  
- Null values handled and irrelevant columns dropped.  
- Data merged using **Power Query** via primary and foreign key relationships.  

Note - This cleaned dataset was later used to build the **Sales** and **Customer** dashboards.
