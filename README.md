# time\_series\_forecasting_pytorch
Experimental source code:
Time series forecasting using pytorch，including MLP,RNN,LSTM,GRU, ARIMA, SVR, RF and TSR-RNN models.

Requirements

- python 3.6.3 (Anaconda)
- keras 2.1.2
- PyTorch 1.0.1
- tensorflow-gpu 1.13.1
- sklearn 0.19.1
- numpy 1.15.4
- pandas 0.23.4
- statsmodels 0.9.0
- matplotlib 2.1.0

## Code
- ARIMA.py: ARIMA model, iteration version
- Holt\_Winters.py Holt-Winters model, only primary version
- eval.py: evaluation metrics, including RMSE,MAE,MAPE and SMAPE.
- NN\_forecasting.py:neural networks forecasting
- model.py: neural network models
- train.py: training and predicting of neural network models, including RNN, LSTM, GRU, MLP, TSR-RNN 
- ts_decompose.py: time series decomposition
- ts_loader: data loader for neural network models
- ML_forecasting.py: general machine learning models, including SVR and RF
- util.py: data loader

## Related Repository

[Time Series Forecasting using Keras](https://github.com/zhangxu0307/time-series-forecasting-keras)

## Model compare (beijing pm2.5 data)
### MSE

- train time: 348.13783407211304
- test pred shape: (10929, 1)
- test MAE 0.0038882897
- test RMSE 0.004629571
- test MAPE 0.9013449773192406
- test SMAPE 0.9034011512994766

## Casamento

- train time: 406.5106370449066
- test pred shape: (10929, 1)
- test MAE 7.7727476e-05 
- test RMSE 0.00010306614
- test MAPE 0.036181669565849006
- test SMAPE 0.036206579534336925
