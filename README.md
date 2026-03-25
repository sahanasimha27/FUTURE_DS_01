# business-sales-performance-analysis
Retail sales performance dashboard with insights and business recommendations using Power BI


# 📊 Retail Sales Performance Analysis Dashboard

## 📌 Project Overview
This project involves analyzing historical retail sales data to uncover meaningful business insights. Using Microsoft Power BI, the analysis focuses on understanding trends in revenue, profit, product performance, regional sales, and shipping efficiency. The dashboard is designed to support data-driven decision-making for business owners or managers looking to improve performance and growth strategy.

The dataset used is the **Superstore Sales Dataset**, which contains transactional data from 2011 to 2014. Key dimensions include products, categories, customer segments, regions, shipping modes, and order priorities.
- The sales is between the period of 2011 to 2014
   ![image](https://user-images.githubusercontent.com/103464406/218605670-7fe2f56e-7cc7-433e-9a09-fd0b655195aa.png)

## Dashboards:

### Sales Analysis Dashboard:
- Sales department can analyze sales and profit through this dashboard. Filter through years and quarterly sales.
- The company has made a Total Sales of 3 million and Total Profit of 400.9K between 2011- 2014.
- 1 million worth of sales and 119.11K profit was made in 2014.
- 46% of profit came from product category technology.
- Year 2014 March and April has seen high sales revenue and December being the holiday Season has the lowest revenue sales.
    ![image](https://user-images.githubusercontent.com/103464406/218605834-500b9b47-8873-4b4a-94ae-ed86486e3194.png)
- Filter for year 2014, category: technology, Order Priority: Medium
    !![image](https://user-images.githubusercontent.com/103464406/218607224-3a1bf219-c16f-44cb-bb8e-4e7b0ee22838.png)


### Product Analysis Dashboard:
- This dashboard dive deep into product categories, quantity ordered, product- subcategory
-  Highest amount of office supplies have been ordered in terms of quantity.
-  Tables have been sold at an average discount of 28% in 2014
   ![image](https://user-images.githubusercontent.com/103464406/218607609-fcf817e6-17a1-4b03-af50-00bbe806ad79.png)
- Filter year: 2014, market: US
    ![image](https://user-images.githubusercontent.com/103464406/218608118-393e40ea-9f77-46f2-9826-82f7be538d1d.png)

### Shipping Analysis Dashboard:
- 53% of the orders have Standard shipping mode and lowest preferred is same day shipping.
- 41% of Orders with critical order priority have been ordered by firstclass ship mode.
- 100 % of the orders with low priority have been ordered through standard class.
- APAC markets have highest shipping cost, followed by EU and US.
   ![image](https://user-images.githubusercontent.com/103464406/218608777-892f74b8-ee20-4c22-8c2f-953638930e54.png)

---

## 🎯 Business Objectives
1. Identify the **highest-performing products and categories** to optimize stock and promotions.  
2. Analyze **sales and profit trends over time** to detect growth patterns or seasonal demand.  
3. Evaluate **regional and market performance** to focus expansion efforts.  
4. Understand **shipping preferences and costs** to improve operational efficiency.  
5. Generate actionable recommendations to **increase profitability**.

---

## 🛠 Tools & Technologies
- **Microsoft Power BI**: Dashboard creation and interactive visualization  
- **Excel / CSV**: Data cleaning and preparation  
- **Data visualization best practices**: KPI cards, trend analysis, and drill-down filters

---

## 📂 Dataset Details 
- Period: 2011 – 2014  
- Key Fields:  
  - `Order ID` – Unique identifier for each order  
  - `Product Name` / `Category` / `Sub-Category` – Product details  
  - `Sales` – Revenue generated  
  - `Profit` – Profit margin  
  - `Region` / `Market` – Geographic information  
  - `Ship Mode` / `Order Priority` – Operational details  

---

## 📊 Dashboard Overview
The dashboard is divided into **three main sections**:

### 1️⃣ Sales Analysis
- Tracks **overall revenue and profit trends** over the years.  
- Highlights **peak months and seasonal trends**.  
- Provides **year-over-year comparisons**.  

**Key Observations:**
- Total revenue over 4 years: ~$3 million, with total profit of ~$400K.  
- Peak sales occur during March–April each year, reflecting seasonal demand.  
- Holiday season (December) shows relatively lower revenue, suggesting a potential opportunity to improve promotions.

---

### 2️⃣ Product Analysis
- Evaluates **product categories and sub-categories** for revenue and profitability.  
- Tracks **quantity ordered, average discount, and profit margin**.  

**Key Observations:**
- Technology category contributes **~46% of total profit**, making it a key focus area.  
- Office Supplies have **high order volumes but lower margins**.  
- Furniture category sales are high but profitability is reduced due to **heavy discounting** (~28% average discount).  

---

### 3️ Shipping & Regional Analysis
- Monitors **shipping preferences and costs** across regions.  
- Evaluates **order priority and shipping mode trends**.  

**Key Observations:**
- Standard shipping accounts for **53% of orders**, while same-day delivery is rarely used.  
- APAC region has the **highest shipping costs**, followed by EU and US.  
- Critical-priority orders are mostly shipped via First Class, suggesting room to optimize logistics for cost efficiency.  

---

## 💡 Insights & Recommendations

1. **Focus on High-Profit Categories**  
   - Prioritize Technology products for marketing and inventory expansion.  
   - Consider limited discounting on profitable categories to maximize margins.  

2. **Optimize Pricing & Discounts**  
   - Furniture category discounts may be hurting profitability; consider price adjustments or bundling strategies.  

3. **Leverage Seasonal Trends**  
   - Peak months (March–April) should be targeted with **promotions and stock optimization**.  
   - Holiday season requires stronger marketing campaigns to improve revenue.  

4. **Improve Regional Operations**  
   - Investigate high shipping costs in APAC and EU to reduce operational expenses.  
   - Explore regional distribution centers or negotiated shipping contracts.  

5. **Enhance Shipping Strategy**  
   - Encourage adoption of faster shipping modes for premium revenue opportunities.  
   - Analyze customer segments to identify who values faster delivery most.  

---

## ⚠️ Limitations
- Data only covers 2011–2014, so trends may not reflect current conditions.  
- Customer demographics and marketing spend data are not included.  
- External factors such as competitor activity and economic conditions are not captured.  

---

## Conclusion
This analysis provides actionable insights into **product performance, revenue trends, and operational efficiency**. By focusing on high-margin categories, optimizing discount and shipping strategies, and leveraging seasonal trends, a business can **improve profitability and make data-driven strategic decisions**. The interactive dashboard allows managers to filter and drill-down on specific regions, products, and time periods for deeper insights.

---

## 📎 Project Files
- `/dashboard/retail_sales_dashboard.pbix` – Power BI interactive dashboard  
- `/data/superstore_sales.csv` – Dataset  
- `/images/dashboard_preview.png` – Dashboard screenshot  
- `README.md` – Documentation (this file)  

---
