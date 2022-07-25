# Diabetes_Prediction_Ensemble_Classifiers

Problem: The aim is to predict whether the patient is having diabetes or not based on the diagnostic measurements.

Data Source: Dataset is originally from National Institute of Diabetes and Digestive and Kidney Diseases. It is available on kaggle.com

Features	                             Data Type	Relevance
Number of times pregnant		          Continuous	Relevant
Plasma glucose concentration	      	Continuous	Relevant
Diastolic blood pressure		          Continuous	Relevant
Triceps skin fold thickness		        Continuous	Relevant
2-Hour serum insulin		              continuous	Relevant
Body mass index	                   	Continuous	Relevant
Diabetes pedigree function		      Continuous	Relevant
Age (years)		                      Continuous	Relevant
Class variable		                  Categorical	Relevant


#Ensemble Learning Algorithms
Ensemble machine learning is an approach that combine the predictions from different models to provide better predictive performance. 

The most popular type of ensemble learning classifier are
1. Bagging
2. Boosting
3. Stacking
4. Voting

1. Bagging Classifier- The name BAGGing is derived from  Bootstrapping and Aggregation to create an ensemble model. Bagging involves fitting many decision trees on different samples of the same dataset and averaging the predictions.
2. Boosting Classifier involves adding ensemble members sequentially that correct the predictions made by prior models and outputs a weighted average of the predictions.
3. Stacking Classifier involves fitting many different models types on the same data and using another model to learn how to best combine the predictions.
4. Voting Classifier is a learning model that trains on an ensemble of numerous models and predicts an output (class) based on their highest probability of chosen class as the output.

