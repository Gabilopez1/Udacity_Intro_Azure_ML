# Operationalizing Machine Learning

## Overview
This project is part of the Udacity Azure ML Nanodegree.
In this project, we build and optimize an Azure ML pipeline using the Python SDK and a provided Scikit-learn model.
This model is then compared to an Azure AutoML run.

## Architectural Diagram

This dataset contains data about the direct marketing campaigns (phone calls) of a Portuguese banking institution. The classification goal is to predict if the client will subscribe to a term deposit (variable y).
Creating the compute cluster
Training AutoML model
Deployment of the best model
..
Consuming the endpoint
..
and so on.



## Future work
**What are some areas of improvement for future experiments? Why might these improvements help the model?**

I would like to find out more about why the difference in accuracy between the Scikit Pipeline and AutoML was not larger. Could it be that to get a significant difference the dataset should be larger and more complex? Also, I read that AutoML is able the apply preprocessing transformation such as fix null on the training dataset, categorical encoding to convert features to numeric, and dropping high-cardinality features, this means that is possible that previous use on the fuction data_clean is not necessary for AutoML.


## Screencast video 
**If you did not delete your compute cluster in the code, please complete this section. Otherwise, delete this section.**
**Image of cluster marked for deletion**


## Screenshot Publish a ML Pipeline


![alt text](https://github.com/Gabilopez1/Optimizing_a_Pipeline_in_Azure/blob/master/clusterdeleting2.PNG)

