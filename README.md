# Lead-Scoring-CaseStudy
This repository contains the code and documentation for the lead scoring case study conducted for X Education, an online course provider. The objective of this study is to increase the lead conversion rate from the current average of 30% to approximately 80%. The lead scoring model aims to identify the most prospective leads with the highest probability of conversion.

Project Structure data/: This directory contains the dataset used for the analysis. It includes lead information, website interactions, course preferences, and demographic data. notebooks/: This directory contains Jupyter notebooks used for data preprocessing, exploratory data analysis, feature engineering, model development, and evaluation. models/: This directory contains the trained machine learning models used for lead scoring and classification. reports/: This directory contains the analysis report, presentation slides, and any other relevant documentation generated during the study. README.md: This file provides an overview of the project, instructions for running the code, and contact information. Requirements To run the code and reproduce the results, the following dependencies are required:

Python 3 Jupyter Notebook Pandas NumPy Scikit-learn Matplotlib Seaborn

Goals of the Case Study.

Building a logistic regression model to assign a lead score between 0 and 100 to each of the leads which can be used by the company to target potential leads. A higher score would mean that the lead is hot, i.e. is most likely to convert whereas a lower score would mean that the lead is cold and will mostly not get converted. There are some more problems presented by the company which my model should be able to adjust to if the company's requirement changes in the future so you will need to handle these as well. These problems are provided in a separate doc file.

Steps performed in the case study :
Importing of Data , Understanding of Data , Cleaning of Data , Univariate and Bivariate Analysis , Multivariate Analysis , Data Preparation , Train-Test Split , Feature Scaling using Standard Scaler , Feature Selection using RFE , Model Building , Model Evaluation , Plotting of ROC curve , Calculating optimal cut off point , Calculating Sensitivity, Specificity, Accuracy , Calculating Precision and Recall , Prediction of Test set ,

Model Performance : Let us compare the values obtained for Train & Test:

Train Data:

Accuracy : 80.16%

Sensitivity : 79.72%

Specificity : 80.41%

Test Data:

Accuracy : 80.87%

Sensitivity : 79.29%

Specificity : 81.79%

The Model seems to predict the Conversion Rate very well and we should be able to give the CEO confidence in making good calls based on this model
