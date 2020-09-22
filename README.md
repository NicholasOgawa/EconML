Notebooks I have done on my free time using ML with a focus on finance/ economics.

#### CreditSpreads.ipynb 
- Using Quandl to extract Yield curve data, performing basic data visualization and data wrangling to plot yield curve and yield curve volatility. Testing a naive prediction model against a LSTM Neural Network architecture. Conduct Dickey Fuller Tests for Stationarity. 
- Applies a Multistep, multifeature, multilag model. In specific, we apply a 45 lags on 9 different maturity features, and conduct a 5-day/step for each feature. Compare LSTM model against our naive prediction model.

#### PCA-MVPY.ipynb
- Using FRED data and testing the empirical robustness of the MV = PY function taught in Macroeconomics courses. Includes visualization and wrangling to allow for reusability, since the dates are in different intervals.
- Using Principal Component Analysis to explain the variation in our time observations. What features were sicnifigant in different recessions or times of economics instability, interesting analysis of 2008 and 2020 compared to the 1970's. 
