# SUV-Purchase-Prediction



In this notebook, we perform three major tasks:

### Data Preparation
Acquire the dataset from here and import the neccessary libraries to use

### Data Exploration
Explore the dataset and make some data transformation and data visualization

### Data Modeling (Train & Test)
Model the dataset with multiple machine learning models


## About the Dataset
The dataset provides information regarding the age ,gender and Estimated Salary. There is one more column in dataset which is our target variable i.e Purchased.
We are going to apply multiple machine learning models and compare their accuracies.
I have downloaded above dataset from kaggle which you can download from "[here]" "(kaggle kernels output aimanabdollah/suv-purchase-prediction -p /path/to/dest)".

### Let’s Get Started
First we will import the libraries which we are going to use in this model.


The dataset comprises of 5 columns:

1.User ID

2.Gender

3.Age

4.Estimated Salary

5.Purchased


The value '0' means that the person has not purchased the car and '1' means that the person has purchased a car.



The dataset does not contain any null values.


We will split our model into 20% testing and 80 % for training model.

We built multiple machine learning models followed by classification report and confusion matrix.
