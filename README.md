# Neural_Network_Charity_Analysis

## Overview

AlphabetSoup is a non-profit philanthropic foundation dedicated to helping organizations that protect the environment, improve people’s well-being, and unify the world. The foundation already raised and donated over 10 billion dollars in the past 20 years. To help ensure that the money that is being donated is being used effectively, the company data analytics group was tasked to predict which organizations are worth donating to and which are too high risk.  

In this project developed and trained a deep learning neural network model to produce a clear decision-making result.

## Results 

### Deliverable 1: Preprocessing Data for a Neural Network Model

The following preprocessing steps have been performed:

•	The EIN and NAME columns have been dropped 

![deliv1-dropped_EIN_NAME.png](https://github.com/OPahunang/Neural_Network_Charity_Analysis/blob/main/Resources/deliv1-dropped_EIN_NAME.png)


•	The columns with more than 10 unique values have been grouped together 

![deliv1-2.png](https://github.com/OPahunang/Neural_Network_Charity_Analysis/blob/main/Resources/deliv1-2.png)


•	The categorical variables have been encoded using one-hot encoding 

![deliv1-3.png](https://github.com/OPahunang/Neural_Network_Charity_Analysis/blob/main/Resources/deliv1-3.png)


•	The preprocessed data is split into features and target arrays 
•	The preprocessed data is split into training and testing datasets 

![deliv1-4.png](https://github.com/OPahunang/Neural_Network_Charity_Analysis/blob/main/Resources/deliv1-4.png)


•	The numerical values have been standardized using the StandardScaler() module 

![deliv1-5.png](https://github.com/OPahunang/Neural_Network_Charity_Analysis/blob/main/Resources/deliv1-5.png)



### Deliverable 2: Compile, Train, and Evaluate the Model

The neural network model using Tensorflow Keras contains working code that performs the following steps:

•	The number of layers, the number of neurons per layer, and activation function are defined
•	An output layer with an activation function is created
•	There is an output for the structure of the model
•	There is an output of the model’s loss and accuracy
•	The model's weights are saved every 5 epochs
•	The results are saved to an HDF5 file

![deliv2-1.png](https://github.com/OPahunang/Neural_Network_Charity_Analysis/blob/main/Resources/deliv2-1.png)


![deliv2-2.png](https://github.com/OPahunang/Neural_Network_Charity_Analysis/blob/main/Resources/deliv2-2.png)



### Deliverable 3: Optimize the Model

The model is optimized, with combinations of the following

•	Added additonal neurons
•	Added hidden layers  
•	The results are saved to an HDF5 file 

#### Optimization First Attempt

Optimization by adding neurons at layer 2 from 30 to 80. From Accuracy 53% to 69%

![deliv3%20-%201st.png](https://github.com/OPahunang/Neural_Network_Charity_Analysis/blob/main/Resources/deliv3%20-%201st.png)


#### Optimization Second Attempt

![deliv3-2nd.png](https://github.com/OPahunang/Neural_Network_Charity_Analysis/blob/main/Resources/deliv3-2nd.png)


### Optimization Third Attempt


![]()



## Summary 
