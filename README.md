# Customer-Segmentation

Problem Statement

Customer Personality Analysis is a detailed analysis of a company’s ideal customers. It helps a business to better understand its customers and makes it easier for them to modify products according to the specific needs, behaviors and concerns of different types of customers.

Customer personality analysis helps a business to modify its product based on its target customers from different types of customer segments. For example, instead of spending money to market a new product to every customer in the company’s database, a company can analyze which customer segment is most likely to buy the product and then market the product only on that particular segment.
Content

Attributes

People

    - ID: Customer's unique identifier
    - Year_Birth: Customer's birth year
    - Education: Customer's education level
    - Marital_Status: Customer's marital status
    - Income: Customer's yearly household income
    - Kidhome: Number of children in customer's household
    - Teenhome: Number of teenagers in customer's household
    - Dt_Customer: Date of customer's enrollment with the company
    - Recency: Number of days since customer's last purchase
    - Complain: 1 if customer complained in the last 2 years, 0 otherwise

Products

    - MntWines: Amount spent on wine in last 2 years
    - MntFruits: Amount spent on fruits in last 2 years
    - MntMeatProducts: Amount spent on meat in last 2 years
    - MntFishProducts: Amount spent on fish in last 2 years
    - MntSweetProducts: Amount spent on sweets in last 2 years
    - MntGoldProds: Amount spent on gold in last 2 years

Promotion

    - NumDealsPurchases: Number of purchases made with a discount
    - AcceptedCmp1: 1 if customer accepted the offer in the 1st campaign, 0 otherwise
    - AcceptedCmp2: 1 if customer accepted the offer in the 2nd campaign, 0 otherwise
    - AcceptedCmp3: 1 if customer accepted the offer in the 3rd campaign, 0 otherwise
    - AcceptedCmp4: 1 if customer accepted the offer in the 4th campaign, 0 otherwise
    - AcceptedCmp5: 1 if customer accepted the offer in the 5th campaign, 0 otherwise
    - Response: 1 if customer accepted the offer in the last campaign, 0 otherwise

Place

    - NumWebPurchases: Number of purchases made through the company’s web site
    - NumCatalogPurchases: Number of purchases made using a catalogue
    - NumStorePurchases: Number of purchases made directly in stores
    - NumWebVisitsMonth: Number of visits to company’s web site in the last month
    
    
# Conclusion Segmentation

## Write a short text of what is the key business takeaway of the recommendation.

## Group 0 <br>
- high spending and average income
- Are a parent
- Are older
- has teen at home
- Family size is atleast 2



## Group 1 
- high spending and high income
- More number of store purchases and catalog purchases
- Family size is atmost 3
- Atmost 1 child
- Spend on all products

## Group 2 
- low spending and low income
- more web visits
- at most 2 children
- have only 1 teen

## Group 3 
- high spending and low income
- spends more on wines and gold.
- more store purchases
- atleast size of family is 2
- definitely a parent
 
 # Conclusion Promotion
 ### Run SHAP analysis on the model results, and write a short text of what would be your recommendation to business for the next round of campaigns.?

<i>It looks like the campaigns had a very least effect on people and it has'nt pulled the audience to buy the product. Deals made with Disocunt may had been able to make more effect then Campaigns.Perhaps there is a need of better targeted and well planned campaigns.<i><br>
##### Recommendation to business for the next round of campaigns.
- Discounts can be mentioned in the campaigns
- Campaigns should be  more family oriented as we saw our data mostly contains families
- A strategy can be followed as we have already clustered data so we can provide valid recommendations to customers according to their interests.
- Some discounts  can be made on products displayed via campaign so that to sell more products at a cheap rate. This will help to retain customers.
-  Meat and Fish can be sold together at some discount rate.
- Campaigns should represent cultural aspects of the country that will drive more people towards them.
- Campaigns can use humour. As the memes will do the rest.
- Social Media can be used more effectively.








