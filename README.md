# Neural_Network_Charity_Analysis

## Overview

Alphabet Soup has tasked us to use maching learing to analyze past data to help determine if a future applicant will be successful.

The data consists of over 34,000 organizations that have previously received funding from ALphabet Soup. We will take this data and apply it to 3 different machine learning models to see if one has the potential to predict whether an applicant will be successful.

## Results

### Data Preprocessing
  1. What variable(s) are considered the target(s) for your model?
    
   - The variable column IS_SUCCESSFUL was the target for this model. This column determines if the money was used effectively (1 - Successful and 0 - Not Successful).
    
  2. What variable(s) are considered to be the features for your model?
  - The features of this model are: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL CONSIDERATIONS, and ASK_AMT.
  
  3. What variable(s) are neither targets nor features, and should be removed from the input data?
  - We first removed columns NAME and EIN. THen during optimization, wewe also dropped STATUS and SPECIAL_CONSIDERATIONS.
    
### Compiling, Training, and Evaluating the Model
  1. How many neurons, layers, and activation functions did you select for your neural network model, and why?
  - The first model - layer 1 had 80 neurons with a "relu" activation. The second layer had 30 neurons. The output layer used the activation "sigmoid".
  
  2. Were you able to achieve the target model performance?
  - After running through three models, the highest accuracy rating outcome was 72.6%. This is not high enough to predict if an applicant will be successful. So, no, we did not acheive the target model performance.
  
  3. What steps did you take to try and increase model performance?
  - To attempt to get increased model performance, we experimented with adding neurons and hidden layers, and then changing the activation functions with no success.
  

## Summary
We were not able to acheive the 75% accuracy levels that was asked with the deep learning neural network. Multiple models were ran with different techniques. We will need to experiment with different techniques to get the 75% accuracy.
