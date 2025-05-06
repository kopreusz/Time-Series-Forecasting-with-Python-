# Time-Series-Forecasting-with-Python-
In this repo I am going to share my time series forecasting journey with theory and different ML/AI models using the most popular Python libraries.

In this project we'd like to predict the S&P 500 index's price. We have used a Recurrent Neural Network as our model and trained our model on the first 300 samples 
where the data is ordered by time. We've left the last 31 days' prices for the testing set. 

IMPORTANT: Our first attempt in the time series forecasting game ended up by predictiong prices. We've fitted a minmax scaler on the training data for the sake of preventing data leakage, while it would be a much safer choice to fit the scaler and train the model on the daily returns, rather then the current price.
