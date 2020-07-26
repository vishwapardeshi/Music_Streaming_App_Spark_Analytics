# Music Streaming App: Apache Spark Analytics

## Motivation
Sparkify is a fictional music streaming service. Like any product-based company, retaining existing customers is of prime importance as it is easier and cheaper to retain existing users than it is to acquire new users. Thus, here I analyze big data containing user log to perform churn analytics using exploratory analysis, feature engineering, analytics & machine learning techniques using Apache Spark Python Spark API, pySpark.

**The aim of the project is to predict customer churn propensity. If we can identify users that are at risk to churn either by downgrading from premium or by cancelling their service, the business can offer them incentives and discounts potentially saving millions in revenues.**

## Outline

## Dataset
The dataset contains log of the activities of each user on the service. It captures their behaviour - whether they are playing songs, logging out, upgrading their service or cancelling it.
cases of interactions which cannot be attributed to registered users are removed and a brief general overview of the reduced dataset is given.

### Metrics
Churn is defined as Submit Downgrade or Cancellation Confirmation events. If a user has at some instance performed the above two activities, he is considered a churned user.

## Methodology

Post performing exploratory data analysis, the dataset is cleaned. This included:
1. Removing Outliers

2. Scaling Features

3. Encoding features

Once the metrics is defined, a number of different aggregated features per user are discussed, created. These features are then compared across the two groups of users, churners and non-churners. In this process, promising features which are subsequently used for the machine learning models are identified.

The following Machine Learning Models are explored:
1. Logistic Regression

2. Random Forest Classifier

3. Gradient Boosting Trees

## Packages used
```
pyspark
time
matplotlib
numpy
pandas
pickle
os
tqdm
```
