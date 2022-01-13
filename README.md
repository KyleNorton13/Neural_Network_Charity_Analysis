# Neural_Network_Charity_Analysis

## Overview

The purpose of this analysis was to design a nueral network in order to create a binary classification model that is able to predict if an organization backed by Alphabet Soup will be successful. In order to do this the data needed to be preprocessed a considerable amount which was accomplished in deliverable 1. After the preprocessing we evaluated our our models accuracy with two hidden layers. For deliverable 2 we needed to make adjustments in order to increase the optimization and accuracy of the model. 

## Results

### Data Preprocessing
- Targets - IS_Successful
- Features - All columns other than our target and the columns that were dropped which were EIN and Name
- Removed - EIN and NAME

### Compiling, Training, and Evaluating the Model
- Deliverable 1 - There were two hidden layers, one with 80 neurons and one with 30 neurons. The activation function was sigmoid.

![image](https://user-images.githubusercontent.com/87450415/149309431-c22f6e91-d95e-442c-b0b1-87a1beed830d.png)

- Deliverable 2 - There was one hidden layers with 80 neurons. The activation function was sigmoid.

![image](https://user-images.githubusercontent.com/87450415/149309705-02a3d0f5-5e5c-41b2-a352-da3f9ee7985b.png)


## Summary
Although I was not able to reach the target goal of 75% accuracy for the model I did improve upon the original by one percentage point. I had tried using anywhere from 1 -4 hidden layers and different activation models. The highest achieved accuracy I was able to obtain was with 1 hidden layer and continuing to use the sigmoid activation. I could have potentially worked with the preproccessing some more to make sure my model was scaled efficiently and all features were needed. 

