# Customer-Personality-Analysis
**Unveiling Customer Insights: Unsupervised Learning for Dynamic Segmentation**

## Context.
### Problem Statement
Customer Personality Analysis is a detailed analysis of a company’s ideal customers. It helps a business to better understand its customers and makes it easier for them to modify products according to the specific needs, behaviors and concerns of different types of customers.

Customer personality analysis helps a business to modify its product based on its target customers from different types of customer segments. For example, instead of spending money to market a new product to every customer in the company’s database, a company can analyze which customer segment is most likely to buy the product and then market the product only on that particular segment.

## Content
### Attributes

#### People
- ID: Customer's unique identifier
- Year_Birth: Customer's birth year
- Education: Customer's education level
- Marital_Status: Customer's marital status
- Income: Customer's yearly household income
- Kidhome: Number of children in customer's household
- Teenhome: Number of teenagers in customer's household
- Dt_Customer: Date of customer's enrollment with the company
- Recency: Number of days since customer's last purchase
- Complain: 1 if the customer complained in the last 2 years, 0 otherwise

#### Products
- MntWines: Amount spent on wine in last 2 years
- MntFruits: Amount spent on fruits in last 2 years
- MntMeatProducts: Amount spent on meat in last 2 years
- MntFishProducts: Amount spent on fish in last 2 years
- MntSweetProducts: Amount spent on sweets in last 2 years
- MntGoldProds: Amount spent on gold in last 2 years

#### Promotion
- NumDealsPurchases: Number of purchases made with a discount
- AcceptedCmp1: 1 if customer accepted the offer in the 1st campaign, 0 otherwise
- AcceptedCmp2: 1 if customer accepted the offer in the 2nd campaign, 0 otherwise
- AcceptedCmp3: 1 if customer accepted the offer in the 3rd campaign, 0 otherwise
- AcceptedCmp4: 1 if customer accepted the offer in the 4th campaign, 0 otherwise
- AcceptedCmp5: 1 if customer accepted the offer in the 5th campaign, 0 otherwise
- Response: 1 if customer accepted the offer in the last campaign, 0 otherwise

#### Place
- NumWebPurchases: Number of purchases made through the company’s website
- NumCatalogPurchases: Number of purchases made using a catalogue
- NumStorePurchases: Number of purchases made directly in stores
- NumWebVisitsMonth: Number of visits to company’s website in the last month

## Target
Need to perform clustering to summarize customer segments.

## Conclusions
- Most customers didn't make a complaint in the last two years.
- Most customers have a single dependent/child in their household.
- Most customers made purchases via the Store.
- Most customers enrolled between 20 and 25 months ago
- Majority of the customers have partners.
- Majority of the customers have been Graduates.
- Majority of the customers are parents.
- Customers that didn't respond to campaigns are the majority.
- The earliest enrollments in the business were by customers aged 48.
- The total amount spent is highly correlated with customers income and the total purchases they made.
- The highest spending age groups are between 40–60
- Of the three metrics we used to evaluate the model, two of them(majority) suggested 2 clusters.
- Customers with no dependents/children have been the highest spenders.

## Business Insights
- To address the reluctance of customers in accepting the campaigns and encourage higher participation rates, tailor the campaign offers specifically to the preferences and needs of customers in cluster 1.
- To address the challenges of low income and low spending among customers in Cluster 1,  develop affordable and cost-effective products that cater to the budget constraints and you can also implement programs that provide incentives if they repeatedly buy a product more than once which will allow the, to continue engaging with the business even with their low income.
- The preferences, priorities, and purchasing behaviors of older customers in Cluster 0 may differ from those of the younger customers in Cluster 1 hence the need to consider age-related factors when developing new products or enhancing existing ones. 
- Given that the majority of customers make purchases from the stores, it is crucial to maintain a strong presence and optimize the in-store experience and while fewer customers make purchases online, it highlights the potential for growth in the e-commerce channel hence the business should focus on improving website usability.

  ## Contact
  For any questions or inquiries, please contact abdulraqibshakir03@gmail.com.
