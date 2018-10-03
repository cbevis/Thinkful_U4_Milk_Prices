# Thinkful_U4_Milk_Production
Capstone project on graphing milk production

Data Sources
I obtained my data from several different sources. Cornell has a list of documents from the USDA that have monthly production estimates. However, the states they sample from to form the estimates change over time. This means that it true year on year comparisons are best from 1960-1985 or 1996-2018. I used factors to predict the US production based on the sampling production, but there will be some error associated with those factors. I merged my data set from US prodution with data on the US population from 1960-present and commodities pricing of milk, cattle, calves, corn, and soy.

Notes on data:

1960-1985 all 50 states were used for the estimates.
1982 from April-December, only quarterly data available, data set filled in with 1/3 amount for each month
1985-1993, 21 producing states sampled, I used factor of 1.185 to estimate 50 state total. I picked this factor because New Mexico was 2.4% of the total US production in 1995, so I made the factor larger than the 1994-1995 factor to accomodate this.
1994-1995, 22 producting states sampled, I used factor of 1.161 to estimate 50 state production, based on how production changed from February 1995 to February 1996
1996-2018, 23 producing states sampled, data also estimates values for all 50 states

USDA: http://usda.mannlib.cornell.edu/MannUsda/viewDocumentInfo.do?documentID=1103 
US Population: http://www.multpl.com/united-states-population/table?f=m 
Commodities Pricing: http://www.farmdoc.illinois.edu/manage/uspricehistory/us_price_history.html
