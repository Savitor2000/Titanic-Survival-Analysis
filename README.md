In this project, we use a logistic regression model to predict the survival of passengers on the Titanic based on various features. We explore the dataset, clean the data, perform feature engineering, and build the model to make predictions on a test dataset.

Dataset Information
The dataset is divided into two files: one for training and one for testing. It includes the following features:

PassengerId: Unique ID for each passenger.
Survived: Survival (0 = No, 1 = Yes).
Pclass: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd).
Name: Name of the passenger.
Sex: Gender of the passenger.
Age: Age of the passenger.
SibSp: Number of siblings/spouses aboard the Titanic.
Parch: Number of parents/children aboard the Titanic.
Ticket: Ticket number.
Fare: Passenger fare.
Cabin: Cabin number.
Embarked: Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).

We start by loading the training and testing datasets and checking their shapes.We calculate the total number of survivors in the training dataset.We check if the fictional characters Jack and Rose or the real passenger Beatrice Irene Sandstrom are in the dataset.
We calculate the survival rates based on different features.
We plot histograms of the age distribution for survivors and non-survivors.
We plot age histograms by passenger class (Pclass) and survival status.
We handle missing values in the dataset by filling them with appropriate values.
We build and train the logistic regression model.

We plot the coefficients of the logistic regression model to show the importance of each feature.
We clean the test data similarly to how we cleaned the training data.
