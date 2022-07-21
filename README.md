# Supervised Machine Learning Homework 

## Predicting Credit Risk

For this assignment, I built a machine learning model that attempts to predict whether a loan from LendingClub will become high risk or not. Further, I used an entire year's worth of data (2019) to predict the credit risk of loans from the first quarter of the next year (2020). My important steps to complete this process are as follows. 

### 1. Preprocessing: Converting Categorical Data to Numeric

I created a training set from the 2019 loans using LabelEncoder to convert the categorical data to numeric columns. Similarly, I created a testing set from the 2020 loans, also using LabelEncoder. 

### 2. The Models

I created and compared two models on the aforementioned data: a logistic regression, and a random forests classifier.

### 3. Fit Models on Unscaled Data

I created a LogisticRegression model, fitted it to the data, and printed the model's score. I did the same for a RandomForestClassifier as well. 

### 4. Revisit the Preprocessing: Scale the Data

I used `StandardScaler` to scale the training and testing sets.

### 5. Fit Models on Scaled Data

Finally, I fitted and scored the LogisticRegression and RandomForestClassifier models on the scaled data.
