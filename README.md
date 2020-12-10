# Sales-Forecasting-Model

Lankatiles PLC has two main product fields; wall tiles and floor tiles. Each of them has more than 15 sub categories. For wall tiles, 3 machine learning models were developed for predicting future sales quantities by training sales data of past 6 years, 4 years and 2 years. Same task was performed for floor tiles too. I tried using Random forest classifier, Gradient boosting and Fully connected neural networks.

Gradient boosting had the best sales predicting model for 4 years trained data of wall tiles, and Random forest classifier had the best sales predicting model for all other five. Finally, Random forest(number of estimators=240) model for 6 years trained data was used as the forecasting model for wall tiles, and Random forest(number of estimators=75) model for 2 years trained data was used as the forecasting model for floor tiles.
