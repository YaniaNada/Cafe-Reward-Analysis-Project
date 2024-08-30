### Analysis GOAL:
1. Identify key Cafe Rewards customer segments and develop a data-driven strategy for future promotional messaging & targeting.
2. Create a dashboard to monitor the performance & result

This repository is for data wrangling purpose. The original datasets are in the "Data" folder and the post-transformation datasets are in the "outputs" folder. 

Transformation involved:
- Cleaning the data
- Extracting data from columns to create new columns
- Joining tables to enrich and create new datasets

For dashboard creation I used Tableau (Link is at the end).

#### DATA DESCRIPTION:

Data Structure: Multiple tables. 
No. Of Records: 306,534. 
No. Of Fields: 14. 
More about data can be found in: https://mavenanalytics.io/challenges/maven-rewards-challenge/404c6060-60eb-400f-9bce-c3b9f97e9d5a

The data simulates the behavior of Cafe Rewards members over a 30-day period.

Customers receive offers once every few days and have a limited time to redeem them. 

They receive three types of offers:
1. informational offers (simple advertisement of a product), 
2. discount offers, or 
3. BOGO (buy one, get one) offers. 

Each customer receives a different mix of offers, attempting to maximize their probability of making a purchase. Every customer purchase during the period is marked as a transaction. 

NOTE: A transaction is attributed to an offer ONLY if it occured at the same time as when the offer was "completed" by the customer.

### ANALYSIS OUTCOME

#### Customer segments:
The ideal segment to target is customers older than 35 years with income above $50k, irrespective of gender.

#### Channels:
The most effective channel combination: [web, email, mobile, social]. 53% of the successful offer used this combination.

NOTE: An offer is considered successful if a transaction has been made related to it.

25% used a combination of [web, email, mobile].
11% [email, mobile, social] and 10% [web, email].

#### Offer Types:
Among the three types of offers (discount, BOGO, and informational), as expected, only discount and BOGO (buy one, get one) type offers led to successful offers.

Comparing the conversion rates, 'discount' type on average had +3% higher success rate than BOGO type. 

The average success rate for discount offers is 25%.

Only 1 BOGO offer achieved 25% success rate.

#### Rewards, offer duration, & difficulty levels:
Among these three factors, the difficulty of completing an offer has the stongest influence on offer completion rate. About 90% of the completed offer is within a difficulty level of less than or equal to '10'.

However, higher rewards does incentivize customer to complete offers with higher difficulty levels. Offer duration doesn't have any significant impact on the probability of an offer success.

#### RECOMMENDATION:
Based on the analysis, it is recommended to use discount type offers for promotional offers. The campaign should be targeted to individual above age of 35 with an income higher than $50k. The recommended channel to us is a combination of [web, email, mobile, social].

Link to Dashboard: https://public.tableau.com/views/Cafe_rewards_challenge/Dashboard13?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link