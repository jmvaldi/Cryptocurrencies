# Cryptocurrencies
## Overview
The purpose of this analysis is to create a portfolio on cryptocurrency investment to an investment bank. The report includes the cryptocurrencies that are on the trading market and a classification system to group the currencies. Since the outout for the system is unknown and its a new type of investment, an unsupervised machine learning route is taken with data provided by CryptoCompare.

## Results
The data provided for the cryptocurrencies was preprocessed for currencies that are actively trading, have a defined algorithm, and a complete set of data with no null values. The data was then standardize with a scaler and then reduced to three principal components using PCA. A PCA dataframe was made using the results and then an elbow curve was done to find the best K-mean. From the chart it was deduced that the best K value was 4. This output was initilaized in a model and the predicted clusters were concatinated into a dataframe with the PCA dataframe. THe new dataframe was then visualized into a 3D scatter model to show how the different cryptocurrencies were grouped together. 

After this a 2D scatter plot was created with the tradable cryptocurrencies. THe graph shows the relationship between the total coin supply and the totla coin mined.

## Summary
From the graphs you can observe that there are two groups that are clumped together (very close proximity), another group is that is not that distant from the first two, and then the fourth group that is farther away. Most of the groups are performing relatively similar to one another while the distict group that is farthest seems to be performing differently than the rest. Further analysis should be done to compare the current performances of the cryptocurrencies with past behaviors for a more complete report to present to the investors.  

