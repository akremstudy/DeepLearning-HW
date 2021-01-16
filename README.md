# Deep Learning HW
### Long-Short Term Memory (Recurrent Neural Network)

Build and train LSTM RNN models and evaluate their performance in making predictions using two different metrics. Fear and Greed index vs. historical prices.


Which model has a lower loss?

>The model with historical closing prices had a lower loss: 0.0886 compared to model with F&G values as the feature, loss: loss: 0.3022. This was at 10 epochs and window_size = 10

Which model tracks the actual values better over time?
> The model that tracked the values better over time was the model that used historical prices to make predictions.

Which window size works best for the model?
> Three window sizes(10,20,30) were tested and the models had a lower loss with better tracking of actual values except for the model with the historical prices when tested with window_size=30.It had a higher loss in comparison with the other window sizes and it tracked better with actual values perhaps due to overfit. The models were fit with 10 epochs.