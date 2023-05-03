# BreastCancerPrediction
Programming for AI - Project

Breast Cancer Prediction (Malignant versus Benign)

This project predicts the probability of a diagnosed breast cancer case that whether it is malignant or benign. Data Set used is uploaded by UCI Machine Learning on Kaggle: Breast Cancer Wisconsin (Diagnostic). 
Link to the dataset: https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data
We did classified supervised machine learning on this dataset as the target variable was categorical that is either diagnosis is malignant or benign.
I.	Exploratory Data Analysis:
ᶱ	After extracting the data from csv files we can describe it as:
There are 569 cases in this dataset
There are 32 features in this dataset
There are 212 cases diagnosed as malignant tumor
There are 357 cases diagnosed as benign tumor
The percentage of malignant cases is: 37.2583 
The percentage of benign cases is: 62.7417 %
ᶱ	Patient ID column were removed from the data due to their insignificance with respect to the project.
ᶱ	After analyzing the unique values, the data was divided into independent and dependent variables

II.	Separation of Test and Train Data:
ᶱ	The test and train data was separated in the 20% to 70% ratio accordingly.  

III.	Accuracies calculated of all the classified learning algorithms:
ᶱ	Accuracies calculated is represented in a bar graph
ᶱ	Confusion matrix of every algorithm is made to further inspect the efficiency of algorithm for our project

IV.	Algorithm with highest accuracy used to predict:
ᶱ	Naive Bayes proved to be perfect for predictions.
