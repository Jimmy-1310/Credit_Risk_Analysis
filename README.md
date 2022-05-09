# Credit_Risk_Analysis

## Overview

Banking institutions have the service of lending money to customers and gaining money with interests when they pay back the loan. But the question must be asked, to who should banks and financial institutions lend money? Because they gain money when the customer pays back, they need to make sure the customer is paying back. For this, they categorize every customer that applies for a loan with a "high risk" or "low risk" depending on their information. Going application by application might take a lot of time, instead this process can be done with machine learning algorithms. For this project we tested 6 different machine learning models to see how they categorize and predict new applications.

For this project I learned to use 6 different machine learning models and how to prepare the data to use them.

### Results

Each model was given and trained with the same data. After this, predictions were made with a training data-set to then check the efficiency of the model. For each model we have its efficiency, confussion matrix, and imbalance report.

- Random Over Sampling (65.16%)

![ROS](https://user-images.githubusercontent.com/95836718/167331746-b9d4f6e8-f8b4-40c0-8ec0-ca611abc9aee.png)

*Precision:* 0.0009
*Sensitivity:* 0.62

- SMOTE (62.42%)

![SMOTE](https://user-images.githubusercontent.com/95836718/167331799-5b323efa-a48e-453a-a205-aad6df96a032.png)

*Precision:* 0.0008
*Sensitivity:* 0.586

- Cluster Centroids (51.60%)

![CC](https://user-images.githubusercontent.com/95836718/167331841-1a8b053f-b17e-4264-a2cb-8175fe836358.png)

*Precision:* 0.0005
*Sensitivity:* 0.597

- SMOTEEN (63.85%)

![SMOTEEN](https://user-images.githubusercontent.com/95836718/167331883-64f7e44d-efa3-46f6-9061-b2d0e9c14160.png)

*Precision:* 0.0008
*Sensitivity:* 0.70

- Balanced Randon Forest Classifier (78.85%)

![BRFC](https://user-images.githubusercontent.com/95836718/167331981-659c30b5-1e29-4c78-ad4c-74e1558357d9.png)

*Precision:* 0.032
*Sensitivity:* 0.70

- Easy Ensambler Classifier (93.17%)

![EEC](https://user-images.githubusercontent.com/95836718/167332039-f4dc725e-7f4c-4a1d-86f3-04e4e0ddd70c.png)

*Precision:* 0.086
*Sensitivity:* 0.92

## Summary

The first 5 models have a similar outcome and similar accuracy that is around 50% to 70%. The obvious stand out is the Easy Ensambles Classifier is the obvious stand out with a 93.17% accuracy and a 92% sensitivy, which means we are catching most of the high risk loans. This model is the obvious recomendation, but it still might require to really check if the high risk loans are really high risk, or they are just flaws in the model.
