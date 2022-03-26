# Credit_Risk_Analysis
Deploy supervised machine learning models to predict credit risk using Python's imbalanced-learn and scikit-learn libraries

## Overview of the analysis
The objective of this project was to use machine learning models to analyze credit risk to provide a quicker and more reliable loan experience.

## Results
The results for all six machine learning algorithms are listed belows:

 ### Naive Random Oversampling
 - Balanced Accuracy Score: 0.68
 - Precision: 0.99
 - Recall: 0.68
 
 ### SMOTE Oversampling
 - Balanced Accuracy Score: 0.62
 - Precision: 0.99
 - Recall: 0.64
 
 ### Cluster Centroid Undersampling
 - Balanced Accuracy Score: 0.53
 - Precision: 0.99
 - Recall: 0.45
 
 ### SMOTEENN Combination Sampling 
 - Balanced Accuracy Score: 0.65
 - Precision: 0.99
 - Recall: 0.62
 
 ### Balanced Random Forest Classifier
 - Balanced Accuracy Score: 0.79
 - Precision: 0.99
 - Recall: 0.89
 
 ### Easy Ensemble AdaBoost Classifier
 - Balanced Accuracy Score: 0.93
 - Precision: 0.99
 - Recall: 0.94
 
## Summary

In the financial industry, sensitivity is more valuable than precision for analyzing risk and default rates on loan candidates. This because banks want to be able to mark all of the high-risk individuals as high-risk for them not to default. It doesn't matter if it is not as precise as long as the posible defaults are marked as that. 

In terms of precision, all six algorithms had a really low precision rate for high risk individuals. The highest one was the Easy Ensemble AdaBoost Classifier with 7% precision which is still considered pretty low for finding these high risk individuals not to give loans to. This means that out of all the customers marked as high-risk 7% were actually high-risk. On the other hand, all the models had a perfect precision for low-risk individiauls meaning that all of the low-risk customers were marked as that. 

Having this in mind, precision is not telling us much information to compare the algorithms, so we should take a look at sensitivity. The model with the highest sensitivity was the easy ensemble adaboost classifier (91% for high-risk and 94% for low-risk individuals), meaning that 91% of the time all the high-risk individuals are marked as high-risk individuals. Followed by this model, the other two with high recall were the Random Forest Classifier (67%) and SMOTEENN Resample (70%). 

And last but not least, we are going to look at the balanced accuracy score to make the final decision of which model to use. The accuracy score stands for how correct was the model, meaning out of all the predictions how many of them were true to the classification. As we were able to see, the model with the highest accuracy score by far was the Easy Ensemble AdaBoost Classifier. So, this should be the one we chose because of its high accuracy, highest precision, and highest sensitivity. 

