# deep-learning-challenge

In this Challenge, you will develop a deep learning tool that can be used in evaluating applicants for funding by using a dataset that contains information about  applications submitted over the years. Follow the instructions below to complete the assignment. 


Instructions: 

Create a new repository called deep-learning-challenge, clone the repository to your local directory. 

1. Preprocessing: 

- Read in the dataset, identify your target and features.
- Drop the EIN and NAME columns.
- Determine the number of unique values for each column and combine the columns with less than 10 unique values in a new value, Other and check if you have successfully replaced those valuesm, encode the categorical variables. 
- Split the preprocessed data first into a target and features array and then split the data into test and training datasets by using these arrays. 
- Scale the two datasets using an instance of a StandardScaler. Fit the instance to the training data. 

2. Compile, Train and Evaluate the Model 

- Create a neural network model by setting the number of nodes, input dimensions, number of hidden layers, an activation function for each layer, number of epochs and add an output layer to your model, check the structure of the model. Compile and train the model. Create a callback that save the model's weights every five epochs. Evaluate the model's accuracy and loss. Save the results to an Hdf5 file. 

3. Optimize the Model 

Create a new Google colab file, import your dependencies. Repeat the preprocessing steps used in Step 1.  

Optimize the model using tensor flow to achieve an accuracy higher than 75%. 

Configure the model to ensure no variables are causing confusion by changing the number of columns, creating more bins for rare occurrences in columns and adjusting the number of columns for each bin. 

Make adjustments to the model such as adding more neurons or more hidden layers, using different activation functions for the hidden layers or changing the number of epochs. 

4. Write a Report on the Neural Network Model 

Include the following sections in your report:

-The purpose of the analysis, target variables and features, variables removed from the analysis, number of neurons, layers and activation functions selected for the model, steps taken to improve performance. Explain whether you were able to achieve the target predictive performance. Summarize the results of your deep learning model. Include a recommendation for how a different model could solve this classification problem.


Source: 

https://bootcampspot.instructure.com







