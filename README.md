# Data Science Project: Revenue-Forecasting
This is the monthly revenue forecasting using CNN (Convolutional Neural Network) as the base model. Around 9 and a half years of transaction data (aggregated per month) is used to generate next monthly revenue and transaction predictions. The aim is to predict whether the transaction and revenue is going to be on track (in target) or not.

# Technologies used
Python (Pandas, Numpy, Keras, Matplotlib, Sklearn, Plotly)

# Ilustration:
![alt text](https://github.com/cindysuyitno/Revenue-Forecasting/blob/main/newplot.png)

# Comments and Suggestion from Author
Revenue forecasting is very beneficial yet sometimes are tricky to do. A lot of models have been developed for the same purpose, such as ARIMA, SARIMA, Prophet, etc. But for lots of the time these models are not complex enough to detect seasonality and trend of the sales. Hence the thought of using deep learning tools to forecast revenue. Moreover, since the data for this project is highly sensitive to holiday and covid time, they have to be handled. The holiday time is flagged by binary number of 1 (holidays including christmas, new year, and ramadhan, since those 3 holiday always show peaks of revenue), while the covid data (2020-2021) are dropped since it does not depict the actual data trend (understandably, sales in covid time dropped drastically compared to other year). Many deep learning models have been examined and tuned to get the best prediction, in the end the train rmse for tuned-CNN model is 0.097 and the validation rmse is 0.136.
