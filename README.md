# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 3: Sharing Dataset on Kaggle

---

### Statement
Along the journey of becoming the aspiring data scientist that I am, I have come to appreciate the value of data. I have also realized how difficult it is sometimes to obtain data. Yet, all over the world, data scientists are relentlessly gathering and sharing data, some of which I have used to be where I am today.


### Goal
Thus, in light of the importance of collecting, cleaning and sharing data, and in order to unlock higher data science skills, One can only show their appreciation by giving back to the community. I have therefore collected, prepared and shared a Dataset on Kaggle.com. I sincerely hope others will find it helpful and enjoyable to work with.

### Project Summary

- The dataset was prepared using  [Alpha Vantage API](https://rapidapi.com/alphavantage/api/alpha-vantage)
- API documentation can be found [here](https://www.alphavantage.co/documentation/)
- This API returns the daily historical time series for a digital currency (e.g., BTC) traded on a specific market (here, SAR/Sudi Riyal), refreshed daily at midnight (UTC).
- Prices and volumes are quoted in both the market-specific currency (SAR) and USD.
- Historical date range: 2018-05-11 to 30.01.2021
- Collected data was prepared, compiled into a DataFrame and uploaded on Kaggle.com with pubished starter notebook [here](https://www.kaggle.com/ahmedadam415/digital-currency-time-series)
- Suggested task would be to predict future stock price using ARIMA models with RMSE as an accuracy evaluation benchmark  
---
### Data dictionary

|Feature|Type|Dataset|Description|
|:-|:-|:-|:------------:|
|open_SAR|*float*|dc|Opening price Saudi Riyal(SAR)|
|open_USD|*float*|dc|Opening price (USD)|
|high_SAR|*float*|dc|Highest stock price (SAR)|
|high_USD|*float*|dc|Highest stock price (USD)|
|low_SAR|*float*|dc|lowest stock price (SAR)|
|low_USD|*float*|dc|lowest stock price (USD)|
|close_SAR|*float*|dc|Market closing stock price (SAR)|
|close_USD|*float*|dc|Market closing stock price (USD)|
|volume|*int*|dc|Trading volume|

---
#### FOLDERS

 - **code**:
  - contains API calls, parsing of JSON and conversion into DataFrame.
  - Also contains, data cleaning process and basic EDA
 - **data**:
  - contains all data files used in .csv format



#### LICENSE
- Alpha Vantage API terms of service, privacy policy and copyrights can be found [here](https://www.alphavantage.co/privacy/)
- All the code in this file is under MIT License. Re-use and/or alteration of code and associated documentation files is therefore permissible free of charge and without limitation.

---


**CONTACT:**

Ahmed Adam | Email: am4ma@hotmail.com
