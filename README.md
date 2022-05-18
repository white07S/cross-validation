# Cross validation in Finance and Quantitative models
# Volatility: 
Volatility is a statistical measure of the dispersion of returns for a given security or market index.

Cross validation based on different volatility measure.
# 1.Garman Klass Volatility 
Garman and Klass assumed that the process of price change is a process of continuous diffusion (geometric Brownian motion). However, this assumption has several drawbacks. The method is not robust for opening jumps in price and trend movements.
![image](https://user-images.githubusercontent.com/58583011/169019846-ab80f756-fd3f-4cc1-94e6-1fa1150fdb98.png)

# 2.Parkinson Volatility
Parkinson volatility is that the latter uses high and low prices for a day, rather than only the closing price.
![image](https://user-images.githubusercontent.com/58583011/169020443-5cc6a8c8-5d8a-4ed9-a780-3750496feb53.png)

# 3.Yang Zhang Volatility
Yang Zhang is a historical volatility estimator that handles both opening jumps and the drift and has a minimum estimation error.
![image](https://user-images.githubusercontent.com/58583011/169020752-2ac8592c-3bde-43ed-87d5-527bb95cbfb3.png)

# 4.Rogers-Satchell Volatility
Rogers-Satchell is an estimator for measuring the volatility of securities with an average return not equal to zero.
Unlike Parkinson and Garman-Klass estimators, Rogers-Satchell incorporates drift term (mean return not equal to zero).
![image](https://user-images.githubusercontent.com/58583011/169020966-efc0235b-2af7-49b8-aa53-857558d1df2d.png)

# 5. 

