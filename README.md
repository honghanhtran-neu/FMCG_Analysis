# FMCG_Analysis
## 🧠 1. Business Context
- This project simulates the business operations of Nestlé Poland from 2022 to 2024, focusing on several popular food product lines.
- Nestlé Poland is one of the leading companies in the consumer packaged goods (CPG) industry in Poland, operating in a highly competitive market with rapidly shifting consumer behavior.
- In this dynamic environment, Nestlé faces challenges in understanding how factors such as pricing, promotions, delivery times, and regional demand affect business performance. A lack of clear insight into these dynamics can result in missed opportunities for growth and inefficiencies in operations.
- Thus, this data analysis project aims to help identify key business drivers that influence revenue growth and operational performance, enabling Nestlé to make more informed, data-driven decisions and align strategy with market trends.

## 🎯 2. Key Analytical Questions
### 2.1 Descriptive Analysis – What happened?
- What are the historical sales trends over time by region, product category, and sales channel?
- Which customers, products, and regions contributed the most to total revenue?
- How did key operational metrics such as discount levels, delivery times, and product return rates vary over the three-year period?
### 2.2 Diagnostic Analysis – Why did it happen?
- What internal or external factors may explain variations in sales across time and geographic areas?
- Is there a significant correlation between discount percentages and sales volume?
- To what extent did delivery performance or return rates impact customer demand and satisfaction?
### 2.3 Predictive Analysis – What is likely to happen?
- Can we accurately forecast future sales based on historical data and influencing factors?
- Which products or customer segments are likely to generate high revenue in upcoming periods?
- Are there any recurring seasonal patterns or demand surges that the company should anticipate?
### 2.4 Prescriptive Analysis – What should we do?
- How can Nestlé optimize discount strategies to boost sales without compromising profit margins?
- Which customer segments or product lines should be prioritized to drive sustainable growth?
- What logistical or operational improvements could enhance customer satisfaction and overall sales performance?

## 🔍 3. Dataset Description
- Source: Kaggle
- Format: CSV
- Context: Simulated transactional sales data for Nestlé Poland
- Time Period: From 2022 to 2024
- Size: 190757 × 14
- Detailed variables:
  - date: Date of transaction
  - sku: Stock Keeping Unit – unique identifier for each product
  - brand: Brand name associated with the product
  - segment: Market segment the product belongs to
  - category: Product category (Milk, Yogurt, ReadyMeal, Juice, SnackBar)
  - channel: Type of sales channel (Retail, E-commerce, Discount)
  - region: Geographic location of the transaction (Central, North, South)
  - pack_type: Packaging type
  - price_unit: Unit price of the product (before promotions)
  - promotion_flag: Indicates if a promotion was applied
  - delivery_days: Number of days between order and delivery
  - stock_available: Units of product available in stock at the time
  - delivered_qty: Quantity of product actually delivered
  - units_sold: Quantity of product sold (after considering promotions and delivery)

