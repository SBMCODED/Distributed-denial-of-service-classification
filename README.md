The dataset contains 469478 rows and 9 columns,
the project aim to use both supervised machine learning algorithms and ensemble machine learning algorithms to detect denial of service. 
The target variable is classification which contains [0=  distributed denial of service and 1= normal].
The supervised machine learning model in the project are [support vector machine(svm), logisitic regression (LOG) and KNearest Neighbor(KNN)]
For the ensemble model i used [stacking, voting, graident boosting and bagging], for each of the ensemble model it contains some base models. 
Base model for bagging include 
i. DecisionTreeClassifier
Base model for voting include 
i. Logistic Regression 
ii. Random Forest 
iii. SVC (Support vector classifier)
Then for stacking, the base model include 
i. Logistic regression
Finally, a graph to show the comparison of the model for both supervised and ensemble model. 
