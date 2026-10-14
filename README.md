# Discount_Targeting
Customer Segmentation To Improve Discount Rating (E-Commerce Analytics)

## 📊 Interactive Dashboard
<img width="777" height="712" alt="image" src="https://github.com/user-attachments/assets/93557e0e-81b1-4fd0-8342-cda0e5e5913d" />


## 📁 Repository
- [Dataset](./Dataset.csv)
- [Customer Segmentation Dataset](./customer_segmentation.csv)
- [Analysis Notebook](./Ghairandi_Al_Abrar_Discount_Targeting.ipynb)

## 🎯 Business Problems & Project Goals
Discounting is a common strategy to drive sales, but its actual impact on final profit is often unclear. The effectiveness of discounts may vary across customer segments and product categories, creating a need to understand whether higher discounts actually translate into proportional profit gains.

Using over 51,000 transactions from a multi-category e-commerce platform, this project applies RFM analysis and K-Means clustering to segment customers based on their value and evaluate the effectiveness of the current discount strategy.

### Project Goals
1. **Evaluate** the relationship between discounts and final profit.
2. **Identify** patterns across customer gender and product categories.
3. **Segment** customers based on shopping behavior to support a more effective discounting strategy.

## 🧩 Features & Visualization
### Key Features
- **Total Customers** => Total unique customers that has made at least one purchase from the shop
- **Total Profit** => The sum of profit made
- **Average Discount** => The average discount received by customers from all segments with unique purchase behaviors
- **Average Recency** => The average number of days since each customer's most recent purchase
- **Average Frequency** => The average number of purchases made by each customer
- **Average Monetary** => The average total spending made by each customer

### Visualization
-  **Total customers per-segment** => Stacked column chart
-  **Average of Discount Received per Customer Segments** => Stacked bar chart
-  **Sum of Total Profit per Customer Segments** => Pie chart
-  **Comparasion Between the Percentage of Total Customers and the Profit Made per Segment** => Clustered column chart
-  **Customer Segments and Product Category Filter** => Slicer

## 📌 Key Insights
- **Discount allocation is nearly uniform across all segments (~30–31%)**, despite stark differences in purchasing behavior and profit contribution, the current strategy does not differentiate based on customer value and their purchasing behavior.
  
- **Segment profiles vary sharply**: High-value Repeat (8.9% of customers, 19.6% of profit, Rp 204 profit/customer) is the smallest but most valuable group; Repeat Mid-value (16.7% of customers, 23.3% of profit) shows repeat purchases at moderate spend; Recent One-timer (40.4% of customers, 30.9% of profit) is the largest segment and the strongest conversion candidate; Lost One-timer (34.1% of customers, 26.2% of profit, 252-day average recency) shows the lowest return probability.
  
- **Discount efficiency varies significantly by segment**: Using **Profit Margin** as the primary metric and **Discount Efficiency** as a secondary descriptive measure. Repeat Mid-value leads on both (22.8% margin, 0.75 efficiency), while High-value Repeat ranks lowest (14.5% margin, 0.47 efficiency) despite the highest profit per customer. Lost and Recent One-timers sit in the middle (~18.6–18.7% margin, 0.60 efficiency). These gaps mainly reflect differences in basket size and customer value, not different discount rates. 
  
- **Suggestion, discount budgets should be reallocated**: Shift discount intensity away from High-value Repeat customers (replace with non-price benefits) and Lost One-timers (limit discounts), maintain moderate discounts for Repeat Mid-value customers, and use limited time-bound discounts to convert Recent One-timers. Further validation through experimentation is still required before full implementation.

## 🗂️ Data Source 
The raw (uncleaned) dataset that is used in this project can be downloaded through the link below
https://www.kaggle.com/datasets/mervemenekse/ecommerce-dataset
