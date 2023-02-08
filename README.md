# Neural_Network_Charity_Analysis

## Overview of the loan prediction risk analysis
This analysis uses features in the provided CSV dataset to create a binary classifier that is capable of predicting whether loan applicants will be successful if funded.

## Results:

### Data Preprocessing
- The data from the "IS_SUCCESSFUL" column was used as the target variable for the model. 
- The variables used for the features of the model were the columns "APPLICATION_TYPE", "AFFILIATION",	"CLASSIFICATION", "USE_CASE", "ORGANIZATION", "STATUS", "INCOME_AMT", "SPECIAL_CONSIDERATIONS", "ASK_AMT"
- The columns "EIN" and "NAME" containing identification data are neither targets nor features, and were removed from the input data.

### Compiling, Training, and Evaluating the Model
- To try and reach target performance without over training, I used 8 neurons in the first hidden layer and 5 in the second hidden layer.
- Target model performance was not achieved.
- To try and increase model performance I adjusted the number of neurons, hidden layers, epochs, and activation functions.

## Summary:

While this model may predict some risk for loan applicants, it is not achieving target performance even with adjustments. I do not think this model is the best choice for predictions using this dataset. To solve the classification problem, I would suggest a supervised learning algorithm to achieve better model performance. 
