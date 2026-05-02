# Forage - Job Simulation
Data Science Job Simulation @ Commonwealth Bank
---

This project by Forage in partnership with the Commonwealth Bank aims to develop activities designed to provide a better understanding of the various tasks involved in the daily work of a data scientist in the financial sector. Creating a data engineering pipeline to aggregate and extract insights from a data set and practicing using Microsoft Excel to build my data analysis skills in a real-world context.

##Task 1
Performing analysis on the provided CSV data set (a sample of the database) to answer the following questions:
* Across locations, how many apples were purchased in cash?
* How much total cash was spent on these apples?
* Across all payment methods, how much money was spent at the Bakershire store location by non-member customers?
  
To obtain the amount of apples purchased in cash, first the data must be filtered:					
In the product_name column filter by "apple"					
In the payment_method column filter by "cash"					
The output can be seen in the "apples_cash"  tab					
To obtain the result amount, a simple aggregate function "=SUM()" alongside the "quantity" column					
With that, we can infere that the amount of apples purchased in cash is 117, from 2019 to 2021, across all locations.					
					
The same steps can be applied to obtain how much cash was spent on said apples.					
The "=SUM()" function must be applied in the "total_amount" column					
Resulting in a total amount of 537,03$, considering the same variables.					
					
To obtain how much money was spent at the Bakershire store by non-member customers, these filters must be applied:					
Considering the raw dataset					
Filter the "store" column by "Bakershire"					
Filter the "customer_type" column by "non-member"					
The output can be seen in the "bakershire_sales" tab					
To obtain the total amount spent, the same SUM() function can be applied alongside the "total_amount" column					
Resulting in the amount of 2857,51$ spent by non-members at the Bakershire store.					
					
In the "supermarket_transactions" the original dataset can be consulted.					
<img width="685" height="501" alt="image" src="https://github.com/user-attachments/assets/5c2b3b9f-a959-470a-88fb-bed6bca35e83" />

##Task 2
Anonymise this data to hide personal details while preserving any useful information for the data scientists:

For that, I:
Removed unecessary columns (adress, credit card number and informations);
Kept only the customer_id, removing theirs name and username;
Grouped and categorized the ages and anonymised the names;

The new dataset can be consulted in "mobile_customers_treated"
<img width="1654" height="299" alt="image" src="https://github.com/user-attachments/assets/8b94a8bd-0079-4304-88fe-86c44a266e85" />

##Task 3
Writing a proposal that suggests ways to use the available data on the @CommBank Twitter account to extract valuable insights. 

I decided to perform a sentiment analysis algorithm with the tweets replies from the Twitter API using TextBlob.
This project it's the first time I perform a sentiment analysis, representing a great starting point and opportunity for me.

Tweets extracted via the API:
<img width="1037" height="360" alt="image" src="https://github.com/user-attachments/assets/a130e6fd-3b4b-40e4-a6ed-4853b722804c" />

<img width="744" height="513" alt="image" src="https://github.com/user-attachments/assets/128a3296-0aa4-4365-aea9-0981e515247d" />

