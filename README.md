# Data_Visualization
Project 5: Data Visualization

Communicate Data Findings
By Tobias Hagemann

Core of the analysis are the "Posprt Loan data". The file contains a huge amount of different loan related data mainly relating to the borrower's, their background and the loan conditions.

The data set is really tidied and clean so data wrangling is just a minor topic here. Main characteristic is the high number of columns and with that different contents.

The first real obvious finding is, that many entries are not valuable as they are too generic. E.g. the occuption can be called out as "Other" or "Professional" and as this happend int the majority of cases, these data set cannot be used for proper evaluation.
The occupation data is not usable and also not a fully accurate indicator for the prosperity. So therefore the prosperity rating is considered. This rating is showing, that the borrowers are spreaded over all catergories from good to very weak. This leads into the conclusion, that the rating alone is not the single decission baesline for giving loans. 

Based on those results it is analysed if even the rating has no impact on giving loans, the rating level is anyway impacting the loan. A correlation plot considering the several imperic data with regards to the borrowers is showing that indeed the prsoperty ranking has a high correlation value of -0,668. No other analysed value had such a strong correlation in the plot.

A detailed analysis via heatmap analysis is outlining, that better ratings (AA-B) are resulting in nearly all cases into APRS under 0,25 while there is a clear orientation form c to HR with increasing APRs.

As conclusion it is clearling turning out that the loan conditions are related to emperical data banks can trust it. The Prosperity Ranking is therefore a common considered value.
