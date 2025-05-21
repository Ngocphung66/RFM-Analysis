# RFM-Analysis: Customer segmentation
"RFM Analysis" is a part of Marketing Analysis and is used to analyze customer value, thereby helping businesses to analyze each customer group they have, from there marketing campaigns or special care.

Please see the coding file attached or reach this link https://colab.research.google.com/drive/1mnKTwyA4SzgKTpzqynevhoYKjsWnllsj

## I. Introduction
### 1. Business question
* SuperStore is a global retail company. The Marketing Department wants to run marketing campaigns during the Christmas and New Year holidays to thank customers for their past support of the company. In addition, potential customers can be upgraded to become loyal customers.
* The Marketing Director also proposed a plan to use the RFM model in Python to segment customers and then launch appropriate marketing campaigns. Analyze the current situation of the company and give suggestions to the Marketing team
* With the retail model of Superstore company, which indicator should be most focused on in the 3 indicators R, F, and M?

### 2. Dataset
Dataset includes 4 different related tables including: transaction information, products information, returned orders of customers purchasing products from 2014 to 2017 and RFM classification
* Transaction information dataframe

![image](https://github.com/user-attachments/assets/20d3d943-79f1-4956-8971-295b1a7d63a3)

![image](https://github.com/user-attachments/assets/5e70f56f-1012-472b-a429-d54324011fdf)


* Segmentation dataframe

![image](https://github.com/user-attachments/assets/a63cc877-3a9d-430e-b53b-0c1ca0b2a3c9)

### 3. RFM model
* RFM is a method used for analyzing customer value. It is commonly used in database marketing and direct marketing and has received particular attention in retail and professional services industries
  
* RFM stands for the three dimensions:
Recency – How recently did the customer purchase?
Frequency – How often do they purchase?
Monetary Value – How much do they spend?

* RFM analysis numerically ranks a customer in each of these three categories, generally on a scale of 1 to 5 (the higher the number, the better the result). The “best” customer would receive a top score in every category.

## II. Data Visualization with Python

![image](https://github.com/user-attachments/assets/eb2ffc66-609e-450b-9a18-baf16131233a)

![image](https://github.com/user-attachments/assets/fc632556-f21c-474b-977d-9cc7a3ca93bb)

![image](https://github.com/user-attachments/assets/285bae40-706f-4afe-a052-c6fc675075f8)

![image](https://github.com/user-attachments/assets/d1463710-fe77-49d8-9e16-426f08bbbd9e)

![image](https://github.com/user-attachments/assets/5b161edf-703b-475e-b181-7a6dc03303f7)

![image](https://github.com/user-attachments/assets/02480b93-e905-48a9-98ac-befcef8c9dbc)


## III. Insights
### 1. Recency, Frequency and Monetory value of Superstore
* As a retailer, Superstore may prioritize Recency and Frequency over Monetary value because customer engagement and retention are often more critical to long-term success than just individual spending.
* Customers last purchased an average of 91.5 days ago, but half made purchases within 50 days. This suggests a mix of highly engaged and inactive customers.
* The average number of transactions per customer is 89.4, but a high standard deviation of 222.3 indicates significant variability—some buy frequently, while others purchase sporadically.
--> Those are some warnings for Superstore to focus more on Recency and Frequency performance.

### 2. Segments of Superstore
* 3 segments with the highest proportion of customers are Champions (18.51%), Hibernating customers (18.42%) and Potential Loyalist (11.8%)
* Negative segments such as Hibernating and Lost accounted for a high proportion of customers, 18.42% and 10.07%, respectively. However, these two groups account for less than 5% of revenue
* The two most positive segments account for less than 19% of the proportion of customers (Champions, 8.98%, and Loyal, 9.52%).
* Potential Loyalist (the ideal segment) has the highest proportion of customers (11.8%), but its revenue proportion is only 3.34%. Meanwhile, the negative segment, At Risk, accounts for 7.1% of revenue ⇒ In this Christmas - New Year marketing campaign, SuperStore needs to prioritize their efforts to promote the Potential Loyalist group to become Loyal and Champions, and find ways to reconnect with customers in the At Risk and Hibernating group.

### 3. Recommendation
3.1. Potential Loyalists → Loyal & Champions
Goal -- Encourage repeat purchases and increase brand attachment.

* Exclusive Holiday Offers: Send personalized discounts on past purchases or trending seasonal items.
* VIP Early Access: Allow early shopping for holiday collections or limited-time products.
* Gift Bundles & Rewards: Offer bundled products or extra loyalty points for purchases above a certain amount.

3.2. At Risk Customers → Re-engagement
Goal -- Win back disengaged customers and reignite their shopping habits.

* Personalized Win-Back Emails: Send customized messages highlighting special discounts based on past purchases.
* Limited-Time Deals: Use urgency (e.g., “Last chance for holiday rewards!”) to encourage immediate action.
* Festive Event Invitations: Host exclusive online or in-store holiday events with gift incentives for participation.

3.3. Hibernating Customers → Revive Interaction
Goal -- Reintroduce them to the brand and encourage engagement.

* Special Re-Engagement Campaigns: “We Miss You” emails with a unique discount to welcome them back.
* Gamified Offers: Implement interactive promotions like scratch-and-win deals or bonus points for completing small actions.
* Gift Incentives on Purchase: Surprise giveaways or exclusive gifts for their first purchase after re-engagement.
* Surveys & Feedback Requests: Understand reasons for disengagement and adjust strategy accordingly.









