# SaaS revenue analysis

## All analysis:
Analysis of revenue by product, comparing product sales by date and location - [first dashboard](https://public.tableau.com/app/profile/valentyn.hrechanyi/viz/saas_revenue_analysis/Dashboard1).
Cohort analysis of customer payments from first purchase and revenue dynamics - [second dashboard](https://public.tableau.com/app/profile/valentyn.hrechanyi/viz/saas_revenue_analysis/Dashboard2#1).

## Tool

Tableau.

## Data

All data is in [this table](https://docs.google.com/spreadsheets/d/167q-LM-OyXMaa9GmWJhWJgqZUyBTL5flT8qVIZ_FbO4/edit?usp=sharing):
* user_id - unique id of customer;
* payment_date - date of purchase (from June 2022 to May 2023);
* location - region of customer (USA, EMEA (Europe, the Middle East and Africa) and APAC (Asia-Pacific));
* software_name - product bought;
* is_enterprise_customer - if customer are corporation;
* revenue_amount - amount of purchase.

## Purpose

Analysis of product revenue by date and location. 

## Information from analysis on dashboards

### [First dashboard](https://public.tableau.com/app/profile/valentyn.hrechanyi/viz/saas_revenue_analysis/Dashboard1)

1. Distribution of revenue by location.
2. Range of revenue per purchase.
3. Revenue dynamics of each product during the year.
4. Change in the revenue share of each product during the year.
5. Revenue by region and product.
6. Change in the number of paid users and ARPPU during the year.

### [Second dashboard](https://public.tableau.com/app/profile/valentyn.hrechanyi/viz/saas_revenue_analysis/Dashboard2#1)

1. Dynamics of changes in revenue along the customer's journey from the first purchase (cohort analysis in the month of the first purchase). 
2. Dynamics of changes in total profit during the year.  
3. Dynamics of changes in revenue from new customers during the year.

## Іnsights

### From [First dashboard](https://public.tableau.com/app/profile/valentyn.hrechanyi/viz/saas_revenue_analysis/Dashboard1)

1. Locations by profitability:
1) USA; 2) APAC; 3) EMEA;
2. Median revenue is 17,5$ (Range - from 10 to 25, Interquartile range - from 12,5 to 22,5)
3. From June to September the most profitable product was Marketing automotion, from October to December and from March to May - Customer success (in March and April along with Main App), in January and February - Main app. 
4. The most unprofitable product is Publishing.
5. For APAC region the most profitable products are Customer Success (approx. 293K$) and Main App (approx. 137K$).
For EMEA region - Publishing (approx. 85K$) and Main App (approx. 81K$).
For USA region - Marketing Automation (approx. 297K$) and  Main App (approx. 187K$).
6. Count of paid users were rosed rapidly from June (753) to March (4,018) and fell to 3,623 in May.  However, ARPPU decreased from June ($58.55) to December ($37.53), then held around December's level.

### From [Second dashboard](https://public.tableau.com/app/profile/valentyn.hrechanyi/viz/saas_revenue_analysis/Dashboard2#1)

1. From cohort analysis we know that in almost all months except October there are 3 tendentious: 1) revenue in 1 month of purchase approx. the same as in 3 month;
2) the largest revenue is in 2 month; 
3) after 3 month revenue is falls sharply (instead of September and November cohorts);
4) after 4 month revenue changes are very low.
2. We can see that the graph of the change in revenue from new customers is very similar to the graph of the change in total revenue as a percentage, which confirms the trend from the cohort analysis - changes after 4 months after 1 purchase are negligible. Attention: we don't know revenue from new customers in June because we haven't any information about purchase history in previous months.
3. Total revenue increases from June to March (except for December, which also has one of the lowest new user revenue), then starts to fall. At the same time, in March the amount of revenue from new users drops sharply: from $26,235 in March to $17,845 in April.
