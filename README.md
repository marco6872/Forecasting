# Forecasting
Forecasting of Product Sales Time Series in scikit-learn and PyTorch


Reviewed the bachelor's thesis, completely rewriting the code. Additional machine learning models were used to compare their performance with previous work. The thesis results were used as a baseline. Trained models included linear regression, random forest, fully connected network, 1D CNN, LSTM, and GRU. Training was done with and without outlier removal, using MSE and HuberLoss as loss functions. Various model types were created, with different depths and corresponding hyperparameter tuning. Due to the short time series data, more complex models did not outperform simpler ones, confirming model choice should align with problem type and available data.
