
## 預估台積電(2330)隔日收盤價 <br>
程式碼參考https://www.kaggle.com/benjibb/lstm-stock-prediction-20170507 <br>
用過去22天(約1個月的交易日)的日開盤, 高價, 低價, 收盤價以及成交量做隔日收盤的預估 <br>
使用的是LSTM模型 <br>
 <br>
 
## 程式碼測試採用平台如下: <br>
Python 3.6.0  <br>
Keras <br>
Tensorflow backend <br>
 <br>
 
## 模擬結果:  <br>
前90%的資料為訓練資料<br>
後10%的資料為測試資料<br>
訓練資料的MSE為0.00040, RMSE為0.02<br>
測試資料的MSE為0.00036, RMSE為0.02<br>

![image](https://github.com/andrewwang7/stock_price_lstm/blob/master/stock_price_lstm_2330.png)
 <br>
 
##### 資料僅供參考不做任何獲利保證及特定股票跟點位推薦建議<br>
##### This model reference https://www.kaggle.com/benjibb/lstm-stock-prediction-20170507
