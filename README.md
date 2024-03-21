Aim
We are provided with historical sales data for 1,115 Rossmann stores. The task is to forecast the "Sales" column.
Approach
1. Exploratory Data Analysis
Exploratory data analysis is the process of analysing the dataset to understand its characteristics. In this step, we will figure out the following.
a. Identifying the number of unique users
b. Platforms used by the users the most
c. Correlations
d. Checking for null / inconsistent values and various other insights are drawn.
2. Imputation
This step involves the process of filling the missing values in appropriate ways so
that the data is not lost.
3. Outliers Detection and removal
Outliers are nothing but points that are abnormally distant from the other points.
These kinds of outliers present in the data are detected and eliminated.
4. Further Exploratory Data Analysis
Further EDA is performed to understand the data more and find out a few exceptional
cases.
5. Label Encoding and One hot encoding
Machine learning algorithms for regression can understand the input only in the form of numbers and hence it is highly essential to convert the non - numeric data that we have to numeric data by providing them labels.
6. Model Building and evaluation
Various regression algorithms are applied on the dataset and the model that suits best for the dataset is selected. The models that we apply for this dataset are
a. Linear Regression
b. SGD Regression
c. Random Forest Regressor
d. Decision Tree Regressor
7. Feature Importance Analysis
Once we have the right model selected (which in our case is Random forest regressor as this gives us the best train and test accuracy) it is also essential to understand what are the features that contribute the most or least towards the result.
