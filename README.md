 House Sell in King County

Overview

This project thoroughly assess the realtionship between house price and differnt factors that affect home price. 
Descriptive analysis and multiple linear regrsssion model was conducted to assess the correlation of these factors
including but not limited to condition of the house, square feet of the living room, number of bedrooms and bathrooms.
Understanding of these factors by potential home buyers will help them to plan and prepare for issues in regard to their budget
and enhance decision making capability in the process of purchaing the houses.

Business Problem

Seattle, Washington area became one of the center of trade and technology following the establishment of giant companies
like Amazon and Microsoft. Due to the influx of people to Seattle, the housing demand in and around King County has
also increased. However, most people do not have enough inforamtion about the housing pricne in the area. In ordert to assist
home buyers, it is found to be important to give them useful information about the various factors that affect the proce of houses.


Data 

The King County assessor website has an important set of inforamtion realted to housing.
Cetain types of data sets like the number of bedrooms, condition of the house, and grade
of the houses has a numeric, categrocial and coded type of values respectively.

Method

This project uses descriptive and multiple linear regression analysis of differnt factors.
This analysis gives brief overview of factors affecting the price of homes in King county.
simple and multiple linear regression models were developed to see the effect of differnt factors on  
home price, which eventally gives important inforamtion for home buyers.The model also predicts price of homes.

Results 

The heatmap figure below is showing the correlation between the price and all of the features in the dataframe. 
It is indicated that sqft_living has the highest correaltion with price.

![Correlation between the price of homes and other features](https://user-images.githubusercontent.com/37712711/136503211-523892ef-e32d-44ba-aac5-32477b87defb.png).

Among the many factors, Bathrooom happens to be multicolinear with other features.


Conclusions

Based on the above anlysis, the follwoing recommendaions are forwarded.
1.Home buyers must consider the square feet of the living room as an important price indicator and budget accordingly. 
   Sqfit_living is highly correlated with the price of houses. This can be further explained as for every unit of sqfit_living ,
   there is $206.8896 increase in the price of houses.
2.Home buyers should also consider the different grades of homes. As the grades increase, the price also increase.
3.Older houses are not cheap. Therefore, home buyers, should consider,sometimes recently built homes are cheaper than older homes.  
4.Home byers should not rely on this model prediction if they tend buy house outside King County.

Next Steps

Exploring and interpreting other factors which might affect the price of homes should be periodically updated. 
This could significantly help home buyers in many aspect realted to budgeting.

Price prediction methods should be evaluated and updated
The model develped in this study should be compared with other studies in order to come up with powerful prediction of home price.

This model can be used for home buyers in King County. 
Similar model predictions are encouraged to be developed by other counties and compared with King County.







