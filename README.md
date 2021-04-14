# _You're APPROVED!_ || Fast Lending Analysis

## Overview of Study

Fast Lending, a peer-to-peer lending service company, is seeking a more efficient way to predict credit risk, primarily through Machine Learning. Additionally, on the front-end, the hope is to create and offer a better loan experience, overall, to loan applicants based on swiftness and reliability. 

To accomplish this task, a study of a 2019 credit dataset from peer-to-peer lending service company, LendingClub, was analyzed in a series of models to train and evaluate various techniques on the unbalanced classes of which loans are good opposed to which poses risk. 


## Resources 

* Data Source(s): [LoanStats_2019Q1.zip](https://app.box.com/s/69jvd0bg84y78fj6vw338ktbd5mqouiw) 
* Software/Tools: Python | Python Libraries/Packages: SciKit-Learn, Imbalanced-learn | VS Code 1.54.3 | Jupyter Notebook** | Anaconda (MLEV)
  *  Data Access: Workaround, [Project Jupyter: jupyter nbviewer](https://nbviewer.jupyter.org/), a Jupyter Notebook renderer **
     *    Data may not display properly on GitHub, please use provided workaround


## Results
The following algorithms: *Naïve Random Oversampling (RandomOverSampler)* , _SMOTE Oversampling_ ,  _Undersampling with ClusterCentroids_, _SMOTEEN (combination of over and undersampling)_, and _Ensemble Learners: Easy Ensemble Classifier and Random Forest Classifier_ were used to predict high credit risk. 

The below chart showcases the  balanced accruary score, precision, and  recall(sensitivity) of the former models tested. The visual acoompanient, full classification report can be viewed by clicking through each model's title column. 

| |[Naive Random Oversampling](images/naive_random_sampling.png) | [SMOTE Oversampling](images/smote_oversampling.png) |  [ClusterCentroids (Undersampling)](images/clustercentriod_undersampling.png) | [SMOTEEN](images/smoteen_over_undersampling.png) |[Random Forest Classifier (Ensemble Learners)](images/ensemble_random_forest_classifier.png) |[Easy Ensemble Classifier (Ensemble Learners)](images/ensemble_easy_ensemble_adaboost_classifier.png)
| --------------- | --------------- | ------------ |-------------|--------|----------|------------|
|Balanced Accuracy Score | 0.6503524738582371| 0.6621602612787003 | 0.5442661782548694 | 0.644711676499736| 0.7885466545953005 | 0.9316600714093861|
| Precision | 0.01 |  0.01 | 0.01      | 0.01| 0.01      | 0.09|
| Recall| 0.69 | 0.63      | 0.69      | 0.72      | 0.70      | 0.92| 

## Summary

#### Author 

_Whitney D. Gardner_



[Random Forest Classifier (Ensemble Learners)]()


#             
<p align="center"> <b><i>Linear Regression Model Results</b></i> 
 </p>
<p align="center">
 <img align="center" src="images/summary_p-value_r_squared_value_D1.png">
 </p>

## Summary Statistics on Suspension
. 

<p align="center"> <i><b>place holder</b></i>
 </p>
<p align="center">
 <img align="center" src="images/total_summary_PSI.png">
 </p>

  


<p align="center"> <i><b>place holder)</b></i> 
 </p>
<p align="center"> 
 <img align="center" src="images/lot_summaryPSI.png">
 </p>