# XGBoost-to-predict-the-scenario-to-buy-or-sell-stocks-of-retail
A model based in Extreme Gradient Boosting (XGBoost) to predict buy and sell stocks of retail sector.

XGBoost (eXtreme Gradient Boosting) is an ensemble learning method. Sometimes, it may not be sufficient to rely upon the results of just one machine learning model. Ensemble learning offers a systematic solution to combine the predictive power of multiple learners. The resultant is a single model which gives the aggregated output from several models.

The retail sector consists of all companies that sell goods and services to consumers and macroeconomic scenarios are multi-year projections of economic variables. The retail sector is sensitive to macroeconomic variations, especially when there are low gross domestic product (GDP) projections, high interest rates and high inflation rates.

Therefore, the aim of this study was to establish a model using random forest to predict the macroeconomics scenario to buy or sell stocks of retail sector.

MACROECONOMIC INDICATORS AND RETAIL STOCKS

Lojas Renner (LREN3) was chosen to be a representative stock of the retail sector of companies traded on B3 (brazilian stock exchange). The indices Broad National Consumer Price Index (IPCA), Special System for Settlement and Custody (selic), Central Bank Economic Activity Index (IBC-Br), Broad Retail Trade Confidence Index (ICOM), Future Expectations Index, Dollar (exchange), Consumer Stock Index (ICON) and Ibovespa Index (IBOV) were initially analysed by correlation. Data from during 10 years were used (2011-2021).

Dataset Source: https://figshare.com/articles/dataset/Macroeconomic_indices_used_in_predictive_model_for_retail_sector_in_Brazil/22674859

STOCK TREND

The trend of the stock was considered only bullish or bearish (binary classification). When the trend was sideway and followed by a uptrend, the trend was considered uptrend because it would be a good opportunite to buy. This same reasoning was used when there was a lateralization followed by a bearish trend.

RESULTS

![Table 1 XGBoost](https://user-images.githubusercontent.com/78765404/235250807-73140429-c4c2-4f80-ac91-eeb726eb8b87.png)

REFERENCES

da Silva, André Luís Lopes (2023): Macroeconomic indices used in predictive model for retail sector in Brazil. figshare. Dataset. https://doi.org/10.6084/m9.figshare.22674859.v1


