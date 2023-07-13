# Titanic Dataset Exploration and Logistic Regression Model

## Introduction

This project is all about analyzing the Titanic dataset and making predictions using a logistic regression model. We'll fix missing values, change some data into numbers, and build a model to predict if a passenger survived or not.

## Dataset

The Titanic dataset is super famous! It has info about the people who were on the Titanic, like their age, gender, class, and if they survived or not.

## Data Preprocessing

We need to make the data ready for our model. So, we did a couple of things:

1. **Handling Missing Values**: Sometimes, we don't have data for some people. So, we did our best to fill in those gaps or remove the rows or columns with missing values.

2. **Changing Data**: Our model can only understand numbers. But some things like gender are words. So, we changed those into numbers to make our model happy.

## Logistic Regression Model

We used something called logistic regression to make predictions. It's a cool way to guess if something will happen or not. Here's how we did it:

1. **Splitting Data**: We divided our data into two parts - one to train the model and one to test how good it is.

2. **Teaching the Model**: We taught our model using the training data. It learned which features are important and how to calculate the chance of survival for each passenger.

3. **Checking the Model**: Finally, we checked how good our model is by using the testing data. We looked at stuff like accuracy, precision, recall, and F1-score to see how well it could predict if someone survived or not.

## Conclusion

In this project, we had fun exploring the Titanic dataset, fixing missing values, changing words into numbers, and building a logistic regression model to guess if a passenger survived. There's more we can do to make our model better, but for now, it's pretty cool!
