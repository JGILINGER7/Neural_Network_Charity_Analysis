# Neural Network Charitable Giving Risk Analysis

## Goal
The goal of this project is training a neural network to assses whether or not a charity will be succesful with a donation. To this end we used Pandas, sklearn, and tensorflow to organize and asses the data. 

## Results
    *IS_SUCCESFUL was our target for the model it offered a binary recording of success or failure. 
    *All other variables, with the removal of EIN and NAME which were removed as their data is irrelevant to our model, were our features. 
    *I went with three layers at 80 ,50, and 20 neurons respectively, with the large ammount of data it seemed necessary to run a multiple higher than the 8 standard starting neurons for a test model. Seeing a low accuracy on the first run I added an additional hidden layer of 50. I started out with ReLU because of its simplifying output and used sigmoid for the output layer as results should be 0 or 1. 
    * Although I came relatively close to the target performance, getting above 74% I was not able to reach the 75% target.
    * to increase model performance I changed neuron density, attempted dropping the classification column and changing activation functions.

## Summary
    I was nto able to create a viable model although I feel like the work is on the right track. To further explore a better model I believe a more thorough data clean up, removing null values, checking for outliers, and analyzing for other possible tweaks to the data would allow for a more accurate model by reducing noise and the kind of discrepancies that make a model harder to accurately train. 