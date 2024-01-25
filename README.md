# deep-learning-challenge

## Overview

	The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. We have used machine learning and neural networks in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.
From Alphabet Soup’s business team, we have received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. 

## Data Preprocessing

1.	Read the csv file and drop the EIN and NAME columns from the data frame.

2.	Identify the number of unique values for each column.


3.	APPLICATION_TYPE and CLASSIFICATION column has more than 10 unique values. 

4.	Decide a cutoff point to bin "rare" categorical variables together in a new value, other and then check if the binning was successful.


5.	Use get_dummies() to encode the categorical values.

6.	Split the preprocessed data into a features array, x and a target array y. Use these arrays and the train_test_split function to split the data into training and testing datasets.


7.	Scale the training and testing features datasets by creating a standardscaler instance, fitting it to the training data, then using the transform function.

## Compile, Train, and Evaluate the Model

1.	Created neural network model by assigning the number of input features and nodes for each layer using TensorFlow and Keras.

2. Tried to increase the accuracy to 75% by increasing the hidden layers, number of neurons and changing activation method. I could achieve 72% which is lesser than the preffered accuracy.

3. Tried using Randam forest method for better accuracy. Still was able to achieve only 70 % accuracy.

4. May be by decreasing the cut off value and working more on pre processing will increase the accuracy.

## Key Artifacts and Solution
1. AlphabetSoupCharity_Initial
2. AlphabetSoupCharity_Optimization
3. Report on the Neural Network Model

