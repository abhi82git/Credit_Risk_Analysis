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
 
 ![Naive_BAS](https://github.com/abhi82git/Credit_Risk_Analysis/blob/738ab79ac442cd954cad1e05327d3b26ec80b09a/Images/Naive_BAS.png)
 ![Naive_CR](https://github.com/abhi82git/Credit_Risk_Analysis/blob/738ab79ac442cd954cad1e05327d3b26ec80b09a/Images/Naive_CR.png)

 
 ### SMOTE Oversampling
 - Balanced Accuracy Score: 0.62
 - Precision: 0.99
 - Recall: 0.64
 
 ![SMOTE_BAS](https://github.com/abhi82git/Credit_Risk_Analysis/blob/738ab79ac442cd954cad1e05327d3b26ec80b09a/Images/SMOTE_BAS.png)
 ![SMOTE_CR](https://github.com/abhi82git/Credit_Risk_Analysis/blob/738ab79ac442cd954cad1e05327d3b26ec80b09a/Images/SMOTE_CR.png)


 ### Cluster Centroid Undersampling
 - Balanced Accuracy Score: 0.53
 - Precision: 0.99
 - Recall: 0.45
 
 ![ClusterCentroid_BAS](https://github.com/abhi82git/Credit_Risk_Analysis/blob/738ab79ac442cd954cad1e05327d3b26ec80b09a/Images/ClusterCentroid_BAS.png)
 ![ClusterCentroid_CR](https://github.com/abhi82git/Credit_Risk_Analysis/blob/738ab79ac442cd954cad1e05327d3b26ec80b09a/Images/ClusterCentrooid_CR.png)

 
 ### SMOTEENN Combination Sampling 
 - Balanced Accuracy Score: 0.65
 - Precision: 0.99
 - Recall: 0.62
 
 ![SMOTEENN_BAS](https://github.com/abhi82git/Credit_Risk_Analysis/blob/738ab79ac442cd954cad1e05327d3b26ec80b09a/Images/SMOTEENN_BAS.png)
 ![SMOTEENN_CR](https://github.com/abhi82git/Credit_Risk_Analysis/blob/738ab79ac442cd954cad1e05327d3b26ec80b09a/Images/SMOTEENN_CR.png)

 
 ### Balanced Random Forest Classifier
 - Balanced Accuracy Score: 0.79
 - Precision: 0.99
 - Recall: 0.89
 
 ![BalancedRandomForecast_BAS](https://github.com/abhi82git/Credit_Risk_Analysis/blob/738ab79ac442cd954cad1e05327d3b26ec80b09a/Images/BalancedRandomForecast_BAS.png)
 ![BalancedRandomForecast_CR](https://github.com/abhi82git/Credit_Risk_Analysis/blob/738ab79ac442cd954cad1e05327d3b26ec80b09a/Images/BalancedRandomForecast_CR.png)

 
 ### Easy Ensemble AdaBoost Classifier
 - Balanced Accuracy Score: 0.93
 - Precision: 0.99
 - Recall: 0.94
 
 ![EasyEnsemble_BAS](https://github.com/abhi82git/Credit_Risk_Analysis/blob/738ab79ac442cd954cad1e05327d3b26ec80b09a/Images/EasyEnsemble_BAS.png)
 ![EasyEnsemble_CR](https://github.com/abhi82git/Credit_Risk_Analysis/blob/738ab79ac442cd954cad1e05327d3b26ec80b09a/Images/EasyEnsemble_CR.png)

 
## Summary

In the financial industry, sensitivity is more valuable than precision for analyzing risk and default rates on loan candidates because banks ned to identify all high-risk individuals as high-risk for them not to default.

In terms of precision, all six algorithms had a really low precision rate for high risk individuals. The highest one was the Easy Ensemble AdaBoost Classifier with 7% precision which is still considered pretty low. On the other hand, all the models had a perfect precision for low-risk individiauls meaning that all of the low-risk customers were marked as that. 

The aveage precision doesn't give the true picture due to this, and a a higher avaerage precision is due to the skew towards low risk precision.

As far as sensitivity is concerned, the model with the highest sensitivity was the Easy Ensemble adaboost classifier.

The accuracy score stands for how correct was the model, meaning out of all the predictions how many of them were true to the classification. As we were able to see, the model with the highest accuracy score by far was the Easy Ensemble AdaBoost Classifier. So, this should be the one we chose because of its high accuracy, highest precision, and highest sensitivity. 

