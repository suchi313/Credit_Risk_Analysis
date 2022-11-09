# Credit Risk Analysis

## Overview 
The goal of this challenge is to be able to understand machine learning models to make preidctions based on data patterns provided. During the course of this challenge, we had to create a supervised machine learning model to predict credit card risk. 

## Resources 
- Dataset: LoanStats_2019Q1.csv
- Software: Python, JupyterNootebook, Numpy, Imbalanced-learn libraries, Logistic Regression, Random Forest Modes, Ensemble and Resampling Techniques.

## Challenge Deliverables
- Deliverable 1: Use Resampling Models to Predict Credit Risk
- Deliverable 2: Use the SMOTEENN algorithm to Predict Credit Risk
- Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk

## Results 

To decipher the results, you'll need to understand the following definitions:
1. Accuracy Score: Represents the fraction of predictions the model got right. 
2. Precision: (Also called positive predictive value) is the fraction of relevant instances among the retrieved instances
3. Recall (Sensitivity): the fraction of relevant instances that were retrieved. Both precision and recall are therefore based on relevance.

## Native Random Oversampling 
- Accuracy Score: 66.2%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall High Risk: 72%
- Recall Low Risk: 60%

![Balanced Accuracy Score - Naive Random Oversampling](https://user-images.githubusercontent.com/102767530/200698997-d01cae1c-9e1e-4fde-ae03-1051ba2d8ce9.png)

![Native Random Oversampling ](https://user-images.githubusercontent.com/102767530/200698376-7caf63a8-1918-4adc-b873-b973293b2454.png)

## SMOTE Oversampling
- Accuracy Score: 65.6%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall High Risk: 61%
- Recall Low Risk: 70%

![SMOTE Accuracy ](https://user-images.githubusercontent.com/102767530/200699385-9fcef3b4-653a-42e7-af40-aad6459d05d1.png)
![Confusion Matrix - SMOTE](https://user-images.githubusercontent.com/102767530/200699537-23b9ea00-e83b-4127-a28c-00800ebd7143.png)
![Classification Report - SMOTE](https://user-images.githubusercontent.com/102767530/200699616-3ab2411a-e68c-4ed9-b432-fed400ab92eb.png)

## ClusterCentroids Undersampling

I undersampled the data here using the Cluster Centroids algorithm. 

- Accuracy Score: 54.4%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall High Risk: 69%
- Recall Low Risk: 40%

![Cluster Accuracy Score](https://user-images.githubusercontent.com/102767530/200700411-0f389f48-27e8-44b0-aaa9-231f9b562db8.png)
![Cluster Classification Report](https://user-images.githubusercontent.com/102767530/200700547-42aa1e47-5fec-4057-bae4-27a643038588.png)
![Cluster Consuion Matrix](https://user-images.githubusercontent.com/102767530/200700557-d56964c4-1d11-464d-a75a-60883dcc604c.png)

## SMOTEENN Sampling

With SMOTEENN Sampling, I tested a combination over- and under-sampling algorithm to determine if the algorithm results in the best performance compared to the other sampling algorithms used above.

- Accuracy Score: 65.6%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall High Risk: 61%
- Recall Low Risk: 70%

![SMOTEENN Accuracy Score](https://user-images.githubusercontent.com/102767530/200701371-90223677-980a-4dca-a742-432f192f3510.png)
![SMOTEENN Classification Report](https://user-images.githubusercontent.com/102767530/200701375-bdfff74a-8cd9-4887-8eea-bf2fcd69cdee.png)
![SMOTEENN Sampling Consuion Matrix](https://user-images.githubusercontent.com/102767530/200701391-8a8f253f-338d-4646-adbc-691885c8c80a.png)

## Balanced Random Forest 

The Balanced Random Forest model helps to reduce bias by creating 2 trees of equal size for the majority and minority classes. 

- Accuracy Score: 91.7%
- Precision High Risk: 9%
- Precision Low Risk: 100%
- Recall High Risk: 89%
- Recall Low Risk: 94%

![Balanced Random Forest Accuracy Score](https://user-images.githubusercontent.com/102767530/200702076-09959cc2-704d-4e62-aaf4-24c304738ce0.png)
![Balanced Accuracy Score - Naive Random Oversampling](https://user-images.githubusercontent.com/102767530/200702088-578db043-9946-4547-b623-4963d066f0e8.png)

## EasyEnsemble 

The last model we used was the Easy Ensemble Classifer model. This model showcases new examples that are created and classifed by a set of individual decisions.

- Accuracy Score: 91.7%
- Precision High Risk: 9%
- Precision Low Risk: 100%
- Recall High Risk: 89%
- Recall Low Risk: 94%

![EasyEnsemble Accuracy Score](https://user-images.githubusercontent.com/102767530/200702482-95929ad4-1cca-42d6-9cad-dffc320de791.png)
![EasyEnsemble Classification Report](https://user-images.githubusercontent.com/102767530/200702495-b79df457-1376-4c09-80e6-73743953c8a5.png)

## Summary






