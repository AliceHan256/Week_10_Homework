# A Yen for the Future

This project will solve two problems in analysing the Yen's historical returns and predicting its movements using time series tools, time series forecasting and linear regression modeling. Investors can obtain better understanding about the risks of various currencies and make their business decisions.

# Technologies

In the time series analysis, several models have been utilised. ARMA is used for predict returns, ARIMA for predict "Settle" price, GARCH for forecast volatility. In the Linear regression model, it uses Scikit-learn function to train and test time series data in order to make out-of-sample predictions and evaluate its accuracy. 

# Conclusion

The time series model results show very high p-values and the AIC and BIC values are also pretty high, which mean none of the models is good to fit. Therefore, it's not a good time to invest the Yen at present. However, investors who are interested in derivatives may want to take this opportunity. 

The linear regression model result shows that the Out-of-Sample Root Mean Squared Error (RMSE) is about 0.42 and the In-sample Root Mean Squared Error (RMSE) is about 0.60. It is unusual that the RMSE value of the testing data (Out-of-sample) is less than that of the training data (In-sample). Therefore, although the out-of-sample data outperforms the in-sample one, one would like to explore further information to get better understanding about the risks and predictions before any investment.




