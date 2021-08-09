# Machine-learning-Classification---Census Income
**Business Understanding**
The objective of the Census Bureau is to use attributes like an individual’s age, work-class, education, level of education, marital-status, occupation, relationship, biological sex, capital loss, capital gain, hours they work per week, native country, and the number of people the entry presents to determine if an adult earns more or less than $50,000 a year. 

**Data Understanding**
The dataset is the census income dataset from the census bureau, available from the UCI machine learning Repository. The objective of this analysis is to build a classification model that would predict if an adult would more than $50,000 a year or not based on a number of attributes.
The attributes are age, work class, final weight (fnlwgt), education, education-num, marital status, occupation, relationship, sex, capital-gain, capital-loss, hours-per-week and native-country which are the input variables (X) and income as the output variable (Y).
This data analysis is being done the tool for this task is the Python’s Jupyter Notebook which is simple to use and allowing for the easy building of machine learning models. This is a supervised machine learning task because the labels are known and classification is being used because the labels are discrete and already assigned to a class. Five classification models would be used for these analysis and they are the K’s nearest neighbour (KNN), Support Vector Machine, Decision Tree, Logistics Regression, Neural Networks and Logistic Regression.  The model would be evaluated using the 60%, 40% single split and the Kfold validation with K=5. The features would also be ranked using the feature ranking with recursive feature ranking with recursive feature elimination algorithm with a goal of identifying the optimal features. The investigations would firstly be done using all the features without selection, then with feature selection based on the findings. 
