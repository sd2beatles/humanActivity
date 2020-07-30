![image](https://user-images.githubusercontent.com/53164959/88954047-c0eeda00-d2d4-11ea-9514-f4352d265a7c.png)


# 1. Introduction
humanActivity

Human Activity Recognition (HAR) using smartphones dataset and an LSTM RNN. Classifying the type of movement amongst six categories:

WALKING,
WALKING_UPSTAIRS,
WALKING_DOWNSTAIRS,
SITTING,
STANDING,
LAYING.
Compared to a classical approach, using a Recurrent Neural Networks (RNN) with Long Short-Term Memory cells (LSTMs) require no or almost no feature engineering. Data can be fed directly into the neural network who acts like a black box, modeling the problem correctly. Other research on the activity recognition dataset can use a big amount of feature engineering, which is rather a signal processing approach combined with classical data science techniques. The approach here is rather very simple in terms of how much was the data preprocessed.

Let's use Google's neat Deep Learning library, TensorFlow, demonstrating the usage of an LSTM, a type of Artificial Neural Network that can process sequential data / time series.

# 2. Problem Statemet

Given a new datapoint we have to predict the Activity

# 3. Methods

Models used: LSTM,Support Vector Machine,and  XG boost 
Grapical Visualizaiton: Tableau
Programming : Python(Version 3.7.0) and Jupyter Notebook


# 3. Test reutls 

Note that all the peformanace measures are based on F-1 scores. 

- Support Vector Machines: 96 % 

- LSTM: 92 %

- Xgboost : 94 %



