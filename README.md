# TimeSeries_Mauna_Loa
The Mauna Loa CO_2 Concentration

In this project the time series data given for analyzing and forecasting co_2 concentration given by Institution of Oceanography recorded over 60 years. 

### INtroduction:
In 1958, Charles David Keeling (1928-2005) from the Scripps Institution of Oceanography began recording carbon dioxide (CO2) concentrations in the atmosphere at an observatory located at about 3,400 m altitude on the Mauna Loa Volcano on Hawaii Island. The location was chosen because it is not influenced by changing CO2 levels due to the local vegetation and because prevailing wind patterns on this tropical island tend to bring well-mixed air to the site. While the recordings are made near a volcano (which tends to produce CO2), wind patterns tend to blow the volcanic CO2 away from the recording site. Air samples are taken several times a day, and concentrations have been observed using the same measuring method for over 60 years. In addition, samples are stored in flasks and periodically reanalyzed for calibration purposes. The observational study is now run by Ralph Keeling, Charles's son. The result is a data set with very few interruptions and very few inhomogeneities. It has been called the “most important data set in modern climate research."

### Motivation:
We use different techniques in Machine Learning such as Linear Regression, quadratic and other polynomial regressions to find the trends and seasonality in the data. It helps us to find the best regression model to remove the trends in the data and analyze it for prediction of the future CO_2 concentration. It is good practice to be familiar more with time series data and also machine learning techniques. 

### Libraries

The scilit-learn is used in training and validating the predictions. 
**LinearRegression**,**PolynomialFeatures** and sklearn_metrics are used for evaluation of the validation data. 
*8Matplotlib** is used for plotting the data.
Other important libraries such as **pandas** and **numpy** are used as usual. 
Two important error evaluation root mean squared error(RMSE) and mean absolute percentage error(MAPE) are used to test the accuracy of the methods. 

### Results:
The different regresion models are evaluated and it is concluded that the lowest degree which gives lower error based on the metrics described above is the quadratic regression tool. 

𝑅𝑙𝑖𝑛𝑒𝑎𝑟  shows a systematic concave upward trend, 𝑅𝑞𝑢𝑎𝑑𝑟𝑎𝑡𝑖𝑐 does not have a clear systematic trend, and 𝑅𝑐𝑢𝑏𝑖𝑐 closely resembles 𝑅𝑞𝑢𝑎𝑑𝑟𝑎𝑡𝑖𝑐 in terms of both trend and magnitude.

### Acknowledgement:

Thanks to the MIT(Massachusetts Institute of Technology) excellent projects in data analysis and applications of machine learning on edx micro master program. This project is part of their projects and it can be evaluated more in the future. 


