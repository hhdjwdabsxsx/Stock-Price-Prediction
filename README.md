# Stock-Price-Prediction

## Importing Libraries and Dataset

1. Python libraries make it very easy for us to handle the data and perform typical and complex tasks with a single line of code.

2. Pandas: This library helps to load the data frame in a 2D array format and has multiple functions to perform analysis tasks in one go.

3.  Numpy: Nump arrays are very fast and can perform large computations in a very short time

4. Matplotlib/Seaborn: This library is used to draw visualizations.

5. TensorFlow: This is an opensource library that is used for Machine Learning and Artificial Intelligence and provides a range of functions to achieve complex functionalities with single lines of code.

# Exploratory Data Analysis

It is a technique that is used to analyze the data through visualization and manipulation. For this project let us visualize the data of famous companies such as Nvidia, Google, Apple, Facebook and so on.

First let us consider a few companies and visualize the distribution of open and closed Stock prices through 5 years.

![download (12)](https://github.com/user-attachments/assets/7dcbf69a-ae1e-4337-9dfd-2632cb77bc68)

Now, let's plot the volume of trade for these 9 stocks as well as a function of time.

![download (13)](https://github.com/user-attachments/assets/3d3c2b72-e22e-4736-a9e9-2ebe63859f85)

Now let's analyze the data for Apple Stocks from 2013 to 2018

![download (14)](https://github.com/user-attachments/assets/5cbba8bc-49a5-4e8e-a955-d98158b4ffe7)

# Build Gated RNN-LSTM network using TensorFlow

Using TensorFlow, we can easily create LSTM-gated RNN cells. LSTM is used in Recurrent Neural Networks for sequence models and time series data. LSTM is used to avoid the vanishing gradient issue which is widely occurred in training RNN. To stack multiple LSTM in TensorFlow it is mandatory tp use return_sequences = True. Since our data is time series varying we apply no activation to the output layer and it remains as 1 node.

# Model Compilation and Training

While compiling a model we provide these three essential parameters:

1. optimizer: This is the method that helps to optimize the cost function by using gradient descent

2. loss: The loss function by which we monitor whether the model is imrpoving with raining or not

3. metrics: This helps to evaluate the model by predicting the training and the validation data

   ![Screenshot 2024-12-04 211357](https://github.com/user-attachments/assets/e9343145-31f2-4122-ae6e-4f0a740e3f64)

   Now that we have predicted the testing data, let us visualize the dinal results.

   ![download](https://github.com/user-attachments/assets/168a51df-2500-48ba-b0ba-b638093ddfcd)





