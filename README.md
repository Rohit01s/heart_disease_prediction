# Predicting Likelihood of Heart Disease Using Machine Learning Approaches.

Description about the Project:

The heart disease remains a significant public health concern worldwide today. Early and accurate prediction of heart disease risk can help the patient to take the quick action towards it. While various risk assessment models exist, there is a need for more sophisticated and precise predictive methods that can leverage the power of machine learning algorithms to enhance accuracy and reliability in predicting individuals at risk of heart disease by taking the use of previous medical records of patients with heart diseases or not with hear disease. The aim of this project is not to eliminate the job of doctors but to give a tool that might be accessible to every person around the world that can use it in early prediction of disease and get the right time diagnosis of the disease.

This project was done as the minor dissertation project work for partial fulfillment of the Second semester paper “Research Methodology” for the course Master of science in Bio-statistic, 2022-24, under the supervision of Dr. Ashish Kumar Yadav, Professor at Centre of Bio-Statistics, Institute of Medical Sciences, BHU. 

This project encompasses the following processes for fulfilling its objective:

• Performed Exploratory data analysis which includes stub steps in itself, like Data understanding step, data preparation step (missing value detection and handling, duplicate and outliers detection and handling), checking multicollinearity in the data and handling them if present. Univariate analysis, data visualization steps using count plots, scatter plots, displots. Feature understanding and relationship step using bivariate analysis, heatmaps and pairplots.

• Scaled our dataset using Standard Scaler.

• Applying classification task algorithms like Logistic regression, K-Nearest Neighbors, Support Vector Machines, Decision Trees, Random Forest Classifier and Naïve-Bayes Classifier models.

• To evaluate the performance of the above classifier models, I’ve made a user-defined function and evaluated the performance of each classifier.

• What I've noticed is that all models performed nearly same, but the performance Support vector machine was slightly higher than other models.

• After that, I checked for the performance. We also did hyperparameter tuning for support vector machines to find the best kernel and c value for the SVM model, which comes out to be linear kernel with C value of 1.

• We at last made a predictive system for new patients with the same set of data to find if they have heart disease or not.
