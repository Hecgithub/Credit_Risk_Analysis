# Credit_Risk_Analysis

## Overview of the analysis: 
Explain the purpose of this analysis.
The analysis aims to use machine learning models that reduce bias to predict credit risk. The data used for this analysis comes from LendingClub, a peer-to-peer lending services company. The machine learning models will help predict if a person is a low or high credit risk status. The sampling techniques used for this analysis will be Random Over Sampler, SMOTE algorithms, and under-sampling using the Cluster Centroids algorithm. A combination approach of over and under-sampling using SMOTEENN algorithms will also be conducted. The two machine learning models used in the analysis will be the Balanced Random Forest Classifier and Easy Ensemble Classifier. 

## Results: 
The results for the six machine learning models, including their respective balanced accuracy, precision, and recall scores, are as follows:

### Naïve Random Oversampling

	The Balanced accuracy is 0.64%

	The Precision for high risk was 0.01, and low risk was 1

	The recall score for high risk is 0.69, and the low risk is 0.59

 ![image](https://user-images.githubusercontent.com/110510718/205747422-e8ee4543-a094-4fb4-bc58-e220bfbb1edd.png)

### SMOTE Oversampling 

	The Balanced accuracy is 0.66%

	The Precision for high risk was 0.01, and low risk was 1

	The recall score for high risk is 0.63, and the low risk is 0.69

 ![image](https://user-images.githubusercontent.com/110510718/205747457-eddec70a-82c0-476d-9134-bfea499fa315.png)

### Under sampling

	The Balanced accuracy is 0.66%

	The Precision for high risk was 0.01, and low risk was 1

	The recall score for high risk is 0.69, and the low risk is 0.40

![image](https://user-images.githubusercontent.com/110510718/205747496-a5094fc1-ee3e-4cf6-bc1a-59a0f95066c6.png)


### Combination (Over and Under) Sampling 

	The Balanced accuracy is 0.54%

	The Precision for high risk was 0.01, and low risk was 1

	The recall score for high risk is 0.72, and the low risk is 0.57

![image](https://user-images.githubusercontent.com/110510718/205747538-5c584207-6ea7-43da-ac15-ed551fdb3d9b.png)

### Balanced Random Forest Classifier

	The Balanced accuracy is 0.79%

	The Precision for high risk was 0.04, and low risk was 1

	The recall score for high risk is 0.71, and the low risk is 0.89

![image](https://user-images.githubusercontent.com/110510718/205747570-e14a82bc-01ad-4bc4-8f18-702c32036225.png)

 
### Easy Ensemble AdaBoost Classifier 

	The Balanced accuracy is 91%

	The Precision for high risk was 0.09, and low risk was 1

	The recall score for high risk is 0.89, and the low risk is 0.94

 ![image](https://user-images.githubusercontent.com/110510718/205747604-d6867b96-50f3-4eed-939f-7c66a7cd2f33.png)


## Summary: 
From all the machine learning models, the best results came from the Easy Ensemble AdaBoost Classifier. This model had the highest scores all around versus the other models.  In hindsight, all the models did poorly in predicting high credit risk. This could have been because the “High Risk” category was not fairly represented in the data. The machine learning algorithms are creating clusters drawing from too small of a dataset of actual “High Risk” applicants.  
