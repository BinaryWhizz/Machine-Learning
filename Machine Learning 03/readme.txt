pip install yfinance pandas matplotlib

The model performs close to random, indicating that short-term stock movement is highly noisy and difficult to 
predict using basic technical indicators 


The model achieved accuracy close to the baseline (50%), indicating that predicting next-day stock movement is 
highly challenging. Feature importance shows no dominant predictor, suggesting weak signal strength in the engineered 
features.


Conclusion

In this project, we built a supervised machine learning model to predict next-day stock price movement (up or down) 
using historical data of Reliance Industries.

Through exploratory data analysis, we observed that stock prices exhibit a strong long-term upward trend but are highly 
volatile in the short term. Feature engineering was applied to extract meaningful signals such as daily returns (momentum),
moving averages (trend), and volatility (risk).

A Random Forest classifier was trained on these features using a time-based train-test split. However, the model achieved 
an accuracy of approximately 50%, which is very close to the baseline accuracy (51%) obtained by always predicting an 
upward movement.

This result indicates that short-term stock price movement is highly noisy and difficult to predict using basic technical 
indicators. Feature importance analysis also showed that no single feature had strong predictive power, suggesting weak 
signal strength in the dataset.

Overall, this project demonstrates:

* The complete machine learning pipeline for time-series classification
* The importance of feature engineering in financial data
* The limitations of predicting stock market movements using simple models

Future improvements could include incorporating advanced technical indicators, additional external data (news, sentiment),
or more sophisticated models. 



