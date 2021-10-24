# Overview of Credit Risk  Analysis:
The purpose of this analysis is to analyze the cresit cared risk by employing different techniques to train and evaluate models with unbalanced classes. Data is oversampled using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, a combinatorial approachis used to over- and undersampling using the SMOTEENN algorithm. Next,  BalancedRandomForestClassifier and EasyEnsembleClassifier are used  to predict credit risk and then performance is evaluvated between these models.

## Results:

### Balanced RandomForest Classifier

* The balanced accuracy score is 0.9070037779715199 and the precesion and recall is 0.04 and 0.72 respectively.

### Easy Ensemble AdaBoost Classifier

* The balanced accuracy score is 0.8882460553872855 and the precesion and recall is 0.06 and 0.85 respectively.

### Naive Random Oversampling

* The balanced accuracy score is 0.6533977140416822 and the precesion and recall is 0.01 and 0.67 respectively.

### SMOTE Oversampling

* The balanced accuracy score is 0.6512291961274883 and the precesion and recall is 0.01 and 0.64 respectively.

### UndeSampling

* The balanced accuracy score is 0.5102725100821478 and the precesion and recall is 0.01 and 0.59 respectively.

### Combination Sampling

* The balanced accuracy score is 0.6375241226214794 and the precesion and recall is 0.01 and 0.70 respectively.


## Summary:
* From this analysis we can understand that the classifier algorithms Balanced RandomForest Classifier and Easy Ensemble AdaBoost Classifier have a greater balanced accuracy score than the other classifier algorithms.
* We can see that Combination Sampling yields a balanced results in all spectrums and their precision for high risk is 0.01 and recall is 0.70 
* UnderSampling is likely not to be preferred because the precsion and recall is comparitively less than the other algorithms.