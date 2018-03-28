# decisiontrees-randomforest-boostedmodel
Using Exploratory Data Analysis, Decision Trees, Random Forest and Boosted Model to analyze applicants w.r.t their credit risk.

## Background
The German Credit dataset has data on 1000 past credit applicants, described by 30 variables. Each applicant is also rated as “Good” or “Bad” credit (encoded as 1 and 0 respectively in the Response variable). New applicants for credit can be evaluated on these 30 variables. A credit scoring rule has been developed that can be used to help determine whether a new applicant presents a good or bad credit risk. A decision tree based model is used to determine if new applicants present a good or bad credit risk.

## Topic 1
Exploratory Data Analysis to understand which variables will be most relevant for modeling RESPONSE (dependent variable).

## Topic 2
Build a prediction model.
Data partitioned into 50% for Training and Test.
Build Decision Trees using rpart package. Use performance measures, ROC, AUC and lift chart.
Experiment with different parameters to understand their impact on performance.
Understand how to prune trees.
Build trees using C5.0 package. Use performance measures, ROC, AUC and lift chart.
Data partitioned using different split ratios (60-40, 70-30 etc.) to understand performance.

## Topic 3
Use misclassification costs to develop tree models (rpart and C5.0). Compare model performance.
Use ROC curve to choose a classification threshold. 

## Topic 4
Examine best decision tree model in terms of tree depth, nodes, performance etc.

## Topic 5
The predicted probabilities can be used to determine how the model may be implemented. The validation data is first sorted from high to low
on predicted probability of 'good' credit risk. When  going down the cases from high to low probabilities, the appropriate cutoff probability can be determined and values above this can be considered acceptable credit risk. Hence, in using this model to score future credit applicants, a cutoff value for predicted probability is determined.

## Topic 6
Random Forest and Boosted Tree model is developed and performance comparison using ROC, AUC and other performance measures is performed.
