# vnpy trading helper

### About

trading helper  based on vnpy crypto engine


### Features

*Stoploss orders*

*Takeprofit orders*

*Takeprofit by grid*: (20%-30%, lock 20%) (30%-40%, lock 30%) configurable

*Trigger reverse orders (manualy)*: avoid the spike, follow the reversal

*Trigger snipper orders (manualy)*: avoid the back fire, follow the trend

*(Other higher-order trigger orders)*: ...


### Structure 


vnpy_engine -> crypto_engine -> okex_engine

                             -> binance_engine
                             
                             -> other exchanges

### Requirements

```
pip install -r requirements.txt
```


### Welcome PR
