# Neural_Network_Charity_Analysis
Using a Neural Network model to predict charity success

![](https://github.com/JonathanBrown003/Neural_Network_Charity_Analysis/blob/59e0652f8a49da85be175e751a2c478c6edbf8a7/Neural_Network.PNG)

## Overview 
The purpose of this neural network analysis was to predict success for applicants applying for charity grants. The neural network analyzed over 34,000 organizations to predict if the charity was likely to have success or not. The more favorable companies would have a better opportunity to receive funding from Alphabet Soup.

Please click ![here](https://github.com/JonathanBrown003/Neural_Network_Charity_Analysis/blob/eaf5f687235cf2f1c0e0eb4419431d7f0d64d848/AlphabetSoupCharity.ipynb) for the original code. 

Please click ![here](https://github.com/JonathanBrown003/Neural_Network_Charity_Analysis/blob/9242d327273c1e78dc8490be049a12f4c5645077/AlphabetSoupCharity_Optimization.ipynb) for the Optimization file. 

## Results
This model achieved an accuracy score of just a tad under 73%. I changed the activation functions and hidden layers numerous times to improve the score to no avail. Employee ID Number (EIN) and Name were removed from the initial dataset due to not being features nor targets. 

## Summary
The Optimization file achieved an accuracy score just above (72.92%) the original file (72.8%). Other activation functions could be run for the hidden layers including different combinations. Hidden layer numbers could also be increased to achieve better accuracy but at the cost of overfitting the model to this particular dataset. 
