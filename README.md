# Project 2: Operationalizing Machine Learning

## Overview
This project is part of the Udacity Azure ML Nanodegree.
In this project, I used  Azure to configure a cloud-based machine learning production model, after that the best model was  deploy it, and consume it. I also created, published, and consumes a pipeline.

## Architectural Diagram

I continued to work on the same the dataset of Project 1 about a direct marketing campaigns (phone calls) of a Portuguese banking institution. The classification goal is to predict if the client will subscribe to a term deposit (variable y). The Architectural Diagram is:
![alt text](https://github.com/Gabilopez1/Udacity_Intro_Azure_ML/blob/master/Minimalist%20Circles%20Mind%20Map.png)

## Screenshot Machine Learning Ops Principle
The key step of the Machine Learning Ops Principle are:


## Future work
**What are some areas of improvement for future experiments? Why might these improvements help the model?**

I think it will helpful to add more data to the model, this might improve the accuracy of the model. Also it could be interesting instead to tried  Azure Container Instance (ACI) to use Azure Kubernetes Service (AKS). Another thing that I noticed on the Data guardrails run by the Auto-ML, it detected imbalanced classes in the inputs, this can lead to a falsely perceived positive effect  of the model's accuracy because the input data has bias towards a class, this might represent a problem for the future and need to be fix it or at least reviewed.


## Screencast video 
**If you did not delete your compute cluster in the code, please complete this section. Otherwise, delete this section.**
**Image of cluster marked for deletion**


## Screenshot Publish a ML Pipeline



![alt text](https://github.com/Gabilopez1/Optimizing_a_Pipeline_in_Azure/blob/master/clusterdeleting2.PNG)

