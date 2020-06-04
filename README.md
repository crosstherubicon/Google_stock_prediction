# Google-Stock-Price
Using 2012-2016 open Google stock price to predict 2017 opening google stock price using Recurrent Neural Network stacked LSTM. 


The dataset is split into training data with Google stock price from the year 2012-2016 and testing data with stock price in 2017. The training data consists of 13,000 data points - there are six variables, i.e., the date which is essentially dates from January 2012 through December of 2016, the opening stock price on a financial day, the highs and lows, the closing stock price value and the volume of the stock trading. The test contains the opening price for the quarter of 2017 to verify the LSTM model. 


<br>
<p align="center">
<img src = "results/rnn_20timesteps_1lstmlayers.png" width = "700" height = "450">
 </p>
<br>
