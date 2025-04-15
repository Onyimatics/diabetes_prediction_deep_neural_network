# diabetes_prediction_deep_neural_network
Deep Learning &amp; Optimisation – Prediction Task

## 1. Description
Deep learning is widely used to support medical diagnoses such as cancer prediction, diabetes prediction and X-ray categorisation. This challenge is designed to predict the possibility of having diabetes based on past medical records.
In this task, you are given a dataset that contains patient medical records of Pima Indians and whether they had an onset of diabetes within five years. More details about the dataset are described in the below section. Using these data, you need to build and optimise a neural network based on the concepts we covered during the sessions (or your own research on the covered topics) to predict the possibility of having diabetes.

## 2. Dataset
Within the data folder, there are 2 .csv files which are named “train.csv” and “test.csv”. The details of the attributes mentioned in both files are as follows.
- A1 - Number of times pregnant
- A2 - Plasma glucose concentration a 2 hours in an oral glucose tolerance test
- A3 - Diastolic blood pressure (mm Hg)
- A4 - Triceps skin fold thickness (mm)
- A5 - 2-Hour serum insulin (mu U/ml)
- A6 - Body mass index (weight in kg/(height in m)^2)
- A7 - Diabetes pedigree function
- A8 - Age (years)

train.csv
Training data to use with model training and validation.
Number of entries: 668
Columns:
- id - Unique Id assigned to each person in the training data set
- attributes - A1 – A8
- class - 0 or 1 (1= tested positive for diabetes)

test.csv
Testing data to use with predictions.
Number of entries: 100
Columns:
- id - Unique Id assigned to each person in the test data set
- attributes - A1 – A8