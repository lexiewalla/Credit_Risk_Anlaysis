# Credit_Risk_Anlaysis
Module 17 Challenge - Supervised Learning


## Overview 

In this challenge we used unsupervised machine learning techniques to determine applicants credit risk for loan approval. We used several python libraries to build an algorithm to predict if these applicants are a risk or not. Some of the libraries we used were SMOTE, SMOTTEEN, ClusterCentroids, BlanacedRandomForestClassifier and EasyEnsembleClassifier.

## Results

### Random Over Sampling

The first model used was Random Over Sampling. With this model we found that the balanced accuracy score was about 63% with high precision at 1% and sensitivity at 58%.

<img width="303" alt="randomoversample1" src="https://user-images.githubusercontent.com/45208773/146648602-dd7d72d2-f327-4fa6-9edf-b4d00ec2065d.PNG">
<img width="499" alt="ros2" src="https://user-images.githubusercontent.com/45208773/146648637-b81af448-32f3-4f69-83c8-1a9328ee920b.PNG">

### SMOTE

The second model we used is the SMOTE model. The results came out very similar to the random over sampling with the balanced accuracy score at 63% and high precision at 1% and sensitivity at 62%. 

<img width="499" alt="ros2" src="https://user-images.githubusercontent.com/45208773/146648853-8d373822-c7de-401c-b669-e9075c17f783.PNG">
<img width="522" alt="smote2" src="https://user-images.githubusercontent.com/45208773/146648861-f194b1fc-2ef2-4ff5-84fc-711e243abfd0.PNG">

### Undersampling/ClusterCentroid

The third model used was undersampling with ClusterCentroid. In these results we saw that the balanced accruacy was 52%, high risk precision was 1% and sensitivity was 63%.

<img width="680" alt="undersampling" src="https://user-images.githubusercontent.com/45208773/146648988-3f38d533-19a7-413a-9194-13d5d821c496.PNG">

### Combination/SMOTEENN

In this model we used the SMOTEENN model. We found that the balanced accruacy was 62% with high risk precision at 1% and senistivity at 70%.

<img width="675" alt="smoteenn" src="https://user-images.githubusercontent.com/45208773/146649053-36d32e44-1811-4a88-a091-74998fc5c6a6.PNG">

### Balanced Random Forest Classifier

In the balanced random forest classifier the results showed a balanced accuracy score of 78% with a high risk precision at 4% and sensitivity at 67%.

<img width="676" alt="BRFC" src="https://user-images.githubusercontent.com/45208773/146649116-73beb770-48dd-420f-b877-713777ae8bff.PNG">

### Easy Ensemble AdaBoost Classifier

In the easy ensemble method we found that the balanced accruacy score was 93% with a high risk precision at 7% and sensitivity of 91%.

<img width="694" alt="eec" src="https://user-images.githubusercontent.com/45208773/146649198-24370a6d-2dca-40e8-b74d-4aacbfc6fdf1.PNG">

## Summary

It appears that our results are all over the board using all of these models. The easy ensemble method shows the highest sensitivity percentage telling us that almost all applicants are a risk. The models that predicted similar results are the models that I would recommend sticking too. In this case the easy ensemble classifier and the balanced forest classifier would be our best bet because of the high risk precision numbers and the sensitivities. 
