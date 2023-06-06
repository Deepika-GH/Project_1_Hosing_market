# Project_1_Housing_market
Analyze data with various parameters.
# Analysis of 2018-2019 Housing Market Stats For British Colombia

# Number of Houses bought per gender for each 2018 and 2019
-Accodring to the data and charts you can see that there is a very little differnce in percentage of sales between the two genders
-Males have a very slight higher percentage of sales for both years

# Income Vs Housing Sales Price Weighted by Number of buyers
-According to the data there seems to be a weak to none correlation for the 3 variables 

# Regression test for above section (Income Vs Price Vs Number of Buyers)
-through the regression test you can mathimattically see that htere is weak to none correlation

###

# The Analysis is on Age vs Average Sale Price ,Number of buyers and Average buyer age . Considering both genders and all other factors in total for the year 2018 and 2019.

Below I have categorised my code and explained my Analysis

# 1. Age vS Average Sale price (answers the first question ) 

for the year 2018 people in the age group of 35 to 54 years old average sale price was 35.5 % 
and the same age group was spending around 0.1 % less in 2019 as Average sale price 

 2019 the Average sales price was more  by 0.6% for the age group under  35 years old

but the Average sale price decreased in 2019 by 1.9% for 55 years and older people
 
so there is no significant change in the stats they are very similar no significant change or  trend From here we can say Average sale price was for each group was approximately same


# 2.Age vs number of buyers(yes people 35 to 54 are buying more houses)

People in the age group of 35 and 54 years old were highest as number of buyers approx 2300 in 2018 
where as people under age of 35 years old were the least in number  to buy a property for both the years 
the people in 55 years and older age group were 1700 in the year 2018 and it decreased in 2019 . 

we saw the same trend for both the years that is a decrease in number of buyers 

# R3.egression line
There is a very weak correlation between the two variables 
The value is more concentrated towards 44 years old age group so the average buyer age where people were buying houses according to this graph is 44 
So more expensive the houses get less people are buying them with few outliers




###
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

================================================
Family Size and Housing Analysis- DEEPIKA
Investigate these 3 following Buyer Charecteristics:
                   1) Couple Family with Children
                   2) Couple Family without Children          
                   3) Lone (Single) Parent Family   
* Filtered the csv file to obtaine the above three Buyer Charecteristics and plot pie chart and Bar graph to represent the analysis
* Visualized regression testing to find correlation between variables
* plotted map graph using Geoapify API(to get latitude and longitude data).


