# Seattle_housing_price_regression

Analyzing the factors associated with housing prices in King County, WA. After dataset is cleaned, exploratory data analysis is conducted in order to get a sense of the data. Then predictions are run using various regression techniques and feature selection is done to figure out which aspects of housing data most heavily contributed to house price prediction. 

From the results of the analysis, location seems to be a large factor as the regions closer to Seattle have higher costs for houses, which makes sense. Another result is the house prices seem to reach a good maximum around the 2-3 bedroom range and 1-2 bathrooms. Any more and the price increase starts to decrease per level of investment made. 

Multiple models were tested and validated using mean absolute error and cross validation. A gradient boosted regressor turned out to be the most performant with an accuracy of 85% and a mean error of $60,000 amongst the tested properties.
