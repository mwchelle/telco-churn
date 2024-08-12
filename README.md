# telco-churn
Data Analytics and Prediction Model for Telco Customer Churn Data

## Link to Interactive Tableau Dashboard: https://public.tableau.com/views/customer_churn_telco/Dashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

## Objective:
The goal of this project is to help understand the factors that contribute to customer churn for Telco and to create a customer churn model that predicts whether a customer will churn. Propose recommendations, based on insights, to increase customer retention and reduce churn rate. 

## Dataset Description:

The dataset reflects customer data from a telecom company. This dataset is available via Kaggle.

Key Data Fields:
* CustomerID: Unique identifier for the customer
* Gender: Customer gender (Male, Female)
* Senior Citizen: Whether a customer is a senior (0 for no, 1 for yes)
* Partner: Whether the customer has a partner
* Dependents: Whether the customer has dependents
* Tenure: Number of months the customer has stayed with the company
* MonthlyCharges: The amount charged to the customer monthly
* TotalCharges: The total amount charged to the customer
* Churn: Customer churn status (Yes or No)

## Summary of Insights
* Telco has difficulty retaining both senior customers and new customers (less than 1 year), with a senior churn rate of 41.68% and a churn rate of 47.68% for new customers.
* Long contracts are more effective for customer retention as nearly all customer churn (88.5% of total customer churn) comes from customers on a month-to-month contract. Increasing contract length decrease churn by over 30% from month-to-month contracts, with two-year contracts having a churn rate of only 2.83%.
* Customers who churn pay on average $15 more at each number of services and have an average tenure time difference of 20 months. This indicates that cost may be a significant factor in the churn rate, as customers who do not churn pay, on median, less than their counterparts.
* Tenureship length increases as the number of services purchased increases, with all customers who purchase 3+ services having a median tenureship of 12 months or more.

## Recommendations and Next Steps
* Promote longer term contracts by offering promotions such as discounted average monthly charge and flexibility in increasing or decreasing services to increase the overall amount of customers on 1-year or 2-year contracts and incentivize them to maintain and renew contracts to full duration.
* Develop senior retention customer programs, targeting the specific customer segment to improve senior churn rate; this can include additional product support for seniors and exclusive offers.
* Reevaluate current pricing schemes, especially for new customers, to mitigate current pricing differences leading to higher churn rate. Offer service bundling and discounts to encourage customers to purchase additional services, reducing their likelihood to churn.
* Continue to evaluate whether certain discount programs are effective in reducing churn, specifically targeting new customers, senior customers, and focusing on conversion from month-to-month to longer term contracts.

## Relevant KPIs
* Reduce churn rate to 30% for new customers and 35% for senior customers within the next fiscal year.
* Achieve a customer retention rate of 80% of all customers within the next year.
* Increase proportion of customers on 1-year or longer contracts to 50%.
* Achieve an average tenure of 1.5 years (18 months) for all customers.
