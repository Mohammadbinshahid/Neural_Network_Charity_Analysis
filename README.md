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
