# Day-7

Today's task is about SVM (Support Vector Machine). Better than perceptron learning model as it chooses the best line to separate the classes and can also be used for non-linear decision boundaries.

Steps followed are as follows:-
1. Imported the libraries. There were no null values. Then I encoded the categorical values of the target variable and standardized the data.
2. Then used GridSearchCV to choose the best model between linear and svm, best c value, best gamma value, etc based on recall score is False Negatives must be low.
3. Then visualized the decision boundaries by first using PCA to choose the best 2 features and then visualized the boundary between them.
