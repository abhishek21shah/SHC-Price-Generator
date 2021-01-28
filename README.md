# Price_Generator

### A model was built to predict the price of secondhand clothing.
* Using a tool called [Web Scraper](https://webscraper.io/) data was scraped from a site called Vinted.com
* Data cleansing was performed by removing duplicates from the dataset and transforming/removing nulls for various features.
* Various regression models were trained to see which resulted in the lowest Mean Squared Error (Linear & Ridge Regression had similar results)
* Model was further validated by hypertuning the paramters and cross-validating using K-fold.
* Next steps are:
   * Check if Bias/Variance issue with the data.
   * Try new data if above issue cannot be fixed.
