# Exoplanet Exploration

![exoplanets.jpg](Images/exoplanets.jpg)

## Background

Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system.

To help process this data, you will create machine learning models capable of classifying whether a record is a candidate exoplanet from the dataset of observed objects.

In this homework assignment, you will need to:

1. [Preprocess the raw data](#Preprocessing)
2. [Tune the models](#Tune-Model-Parameters)
3. [Compare two or more models](#Evaluate-Model-Performance)

- - -

## Instructions

### Preprocess the Data

* Preprocess the raw dataset prior to fitting the model.
* Perform feature selection and remove unnecessary features. The dataset includes 50 columns-- how many will be sufficient for a healthy model?
* Use `MinMaxScaler` to scale the numerical data.
* Separate the data into training and testing data.

### Tune Model Parameters

* Use `GridSearch` to tune model parameters.
* Tune and compare at least two different classifiers. Three is recommended.

### Evaluate Model Performance

Compare the performance of your tuned classifiers to determine the best-performing model.

- - -

### Findings 

Based on the scores of various models including SVM, Logistic Regression, Decision Trees and Random Forest Classifiers, the best-performing model in predicting whether a record is a candidate exoplanet was the Random Forest Classifier model. The score was highest at 89% accuracy. All model scores were in the 80th percentile.

* Support Vector Machine Testing Data Score: 0.838975297346752
* Support Vector Machine (Tuned) Testing Data Score: 0.8714547118023788
* Logistic Regression Testing Data Score: 0.8435498627630376
* Decision Tree Testing Data Score: 0.848124428179323
* Random Forest Testing Data Score: 0.8934126258005489
