# Neural_Network_Charity_Analysis

## Overview of the analysis:

The objective of this project is to use deep-learning neural networks with the Tensorflow platform in python in order to classify and analyze the success of charitable donations. 
We use the following steps for analysis:
  1. Preprocessing the data
  2. Compile, train and evaluate model
  3. Optimization
  
## Results: 

### Data Preprocessing
- The columns EIN and NAME are identification information and have been removed from the input data.
- The column IS_SUCCESSFUL contains binary data indicating whether or not charitable donations were used effectively. This variable is then considered as the target for our deep learning neural network.
- APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT columns are the features for our model.
- Encoding categorical variables, spliting into training and testing datasets and standardization have been applied to the features

### Compiling, training and evaluating the model

The deep learning model is made of the following hidden nodes and features:-

Hidden Nodes Layer 1 = 80
Hidden Nodes Layer 2 = 30
Number of Input features = 43

To speed up the training process, we are using the activation function ReLU for the hidden layers. As our output is a binary classification, Sigmoid is used on the output layer.

This model acheived 72.7% accuracy with several attempts to incraese the accuracy. The model outcome is under 75%, hence it is not satifactory to predict the outcome of charity donations. We made the following attempts to increase accuracy:

- Increasing the number of hidden nodes in layer 1 (3 X number of input features)
- Increasing the number of hidden layers to include a 3rd
- Changing the activation functions: tried linear, tanh, sigmoid for a combination of hidden layers and output layer but none of them seemed to improve the model's   performance. 

## Summary:
The deep learning neural network model did not achieve the target of 75%. The target level was already set at an average level, hence we can conclude that the model is not outperforming. 

There could be a number of potential reasons for this result, such as using an incorrect number of neurons and layers, dropping columns that may have been useful to the model and vice versa, or failing to identify the best activation function to use.

