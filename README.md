# Binary-Classification
So, first of all the problem which we have to solve is a binary classification problem.

We started with how the data looks like and what type of data we have in the testing dataset. So, all the data consisted of two types float and int and we also checked if there are any Null values in our dataset. If they are present then we replace it with the mean of that value.
After that we tried the exploratory analysis on the dataset in which we saw the scatter plot of ouyr data and distribution of the data with respect to the target variable and with that we also built a corelation matrix. So, that we can easily select the features to use while performing analysis.
After completing these steps some of the features that were not relevent to the target variable we dropped them and then we looked into the models which we could use for our prediction. So, first we used the Logistic Regression model which provided us with the accuracy of 90%. Then we also tried using linear SVM but the Logistic Regression Model was giving better results. So, we stuck with that only.
