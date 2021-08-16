

# Neural Network Charity Analysis


## Overview of the analysis

Using machine learning model and neural networks, we created a binary classifier that will tell the customer whether or not the applicants will be successful using alphabet soup. In order to accomplish this, we Preprocessed the data for the neural network, compiled, trained and evaluated the model, then optimized the model to attempt to reach an accuracy score of at least 75%.

## Results

#### Data Preprocessing:

+  What variable(s) are considered the target(s) for your model?

	-   The variable we are targeting in this module is the IS_SUCCESSFUL variable.

-   What variable(s) are considered to be the features for your model?

	-   The features are every column except the ones that were dropped.

-   What variable(s) are neither targets nor features, and should be removed from the input data?

	-   First variables we drop are the 'EIN' & 'NAME' because we expect both variables to not effect the outcome of the analysis. 

#### Compiling, Training, and Evaluating the Model:

-   How many neurons, layers, and activation functions did you select for your neural network model, and why?

	-   This model is made with an input feature & two hidden layers. The first hidden layer has 80 neurons, while the second hidden layer has 30. In addition, there is an output layer. Each layer has an activation function. The first and second hidden layers have an activation function "relu" & the output layer is "sigmoid".



-   Were you able to achieve the target model performance?

	-   The target model performance was 75%, and the model did not achieve this performance level. Instead, the model reached 72.7% accuracy. 

![1](https://user-images.githubusercontent.com/79758494/129499475-47da3639-87d6-4db2-ace3-7b007ba0e694.PNG)

-   What steps did you take to try and increase model performance?

	-   There were a number of ways we attempted to increase model performance. To attempt to do this, we added hidden layers, changed the number of epochs and neurons in each layer, and changed the activation type. 
	- Three attempts were made to increase the model performance. Below are the results of those three attempts: 
	
![O -1](https://user-images.githubusercontent.com/79758494/129499479-22878f96-02bb-4f7a-b850-49fb19b6d020.PNG)
![O - 2](https://user-images.githubusercontent.com/79758494/129499482-0d171fef-ea3f-428f-87f1-dd3eea3677b1.PNG)
![O -3](https://user-images.githubusercontent.com/79758494/129499489-b9aae026-bb06-4b13-9cf3-6d963cf3e084.PNG)


## Summary

Even after optimization, the models accuracy ended up being 72.7%. The analysis began with a data set and we tried to predict whether or not the analysis would be successful on all of the features that we used after dropping two variables that we concluded would not affect the overall analysis. The accuracy of 75% was not achieved in the end, one reason for this could be that there may be more variables that need to be dropped that are not relevant to the analysis but are affecting the overall accuracy levels. One way to work towards optimizing the neural network model and increasing accuracy levels is to be working with a larger dataset. As mentioned above, another way to increase accuracy is to ensure that the data is clean and concise. 
