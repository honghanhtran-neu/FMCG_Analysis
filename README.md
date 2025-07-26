# FMCG_Analysis
## 🧠 1. Business Context
- This project simulates the business operations of Nestlé Poland from 2022 to 2024, focusing on several popular food product lines.
- Nestlé Poland is one of the leading companies in the consumer packaged goods (CPG) industry in Poland, operating in a highly competitive market with rapidly shifting consumer behavior.
- In this dynamic environment, Nestlé faces challenges in understanding how factors such as pricing, promotions, delivery times, and regional demand affect business performance. A lack of clear insight into these dynamics can result in missed opportunities for growth and inefficiencies in operations.
- Thus, this data analysis project aims to help identify key business drivers that influence revenue growth and operational performance, enabling Nestlé to make more informed, data-driven decisions and align strategy with market trends.

## 🎯 2. Key Business Questions
To support relevant business units such as the Sales & Marketing Department, Demand Planning Team, and Regional Distribution Managers in making data-informed decisions, this project seeks to address the following key business questions:

**Sales & Channel Performance**
- Which sales channels are generating the highest revenue and growth?
- How do sales differ across product categories, pack types, and regions?
- Are there underperforming SKUs or regions that require intervention?

**Promotion Effectiveness**
- To what extent do promotions impact units sold across different products or channels?
- Which types of promotions are most effective in driving sales uplift?
- Are promotional products cannibalizing regular sales or encouraging upsell?

**Pricing Strategy**
- What is the relationship between unit price and quantity sold?
- Are certain product segments more sensitive to price changes?
- Does pricing vary significantly across regions or sales channels?

**Inventory & Delivery Optimization**
- Are there consistent delays in delivery across certain regions or product types?
- How does delivery time impact sales performance?
- Are there recurring patterns in stockouts or overstock situations?

**Demand Trends & Seasonality**
- Are there clear seasonal trends in product demand across months or quarters?
- How have customer purchase patterns shifted over time?
- Can we detect early signals of changing market demand?

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

