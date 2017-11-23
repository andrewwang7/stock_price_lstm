This model reference https://www.kaggle.com/benjibb/lstm-stock-prediction-20170507

=====================================================================================

預估台積電(2330)隔日收盤價
程式碼參考https://www.kaggle.com/benjibb/lstm-stock-prediction-20170507
用過去22天的日開盤, 高價, 低價, 收盤價以及成交量做隔日收盤的預估
使用的是LSTM模型

程式碼測試採用平台如下:
Python 3.6.0
Keras 
Tensorflow backend

前90%的資料為訓練資料
後10%的資料為測試資料
訓練資料的MSE為0.00040, RMSE為0.02
測試資料的MSE為0.00036, RMSE為0.02

![image](https://github.com/andrewwang7/stock_price_lstm/blob/master/stock_price_lstm_2330.png)

資料僅供參考不做任何獲利保證及特定股票跟點位推薦建議
