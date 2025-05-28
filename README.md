## Amazon India Sales Performance Analysis (March 2022 - June 2022)

### Project Background

Amazon, one of the world's largest e-commerce companies, offers a wide range of products and services to millions of customers globally. I'm partnering with the Head of Operations to extract insights and deliver recommendations that can help improve performance across sales and marketing teams. With this, I'm focusing on Amazon's sales data and customer order behavior in India from March to June 2022.
***
### Data Description

Our analysis is based on a dataset encompassing several key aspects of Amazon's order and sales operations:

1. **Order Details**: This includes *Order ID*, *Order Date*, and *Order Item Quantity*. These fields help track the number of orders and items purchased per day and monitor trends in daily transaction volume.

2. **Sales Metrics**: The dataset includes financial information such as *Item Price* and *Revenue*. These metrics allow us to evaluate total and daily sales performance.

3. **Promotions**: The *promotion-ids* column indicates whether an order was made with a promotion. This enables us to assess the effectiveness of promotional campaigns in driving sales and customer engagement.

4. **Time Dimension**: Derived fields such as *purchase_month* and *purchase_day* were created to enable temporal analysis and comparisons across different months and days.

5. **Product Information**: Each record contains *Product ID* and *Product Category*, which could help identify trends in product popularity and category-based sales performance.

This structured data allows for comprehensive performance tracking and behavioral analysis, forming the foundation of our insights and recommendations.
***
### Executive Summary

Amazon India's sales analysis from March to June 2022 reveals a total revenue of ₹78.59 million in 128,975 orders, with an average order value (AOV) of ₹609.36. Sales peaked in April at ₹28.84 million before gradually declining through June. While May recorded the highest AOV at ₹623.85, promotional campaigns played a key role in order volume, driving nearly 62% of total orders and contributing ₹53.59 million in revenue, which is over 68% of total sales. However, promotion efficiency slightly declined month-over-month, indicating potential saturation or diminishing returns. These insights suggest that while promotions significantly boost performance, refining targeting strategies and optimizing non-promotional channels can enhance revenue sustainability and customer engagement moving forward.
***
### Insights Deep-Dive

#### Sales Performance
- Amazon India's total revenue from March to June 2022 reached ₹78.59 million, with 128,975 total orders placed during this period.
- April recorded the highest revenue at ₹28.84 million and the largest order volume of 49,067, establishing it as the peak sales month.
- Revenue declined steadily month-over-month after April, falling to ₹26.23 million in May and ₹23.43 million in June suggesting a possible post-promotion normalization or seasonality effect.
- Despite the revenue drop, AOV actually increased after April, peaking in May at ₹623.85, hinting that customers were purchasing higher-value items or more units per order.
- March showed minimal activity, with only one day of data, resulting in just ₹101.68K in revenue and 171 orders, making it statistically insignificant for broader trend analysis.

![Sales Summary (2)](https://github.com/user-attachments/assets/897d2c78-a63a-4a97-9c47-27b9c0cf0c0b)
![Sales Summary (1)](https://github.com/user-attachments/assets/16bb1682-b802-4cfd-af45-46a957e57fe8)

#### Customer Order Behavior
- Out of 128,975 total orders from March to June 2022, 79,822 (62%) were placed with promotions, showing strong customer response to promotional offers.
- April recorded the highest number of promotional orders (30,842), aligning with its peak in revenue and total orders.
- Orders with no promotion made up 38% of total orders (49,153), with relatively steady counts from April to June.
- Promotion efficiency, which measures the share of orders placed with a promotion, averaged 61.89% across all months, peaking in April at 62.86% (excluding March since it only has one day data).
- In terms of revenue, promotion-based orders drove ₹53.59 million, accounting for nearly 68.2% of total sales, indicating that promotions not only boosted order volume but also revenue contribution.
- Revenue from non-promotional orders remained stable, totaling ₹25 million, with similar levels across April to June.
- The consistency in both promotion effciency and revenue efficiency suggests that promotional campaigns were effective in attracting more customers and generating higher value orders.

![Customer Order Behavior (2)](https://github.com/user-attachments/assets/60c65fc8-1e32-4f5f-9da3-1f2a3b729aec)
![Customer Order Behavior (1)](https://github.com/user-attachments/assets/deb2bcb9-cc94-4aae-bc21-6f65c44e22ca)
***
### Recommendations

#### Driving Revenue Growth and Sales Optimization 
- **Sustain Revenue Momentum Post-April Peak**: Since April recorded the highest revenue and order volume, replicate its sales strategies in future campaigns. Analyze seasonal trends, pricing, and promotional patterns that led to April's success.
- **Improve Revenue Distribution**: Address the decline in monthly revenue from April to June by spreading promotional efforts more evenly and launching mid-month campaigns to boost consistency.

#### Enhancing Promotion Strategies
- **Refine Promotional Campaigns**: With over 60% of orders and nearly 70% of revenue driven by promotions, continue to offer value-driven promotions while testing thresholds that still maintain profit margins.
- **Target Low-Promotion Periods**: Increase promotional visibility in months like June where efficiency dipped slightly, potentially through limited-time offers or exclusive member deals to retain momentum.

#### Boosting Customer Engagement and Retention 
- **Engage Non-Promotional Buyers**: Although smaller in number, non-promotional buyers contributed ₹25 million in revenue. Launch loyalty incentives for this segment to encourage repeat, full-price purchases and increase customer lifetime value.
- **Segment and Personalize Offers**: Use customer order behavior to segment buyers based on responsiveness to promotions and tailor future campaigns. Target deal-seekers with bundle discounts and reward regular buyers with exclusive perks. 





