# Charity Funding Predictor



## Background

Create a classifier for predicting if applicants will be successful if funded by a non-profit foundation using neural networks.



## Approach/Results

1. Preprocessed the dataset by dropping unnecessary columns and converting categorical data to numerical data.
   1. Kept all categorical and numerical data as features for model
   2. Removed identifier data: EIN and Name columns
   3. Used Is_successful column as a target
2. Used TensorFlow to design a neural network to create a classification model. 
3. Used 3 hidden layers using a 8, 3, 1 neuron strategy and trained the model for 10 epochs.
4. Used relu and sigmoid as activation functions because they are the most commonly used.
5. Compiled and trained model
   1. Achieved a 99% model performance on first attempt and did not pursue further optimization
6. Stored model as a .h5



## Summary

Model achieved a 99% performance and it works at classifying applicants.

