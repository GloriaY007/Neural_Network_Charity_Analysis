# Neural Network Charity Analysis

This project aims to analyze the impact of each donation, vet potential recipents, and help ensure that AlphabetSoup's money is being used effectively, using Python TensorFlow library and Neural networks.

## Overview of the analysis
Our main tasks for this analysis were to:
- Predict which organizations are worth donating to and which were high risk 
- Create a mathematical driven solution to design and train a deep learning neural network
- Create a model that would evaluate all kinds of input data and produce a clear decision making result

## Results
Using bulleted lists and images to support your answers, address the following questions.

### Data Preprocessing
The targets of our model were the folowing:

![Targets of our model](https://github.com/GloriaY007/Neural_Network_Charity_Analysis/blob/main/Screenshots/Targets%20of%20Model.png)

The features of our model were the following:

![Features of our model](https://github.com/GloriaY007/Neural_Network_Charity_Analysis/blob/main/Screenshots/Features%20of%20Model.png)

These variables were neither targets nor features, and were removed from the input data:

![Neither targets nor features](https://github.com/GloriaY007/Neural_Network_Charity_Analysis/blob/main/Screenshots/Non-target%20or%20features%20of%20Model.png)

## Compiling, Training, and Evaluating the Model

In [AlphabetSoupCharity.ipynb](https://github.com/GloriaY007/Neural_Network_Charity_Analysis/blob/main/Challenge/AlphabetSoupCharity.ipynb), the model accuracy was 72.69%, which is not quite a good enough performance score for making predictions.
To increase model performance in [AlphabetSoupCharity_Optimization.ipynb](https://github.com/GloriaY007/Neural_Network_Charity_Analysis/blob/main/Challenge/AlphabetSoupCharity_Optimzation.ipynb), we added one additional hidden layers and additional neurons to the hidden layers and ended up with almost the same exact accuracy score with 72.70%.

## Summary

The model was able to correctly identify which organization to donate to approximately ***72%*** of the time. Considering that our input data included more than 100 different variables with significant data points, the deep learning model was able to produce a somewhat reliable classifier.

The initial deep learning models used here, and the optimized version, both achieved a predictive accuracy around ***72%***. Additionally, both iteration of the model took similar amounts of time to train on the input data. 

We could try next, the SVM, or the random forest model. The amount of code required to build and train the SVM is typically less than the comparable deep learning model, and the random forest model is able to achieve comparable predictive accuracy, as the deep learning model, on large tabular data with less code and faster performance.




