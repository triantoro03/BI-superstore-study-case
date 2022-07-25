# BI-superstore-study-case
This is my homework study cases for my business intelligence short course from rakamin academy. The result of this homework is to display the tables according to the user's request. To fulfill the request from this user, I use pgAdmin (postgresql) to import the superstore's csv file and create my own version query.

## homework description
As one of the Business Intelligence Analysts in the Superstore, you are asked to support analysis needs, both from the internal BI team itself and from other teams such as Marketing, Business Development, Sales, etc.

Here are some analysis requests from other teams that are most urgent to complete. As a member of the BI Analyst who works most efficiently, you are asked to help with the following problems!


## Case 1
Ship Mode SAME DAY service is a service where products ordered by customers can be directly delivered on the same day as the order day. But in reality, not all customers who order Ship Mode SAME DAY receive the benefits of this service well. In other words, there are also some SAME DAY orders that are not delivered on the same day as the order day. The Operations Team would like to further analyze this matter so that it can be followed up. You are asked to display the number of SAME DAY orders/orders that are delayed in delivery.

## Case 2
The Business team would like to conduct further analysis of the company's profitability. This time, the Business Team wanted to see the relationship between the amount of discount given and the profitability received by the company. You are asked to display this relationship by showing the average profit for each discount level, where the discount level criteria requested by the Business Team are as follows:
- LOW if the discount is below 0.2 (excluding 0.2),
- MODERATE if the discount starts from 0.2 to below 0.4 (excluding 0.4)
- HIGH if the discount starts from 0.4 and above.

## Case 3
The Sales team asked the Business Intelligence Analyst for help to analyze the performance of the Category and Subcategory of the products owned by the company. You are prompted to return the following metrics for each of the existing Category-Subcategory pairs:
- Average discount
- Average profit

## Case 4
The Business Development team is considering a more in-depth expansion in State California, Texas as well as Georgia. As material for their consideration, you are asked to display the performance of each Customer Segment in the three States for 2016 only. The requested performance metrics are as follows:
- Total sales
- Average profit

## Case 5
The Business team is interested in seeing which region has the highest number of discount-loving customers. Therefore, the Business Team asks you as a Business Intelligence Analyst to display the number of people/customers who have an average discount above 0.4 for each existing region.

