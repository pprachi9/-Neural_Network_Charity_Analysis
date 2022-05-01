# Neural_Network_Charity_Analysis

## Overview of the Analysis

In this analysis, Tensorflow was used to run a neural netwrok analysis to predict where to make investments by using a charity dataset of 34,000 organizations that we recieved for funding. This analysis contains 3 steps: Preprocessing the data for the neural network model, then compile, train, evaluate and optimize the model. 

## Results:

### Data Preprocessing

1. What variable(s) are considered the target(s) for your model?
- The variable we are targeting in this module is the IS_SUCCESSFUL column.

2. What variable(s) are considered to be the features for your model?
- The features that we are using are every column except the ones that we will drop.

3. What variable(s) are neither targets nor features, and should be removed from the input data?
- First features we drop are the 'EIN' & 'NAME' because we expect both features to have little to do with our outcome.

### Compiling, Training, and Evaluating the Model

1. How many neurons, layers, and activation functions did you select for your neural network model, and why?
- The first hidden layer has 80 neurons, the second has 30 there is also an output layer. Each layer has an activation function. The first and second hidden layers have an activation function "relu" & the output layer is "sigmoid".

2. Were you able to achieve the target model performance?
- Although we the target for the model was to be 75% or above, I was not able to reach the target.

3. What steps did you take to try and increase model performance?
- Some of the steps I took to try and make the model more accurate were adding hidden layers, changing the activation type, changing the number of epochs and changing the number of neurons in each layer.

## Summary

The accuracy of the model ended up being 72% and we can conclude from this that the deep learning model was not optimized for optimal target performance to identify which charities to invest in. An SVM may have been a better model to solve this classification problem because it is intended to be a binary classifier and can conduct the same analysis without going very deep. 
