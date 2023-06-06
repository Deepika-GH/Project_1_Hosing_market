# Project_1_Housing_market
Analyze data with various parameters.

**IMMIGRANT STATUS ANALYSIS BY HUMA ALAM**
Looking at the Immigrant Status of Immigrant and Non-Immigrant against the BC Housing Market in 2018-2019.

**Data:**
We used the Statistics Canada Data:
https://www150.statcan.gc.ca/t1/tbl1/en/cv.action?pid=4610006201

**Data Cleaning:**
First step is to clean up the data by:
 - Checking and Removing Null Values
 - Removing non-relevant columns
Secondly, we need to isolate the immigrant status which are in the Buyer Characteristics column and the overall totals for each category, which is shown row wise. We create a data frame to isolate the column Buyer Characteristics = Immigrant and Non-Immigrant. Then we isolate the totals:
1)	Number of property buyers                
2)	Average total income of property buyer   
3)	Average family total income               
4)	Average sale price                       
5)	Average buyer age    

**Once we have our data isolated for Immigrant and Non-Immigrant status, we are ready to run some analysis:**
**1)	Immigration Status and Average Number of Property Buyers 2018-2019:**
-	Now that we have the Immigrant Status filtered data frame, we are now, narrowing down to specific totals, in this case, we are looking at the affects of Number of Property Buyers.

**-	**ANALYSIS:**** There is a significant difference between property bought by Immigrants and Non-Immigrants. Almost 50% more houses were bought by Non-Immigrants against Immigrants. The trend follows for both years; 2018 and 2019. This can be explained by the different priority of people in Immigrant Status and also alludes to the inherited wealth/ assets that can be leveraged in the housing market.                     

**2)	Correlation between Immigration Status vs. Average Sales Price and Average Total Income Property Buyer**
- We are looking at both 2018-2019 years to see if Total Income vs. Sale Price makes a difference depending on your immigration status. (Estimate Column filtered by Average Sales Price and Total Income Property Buyer, one data frame for Immigrants and another for Non-Immigrant)
**-	ANALYSIS:** With the regression test we can see that r-value is less than 0.30 meaning it has no correlation. There is no correlation between the Average Price and Average Total Income of Property Buyer in BC, this can indicate that there are multiple other factors that can affect it.

