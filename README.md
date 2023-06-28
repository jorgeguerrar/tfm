# Forecasting the electricity load daily peaks
This is a github repository of the code developed for my Final Thesis of the Master's degree in Big Data Analytics of Carlos III University. 

This thesis aims to forecast daily peaks of electricity demand combining statistical modeling techniques and machine learning approaches. The study evaluates the predictions using various evaluation metrics, scenarios and a training/testing partition strategy with backtesting. Initially, the research focuses on forecasting without covariates by means of Auto-Regressive Integrated Moving Average (ARIMA) models fitted to the latent factors given by a Dynamic Factor Model across different forecasting scenarios outperforming the benchmark of a dummy model. Subsequently, it incorporates weather covariates as regressors in an Interactive Fixed-Effects Model. Latterly, it purposes some attempts to enhance the accuracy through polynomial regression and binary variables for explaining the non-linear relationships. The research emphasizes the importance of capturing subtle variations for peak demand prediction and introduces a K-nearest neighbors model that identifies the most common peak hour within some of the nearest training set days, assigning that peak hour as the predicted peak hour of each day in the test partition.
