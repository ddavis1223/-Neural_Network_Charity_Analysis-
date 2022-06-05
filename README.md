# -Neural_Network_Charity_Analysis-

## Overview of Project

### Purpose
The purpose of this project is to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

## Results
From this analysis, we can address the following questions regarding Data Preprocessing:
     * The variable that was considered the target for the model was "IS SUCCESSFUL".
     * The variables that were the features for the model was:
        "APPLICATION_TYPE"
        "AFFILIATION"
        "CLASSIFICATION"              
        "USE_CASE"                     
        "ORGANIZATION"                 
        "STATUS"                      
        "INCOME_AMT"                  
        "SPECIAL_CONSIDERATIONS"       
        "ASK_AMT" 
        "IS_SUCCESSFUL"                
     * "EIN" AND "NAME" were removed from the input data.

From this analysis, we can address the following questions regarding Compiling, Training, and Evaluating the Model:
     * The deep-learning neural network model was made up of two hidden layers with 80 and 30 neurons.
     * The activation function that was used for the neural network model was relu. This was used because it is simple and fast and it does not activate all the neurons at the same time.
     * The other activation function that was used for the output layer was sigmoid because it transforms the values between the range 0 and 1.
     * I was not able to achieve the target model performance.
     * I added another layer to the model performance in order to increase the accuracy but it lowered the accuracy.

## Summary
The deep learning model that was used failed to reached its target performance of 75%.  I would recommend using Random Forest becuase it can perform both regression and classification tasks.  Random Forest provides a higher level of accuracy in predicting outcomes and it produces good predictions that can be understood easily. 

