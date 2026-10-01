# Discount_Targeting
Customer Segmentation To Improve Discount Rating (E-Commerce Analytics)

## 📊 Interactive Dashboard
<img width="1213" height="660" alt="image" src="https://github.com/user-attachments/assets/e75d18ce-fc0d-4a59-8cdb-97bebda6f8e9" />


## 📁 Repository
- [Dataset](./Dataset.csv)
- [Customer Segmentation Dataset](./customer_segmentation.csv)
- [Analysis Notebook](./Ghairandi_Al_Abrar_Finpro.ipynb)

## 🎯 Business Problems & Project Goals
<p align="justify">
Discounting is a common strategy to drive sales, but its actual impact on final profit is often unclear. The effectiveness of discounts may vary across customer segments and product categories, creating a need to understand whether higher discounts actually translate into proportional profit gains.
<p align="justify">
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
1.) Discount allocation is nearly uniform across all segments (~30–31%), despite stark differences in purchasing behavior and profit contribution, the current strategy does not differentiate based on customer value and their purchasing behavior.
2.) **Segment profiles vary sharply**: High-value Repeat (8.9% of customers, 19.6% of profit, Rp 204 profit/customer) is the smallest but most valuable group; Repeat Mid-value (16.7% of customers, 23.3% of profit) shows repeat purchases at moderate spend; Recent One-timer (40.4% of customers, 30.9% of profit) is the largest segment and the strongest conversion candidate; Lost One-timer (34.1% of customers, 26.2% of profit, 252-day average recency) shows the lowest return probability.
3.) **Discount efficiency varies significantly by segment**: Repeat Mid-value delivers the best ROI (Rp 0.75 profit per Rp 1 of discount spent), while High-value Repeat delivers the worst (Rp 0.47), the segment that needs discounts least is currently receiving them least efficiently. 
4.) **Suggestion, discount budgets should be reallocated**: reduce discounts for High-value Repeat in favor of non-price loyalty benefits (free shipping, priority service), keep moderate discounts paired with bundling for Repeat Mid-value, offer time-limited second-purchase incentives for Recent One-timer, and minimize broad discounting for Lost One-timer in favor of selective win-back offers.

## 🗂️ Data Source 
The raw (uncleaned) dataset that is used in this project can be downloaded through the link below
https://www.kaggle.com/datasets/mervemenekse/ecommerce-dataset
