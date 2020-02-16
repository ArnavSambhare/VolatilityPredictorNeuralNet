# VolatilityPredictorNeuralNet
<br>
With inspiration from models like EWMA, GARCH volatilty models, a neural network would be able to map better non-linear relationships between returns and historical volatility.<br>
This repository contains a pipeline to load, process and train a model to predict future volatilities.<br>
The architecture of the neural network was chosen based on several tests done privately and this architecture performed the best.<br>
This model was tested on AAPL's historical pricing data(1980-2019). The model performed well with the loss(mean squared error) being 5.01E-06. Differences between the true and predicted values exceeded 1% only twice in 7 years of out-of-sample data.
