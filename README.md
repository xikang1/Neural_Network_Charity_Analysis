# Neural_Network_Charity_Analysis

## Overview
For this project, we are analyzing the dataset from Alphabet Soup’s business team and predict if the organizations would use the funding received from Alphabet Soup effectively with applicatioin of nerual network models.We are going to preprocess the dataset, complile and train the neural network models we built, and make adjustments based on the evaluation of the model performance.

## Results
Data Preprocessing:
* We have considered IS_SUCCESSFUL column as the target which tell us directly about if the organizations have used the money they received effectively
* We have considered all columns as the features expect the IS_SUCCESSFUL,EIN and NAME.
* EIN and NAME would not be either targets nor features. They are irrelevant data and should not to be used for training the model.

Compiling, Training, and Evaluating the Model
* I have 100neurons,80 neurons and 30 neurons for my three hidden layers, and usded relu acitvation function for hidden layers and sigmoid activation function for the output layer since this neural network model has the accuracy score of 0.60 which is the highest among my models
* Sorry I did not achieve the target model performance. However, I have tried randomforest algorithm and I have got the accracy about 71%!
* I have adjusted the traning data in the step of preprocessing. And I also added more hidden layers with more neurons for each of the hidden layers. I have tried to use different actication functions but it does not affect the performance that much.


## Summary
Overall, the final result of my deep learning model has the accracy of only about 60% which is not good at all.I have attempted a couple times and adjusted the model parameters but they did not work out as I expected. In addtion, I have tried to use RandomForest and i have increased the accuracy score up to about 71%. Since we are not having too much data, and this is a typical dataset with labeled data. In this case the RandowmForest works better that the deep learning model I designed. As it mentioned in the module, we should try different algorithms to figure out which one is the best under certain circumstances.

