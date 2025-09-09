# Data-Driven-Insight-into-Sales-Performance-and-Delivery-Optimization---GreenCart-Ltd

## 📌 Project Overview
This project analyzes customer behavior, sales performance, and delivery efficiency for **GreenCart Ltd**, an online retail company.  
By merging **three datasets** — `customer_info.csv`, `product_info.csv`, and `sales_data.csv` — the project delivers **data-driven insights** into:

- Revenue performance across categories and regions  
- Impact of discounts on sales volume  
- Customer loyalty tier contributions  
- Delivery efficiency and pain points  

The analysis combines **Exploratory Data Analysis (EDA)**, **feature engineering**, and **business reporting** to provide recommendations that can improve sales, customer satisfaction, and operations.

## 🎯 Project Objectives
- Identify top-performing product categories and regions  
- Assess the impact of **discounts** on sales  
- Understand how **loyalty tiers** affect revenue  
- Evaluate **delivery performance** across regions and product price bands  
- Provide **actionable business recommendations** based on findings  

## 🛠️ Tools & Technologies
- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn  
- **Environment:** Jupyter Notebook, Visual Studio Code  

## 📊 Project Files
- 📂 **Datasets**  
  - [`customer_info.csv`](customer_info.csv)  
  - [`product_info.csv`](product_info.csv)  
  - [`sales_data.csv`](sales_data.csv)  

- 📘 **Jupyter Notebook**  
  - [`GreenCart_Sales_Analysis.ipynb`](GreenCart_Sales_Analysis.ipynb)  

- 🖼️ **Visuals (EDA Outputs)**  
  - [`Weekly Revenue by Region`](weekly_revenue_by_region.png)  
  - [`Top 5 Product Categories by Revenue`](top_5_categories.png)  
  - [`Discount Distribution by Category`](discount_distribution_across_product_categories.png)  
  - [`Correlation Heatmap`](correlation_revenue_discount_quantity.png)  
  - [`Customer Orders by Loyalty Tier & Region`](customer_orders_by_loyalty_tier_region.png)  
  - [`Delivery Status by Price Band`](delivery_status_by_price_band.png)  

- 📑 **Business Report**  
  - [`GreenCart_Business_Report.pdf`](GreenCart_Business_Report.pdf)  

## 📊 Datasets & Merging
- `customer_info.csv` – customer signup details and loyalty tiers  
- `product_info.csv` – product categories, pricing, and attributes  
- `sales_data.csv` – order transactions and delivery status  

# Merging steps:
1. `sales_data` joined with `customer_info` on **customer_id**  
2. Resulting dataset joined with `product_info` on **product_id**  

## 🔍 Analysis Performed
- **Data Cleaning & Standardization**  
  - Removed duplicates, handled missing values, standardized text, and parsed dates.  
- **Feature Engineering**  
  - Revenue per order  
  - Price bands (Low, Medium, High)  
  - Delivery performance flags  
  - Customer signup-to-order interval  

- **Exploratory Data Analysis (EDA):**  
  - Weekly revenue trends across regions (line plot with colored points)  
  - Top 5 product categories by revenue (bar plot)  
  - Discount distribution across categories (box plot)  
  - Correlation heatmap between revenue, discount, and quantity  
  - Customer orders by loyalty tier and region (count plot)  
  - Delivery status by price band (stacked bar chart)  

## 📈 Key Insights
1. **Top Product Categories** – Cleaning, Storage, Outdoors, Kitchen, and Personal Care contributed the most revenue.  
2. **Regional Sales** – Revenue was highest in the **West and South regions**.  
3. **Discounts** – Discounts above **20% boosted sales volumes**, but margins need careful monitoring.  
4. **Customer Loyalty** – **Gold tier** customers generated the highest revenue, despite being fewer in number.  
5. **Delivery Performance** – The **Central region** recorded the most delayed deliveries; high-price products had a higher chance of being delivered successfully.  

## 💡 Recommendations
- Focus promotions (especially discounts) on **top categories** in the West and South for maximum ROI  
- Strengthen **logistics** in Central and North regions to reduce delivery delays  
- Enhance **Gold-tier loyalty perks** to maintain and grow high-value customer spending  
- Monitor discount strategies to balance **sales growth** with **profit margins**  

## 🚀 How to Run the Project
   – Download ZIP (easiest) 
   - Click the green **Code** button on this repo → **Download ZIP**.  
   - Unzip the folder to your computer.  
   - Open the `.ipynb` notebook in **Jupyter Notebook** or **VS Code**.  

## Conclusion
This project demonstrates how EDA and feature engineering can uncover actionable business insights from raw datasets.
By analyzing customer behavior, sales performance, and delivery operations, the study highlights opportunities to improve revenue growth, customer loyalty, and logistics optimization.
 
