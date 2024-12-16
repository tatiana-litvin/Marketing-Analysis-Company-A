# Sales Analysis for The Look 2019 - 2024

# Project Background
The Look, an e-commerce company specializing in clothing sales, has a large operation and thousands of customers. They have collected significant amounts of data on their sales transactions from 01/2019 to 12/2024. This project analyses and synthesizes the data to provide insights that will improve The Look's commercial success

Insights and recommendations are provided on the following key areas:


- **Sales trends analysis:** Evaluation of historical sales patterns, focusing on order volume and revenue.
- **Product level performance:** Analysis of product performance, focusing on their patterns of sales, revenue generated and associated costs.
- **Customer loyalty and acquisition:** Assessment of repeat customers behaviors and new customers acquisition to uncover opportunities for retention and growth. 


Targeted SQL query and python script answering the business questions can be found here [link]().


# Data Structure & Initial Checks


The company's main database structure as seen below consists of four tables: order_items, orders, products and users, with a total row count of 181,082 records. 

Obs: dataset was fictional and made available open access with most data pre-cleaned and with non significant null values, therefore no cleaning code is supplied here. 

![orders](https://github.com/user-attachments/assets/ca8dd42e-fa7d-4fc1-a659-e9be7023ac8f)



# Executive Summary


### Overview of Findings

Since its creation in 2019, The Look has continued to increase sales and revenue, with significant improvements throughout 2024. Key performance indicators have seen a year-over-year increase, with order number up by 97.8%, and revenue up by the same amount. The following sections will expand on these findings with more detail, and highlight areas for improvement


# Insights Deep Dive
### Sales Trends:

* **The company's sales peaked in November of 2024, with a total of 1905 orders, and a total of € 156.948,9 in revenue.** It is possible to see steady growth in revenue over the company's 6 years in business.
  
* **The increase in number of order has been mostly steady since the company's inception** The graph shows how each year there has been an increase in the number of orders, which can be due to the brand becoming more popular and attracting new customers.
  
* **Average order value saw a slight trend of decrease after its first year in the market.** However, from 2021 onwards there was an increase in order value, which from 2021 to 2024 has increased by 2.8%.

  
  ![revenue_2019-2024](https://github.com/user-attachments/assets/4a7cb593-d9c0-4db0-80cf-dc6166904c3a)


![completed_orders_2019-2024](https://github.com/user-attachments/assets/1f7eec38-ebe4-4525-81c0-0f0a915684b8)


### Product Performance:

* **The Look offers a total of 21,857 different products on their website, and the most ordered categories through the years were Intimates, Jeans, and Tops and Tees, representing a combined 20.9% of all orders .** In 2024, the most ordered categories were again those same three, and their combined revenue represented around 20% of the yearly revenue.
  
* **In 2024, the largest part of the revenue came from Outerwear and Coats.** This can be explained by the higher price of items in this category averaging € 143.4 per item.
  
* **The Clothing Sets category brought in the least revenue in 2024, at 0.0008% of the total yearly revenue.** This category was the least ordered during the year, and it is also one of the costliest, with a profit margin of 39.4%, while the average profit margin of their other product categories averages at 51%. 

  
![Screen Shot 2024-12-16 at 19 35 47](https://github.com/user-attachments/assets/909859ab-7890-4e55-a9e8-e8d9534c9bd4)


### Customer loyalty and acquisition analysis:

* **Customer acquisition has been steadily growing since the company's creation.** In 2019, the first year The Look was in business, 446 customers made purchases at their website. In 2024, 13.511 unique customers ordered items, and of those, 12.416 were new customers. These trends show that The Look is very successful at attracting new customers.
  
* **There was a peak in new customer orders in November of 2024.** This may have been due to a new marketing campaign that both attracted new customers and resulted in the increased revenue shown previously for this month.
  
* **Customer loyalty is low, the percentage of customers that return to make a second order is 12.29%.** While the company is doing well at attracting new customers, only a small percentage of those become recurrent and proceed to make more orders on the website. 


![newCustomersPerMothPlot](https://github.com/user-attachments/assets/0f3da58e-2c9e-418d-9209-2f926bc1f0af)



# Recommendations:

Based on the insights and findings above, the following recommendations were provided:

* The stable increase in order numbers over the years in business show that the marketing and outreach efforts are having positive results. **Continue with those strategies as their positive influences can be seen in the results on these analyses.**
  
* The Look's product portfolio is very widespread, with a total of 21,857 products for sale at the moment, at different levels of performance success. **Limiting the catalog offer by removing the categories that have the lowest profit margins, such as the Clothing Sets, can lower operation costs.**
  
* The Look is successful at attracting new customers, but the low rate of recurring customers shows that there can be improvements at fostering customer loyalty. **Developing and implementing A/B tested retention marketing campaigns can help lead current customers to return. Also consider supplying coupons after a first purchase is completed.**
  
* Invest in understanding the motives why customers do not make consecutive purchases often, consider sending out surveys via email requesting people to rate their order. **Consider offering a sign up discount for users that rate previously ordered items, and pair that with targeted ads recommending previously purchased items that may need replacing.**
  


# Assumptions and Caveats:

Throughout the analysis, some assumptions were made to manage challenges with the data. These assumptions and caveats are noted below:

* Only orders with ‘complete’ status were included in the main analyses as those would contribute to revenue and profit, therefore rows with ‘processing’ status that may have contributed to the sales trend later on were not included as they were not considered complete at the time of analysis.

* The filtering conducted at the start of the analysis was made to ensure only complete, and not returned orders were included. If needed afterwards by any team member, more can be investigated about returns and how that affects the business.
  
* Since the data was fictitious, the trends and results look too good to be true, and that's because they're indeed not based on a real company's operations, but explanations were provided to the best of my abilities, based on past experience and reflection.

