# Intro to Machine Learning Project 1

CSE 474/574: Introduction to Machine Learning 
(Fall 2019) 

Sargur N. Srihari 
University at Bufalo,

The State University of New York 
Bufalo, New York 14260

September 9, 2019 

1	Task 

The task of this project is to perform classification using machine learning. It is for a two class problem. The features used for classification are pre-computed from images of a fine needle aspirate (FNA) of a breast mass. Your task is to classify suspected FNA cells to Benign (class 0) or Malignant (class 1) using logistic regression as the classifier. The dataset in use is the Wisconsin Diagnostic Breast Cancer (wdbc.dataset). The code should be written in Python from scratch. Deadline to submit the code and the report on timberlake server is September 25, 2019. 

2	Dataset 

Wisconsin Diagnostic Breast Cancer (WDBC) dataset will be used for training, validation and testing. The dataset contains 569 instances with 32 attributes (ID, diagnosis (B/M), 30 real-valued input features). Features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass.

3	Plan of Work 

1. Extract features values and Image Ids from the data: Process the original CSV data files 
into a Numpy matrix or Pandas Dataframe. 

2. Data Partitioning: Partition your data into training, validation and testing data. Randomly 
choose 80% of the data for training and the rest for validation and testing. 

3. Train using Logistic Regression: Use Gradient Descent for logistic regression to train the 
model using a group of hyperparameters. 

4. Tune hyper-parameters: Validate the regression performance of your model on the validation 
set. Change your hyper-parameters. Try to find what values those hyper-parameters should take so as to give better performance on the validation set. 

5. Test your machine learning scheme on the testing set: After finishing all the above 
steps, fix your hyper-parameters and model parameter and test your models performance on the testing set. This shows the ultimate efectiveness of your models generalization power gained by learning.
