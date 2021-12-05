# Description
This research mainly uses the data of Hushen 300 index from 2005 to 2021 and the data of 22 citic first-level industries. Python3.8 version is used to calculate the industry β according to the capital asset pricing model (CAPM). The spearman rank correlation coefficient between industry β and industry rate of return was calculated to analyze the market performance and forecast the future trend of Hushen 300 index. Through sensitivity analysis of the data in the sample, this study selected the relatively stable spearman rank correlation coefficient threshold and the calculation range of β. When the spearman rank correlation coefficient exceeded the threshold, this model would send long or short signals to guide investors' strategies. It is found that the model has good stability in the long term and performs well under the condition of stable market. The sharp change is the main risk of this model.

# To Start
1. ```data.ipynb``` Filter data from different sources(windA, hs300 and CITIC) according to timestamps.
2. ```choose_capm_hs300.ipynb``` Calculate β and rank correlation coefficient to buy hs300.
