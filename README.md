# Discount_Targeting
Customer Segmentation To Improve Discount Rating (E-Commerce Analytics)

## 📊 Interactive Dashboard
<img width="1276" height="692" alt="image" src="https://github.com/user-attachments/assets/4d9a8df8-62ac-47cb-ac9f-00f741c58331" />



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
  
- **Customer segments differ significantly in value and behavior**: High-value Repeat represents only 8.9% of customers but contributes 19.6% of total profit, making it the most valuable segment in terms of profit per customer. Repeat Mid-value contributes 23.3% of profit from 16.7% of customers, indicating strong repeat-purchase behavior. Recent One-timer is the largest segment (40.4% of customers) and a key conversion opportunity, while Lost One-timer accounts for 34.1% of customers but only 26.2% of profit, with an average recency of 252 days.
  
- **Discount efficiency varies considerably across segments**: Using Profit Margin as the primary performance metric and Discount Efficiency as a secondary measure, Repeat Mid-value ranks highest (22.8% margin, 0.75 efficiency), while High-value Repeat ranks lowest (14.5% margin, 0.47 efficiency) despite its highest profit per customer. Lost and Recent One-timers fall in the middle, with margins of 18.6–18.7% and efficiency of 0.60. These differences suggest that discount effectiveness depends more on customer value and purchasing patterns than on discount intensity alone.
  
- **Recommendation: Adopt segment-specific discount strategies**: Prioritize non-price benefits, such as loyalty rewards and exclusive perks, for High-value Repeat customers to protect profitability. Maintain targeted incentives for Repeat Mid-value customers, use time-limited offers to encourage Recent One-timers to make a second purchase, and limit broad discounting for Lost One-timers in favor of selective reactivation campaigns. Validate these strategies through controlled experiments before full implementation.

## 🗂️ Data Source 
The raw (uncleaned) dataset that is used in this project can be downloaded through the link below
https://www.kaggle.com/datasets/mervemenekse/ecommerce-dataset
