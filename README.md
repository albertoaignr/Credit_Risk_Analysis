# Credit Risk Analysis

Machine Learning algorithms can help develop solutions for real world challenges. Credit risk is a type of problem which data is unbalanced, as there is a good amount of low risk loans that outnumber where the risk factor is high. For this analysis, various machine learning approach were used to work with the data, using re/over/under-sampling and different modeling techniques to compare overall performance. 

## Results 

Overall performance will be determined on the values of balanced accuracy, "defined as the average of recall obtained on each class"<sup>1</sup>, precision and recall (often referred as sensitivity) of the results.

- Random sampler: 0.67
![M18_Random_Oversampling_D1.png](M18_Random_Oversampling_D1.png)
- SMOTE sampler: 0.66
![M18_SMOTE_Oversampling_D1.png](M18_SMOTE_Oversampling_D1.png)
- Cluster Centroids: 0.54
![M18_ClusterCentroids_Undersampling_D1.png](M18_ClusterCentroids_Undersampling_D1.png)
- SMOTEENN: 0.63
![M18_SMOTEENN_D2.png](M18_SMOTEENN_D2.png)
- RandomForest: 0.79
![M18_BalancedRandomForest_D3.png](M18_BalancedRandomForest_D3.png)
- EasyEnsemble: 0.93
![M18_EasyEnsemble_D3.png](M18_EasyEnsemble_D3.png)


## Summary 

- summary of results 
- Recomendation of which model to use or not 


1- [https://scikit-learn.org/stable/modules/generated/sklearn.metrics.balanced_accuracy_score.html](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.balanced_accuracy_score.html)
