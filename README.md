Onion Market Time Series Prediction
This repository contains a time series prediction model for the onion market in Mumbai. The model utilizes the SARIMAX algorithm, which has shown excellent performance in forecasting onion prices.

Dataset
The dataset used for this project consists of historical onion market data, including the date variable and the Modal Price (Pricemod) of onions in Mumbai. The dataset covers a significant period, providing enough data points for accurate analysis and prediction.

Model Building
Two models were developed: Holt Winter and SARIMAX. After careful evaluation, the SARIMAX model demonstrated superior performance, achieving the lowest Root Mean Squared Error (RMSE) value of 410.

Model Usage
To use the SARIMAX model for predicting onion prices, follow these steps:

Install the necessary dependencies listed in the requirements.txt file.
Preprocess the dataset by handling missing values, outliers, and performing necessary transformations.
Split the dataset into training and testing sets, ensuring a suitable timeframe for validation.
Train the SARIMAX model using the training data, optimizing the hyperparameters for better performance.
Evaluate the model using metrics such as RMSE to assess its predictive accuracy.
Once satisfied with the model's performance, utilize it to predict onion prices for the next year.
Conclusion
By leveraging the SARIMAX model, this project aims to provide accurate predictions for onion prices in Mumbai's market. Users can refer to the provided notebooks for a detailed understanding of the data preprocessing, model training, and prediction steps. The model's robust performance, as indicated by the low RMSE value, ensures reliable insights for stakeholders in the onion market.
