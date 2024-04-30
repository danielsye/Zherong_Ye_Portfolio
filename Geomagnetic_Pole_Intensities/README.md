# Geomagnetic Pole Intensities
Time Series Analysis in R

### Project Overview
The Earth’s magnetic field plays a crucial role in various aspects of our planet. Understanding the behavior of the Earth’s magnetic field is of paramount importance due to its significant
impact on our planet and its inhabitants. Where it plays a critical role in navigation systems, industries, and satellite technology, making it a topic of great relevance and interest.
Through a comprehensive analysis of the data set and the application of appropriate forecasting techniques,
this study aims to provide valuable insights into the behavior of the Earth’s magnetic field, its changes over
time, such as whether there is seasonality within these behavior or there is a significant trend. The goal of
this analysis, is to find models which may effectively predict the future trends of such behavioral changes in
the magnetic fields of the North and South poles.


### Data Sources
The primary dataset used for this analysis is "Geomagnetic_Intensity_Data.xlsx". The data set includes historical measurements of magnetic field intensity, typically collected from magnetic
observatories and satellite measurements of the North and South Pole, covering a significant time span. 

### Tools
- Jupyter Notebook
- R Markdown

### Fitting and Diagnostics
- ACF and PACF analysis
- Unit root and Stationarity Tests
  - ADF Test
  - KPSS Level Test
  - KPSS Trend Test
- Transformation vs Differencing
- Selecting ARMA Model
  - EACF
  - AIC & BIC
  - Standardized Residuals
  - QQ Plot & Sgapiro Test
- Residual analysis
- Seasonality

### Model Specification
The model that has been derived using 90% of the Geomagnetic Intensity Data as training data.

#### North:
Model specification: ARIMA(5,3,4)
- Autoregressive (AR) component of order 5
- Differencing (D) of order 3
- Moving average (MA) component of order 4

#### North:
Model specification: ARIMA(5,2,5)
- Autoregressive (AR) component of order 5
- Differencing (D) of order 2
- Moving average (MA) component of order 5

### Bibliography
- A chapter on Unit Root TestsDownload A chapter on Unit Root Tests (from Applied Econometric Time Series)
- Summary of ADF and KPSSDownload Summary of ADF and KPSS, Dr. Masoud Ataei
- Danielsson, Jon, Casper G. de Vries, and Björn Jónsson. “On the Distribution of Test Statistics in Unit Root Testing.” Econometrica 67, no. 5 (1999): 1027-58. doi:10.1111/1468-0262.00064.
- Brockwell, P. J., and R. A. Davis. Introduction to Time Series and Forecasting. 3rd ed., Springer, 2016.
- Tsay, R. S. (2014). Multivariate time series analysis: With R and financial applications (3rd ed.). Wiley. Chapter 4: Stationarity and differencing.
- Hyndman, R. J., & Athanasopoulos, G. (2018). Forecasting: Principles and practice (2nd ed.). OTexts.
- Box, G. E. P., Jenkins, G. M., and Reinsel, G. C. Time Series Analysis: Forecasting and Control. Wiley, 2015.
