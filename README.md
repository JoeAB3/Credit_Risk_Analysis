# Credit_Risk_Analysis

Overview
Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, we'll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, we'll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, we'll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once that's done, we'll evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

Deliverable #1
Naive Random Oversampling
<img width="625" alt="2021-12-05 (8)" src="https://user-images.githubusercontent.com/86638388/144780651-1b17e933-9a4b-46ea-8c8c-411f3caea9b9.png">


SMOTE Oversampling
<img width="646" alt="2021-12-05 (9)" src="https://user-images.githubusercontent.com/86638388/144781044-d3ada654-b0db-4033-bb2a-6bfbcb84aa8e.png">

Undersampling
<img width="629" alt="2021-12-05 (10)" src="https://user-images.githubusercontent.com/86638388/144781201-851da6da-a97b-4632-a9e7-fdaa568b401c.png">

Combination (Over and Under) Sampling
<img width="625" alt="2021-12-05 (11)" src="https://user-images.githubusercontent.com/86638388/144781347-96a5922b-e26f-43f8-812d-b8f66d0896e6.png">


Deliverable #2
SMOTEEN
<img width="602" alt="2021-12-05 (12)" src="https://user-images.githubusercontent.com/86638388/144781881-b01aeded-7ee2-40bf-aac9-732e6958d984.png">

Deliverable #3
Balanced Random Forest Classifier
<img width="663" alt="2021-12-05 (13)" src="https://user-images.githubusercontent.com/86638388/144783223-0929de42-351d-4095-aed1-37a435edfce8.png">
Easy Ensemble AdaBoost Classifier
<img width="691" alt="2021-12-05 (14)" src="https://user-images.githubusercontent.com/86638388/144783305-4ad80535-c05d-46a2-b853-0c56157e08d3.png">


Summary
In the first four models, the accuracy score is not as high as the ensemble scores. The mixed models have generally low accuracy scores as well. The best predictive models should have a fair mix of recall and precision accuracy. Therefore, I would recommend one of the 2 ensemble models. It appears that the Easy Ensemble AdaBoost Classifier has the most balanced mix of precision and recall accuracy scores and I would recommend that specific model to be used to assess credit risk in this example.
