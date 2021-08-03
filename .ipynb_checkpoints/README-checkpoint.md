# Deep-Learning-Homework

## In this assignment, taught us  deep learning recurrent neural networks to model bitcoin closing prices. One model used the FNG indicators to predict the closing price while the second model used a window of closing prices to predict the nth closing price.

Steps for the Exercise:

1. Prepare the data for training and testing](#prepare-the-data-for-training-and-testing)
2. [Build and train custom LSTM RNNs](#build-and-train-custom-lstm-rnns)
3. [Evaluate the performance of each model](#evaluate-the-performance-of-each-model)

### Evaluating the performance of each model

> Which model has a lower loss?
If you use the closing price then that Model has a lower loss based on testing , tranining and evaluating.
>
> Which model tracks the actual values better over time?
Using Closing prices is key 
>
> Which window size works best for the model?
 It appears that 10 works the best with tracking actual values and also with the loss (with the window size of 10;  0.007 loss score was the lowest).