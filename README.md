- - -
### Reporting

* ### Techniques used
- Logistic Regression (LR)
- Random Forest Classifier (RFC)
- SVC
- Deep Learning
  
## Model Design Approach
- Build a base model using the original dataset and all features.
- Use the base model to evaluate feature importance.
- Tune the model parameters using *GridSearchCV*.
- Build the final model using the tuned parameters.

## Model Comparison
Random Forest Model has the higest accuracy scoring 0.901.<br />
![model_accuracy.png](Images/model_accuracy.png)

It is proved that Random Forest Model is the most accurate, it could to be a reasonable predictor of exoplanet candidacy.<br />
However, a model leveraging deep learning techniques might prove superior but the result is not as expected.<br />
![deep_learning_accuracy.png](Images/deep_learning_accuracy.png)
- - -

# Machine Learning Homework - Exoplanet Exploration

![exoplanets.jpg](Images/exoplanets.jpg)

### Before You Begin

1. Create a new repository for this project called `machine-learning-challenge`. **Do not add this homework to an existing repository**.

2. Clone the new repository to your computer.

3. Give each model you choose their own Jupyter notebook, **do not use more than one model per notebook.**

4. Save your best model to a file. This will be the model used to test your accuracy and used for grading.

5. Commit your Jupyter notebooks and model file and push them to GitHub.

## Note

Keep in mind that this homework is optional! However, you will gain a much greater understanding of testing and tuning different Classification models if you do complete it.

## Background

Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system.

To help process this data, you will create machine learning models capable of classifying candidate exoplanets from the raw dataset.

In this homework assignment, you will need to:

1. [Preprocess the raw data](#Preprocessing)
2. [Tune the models](#Tune-Model-Parameters)
3. [Compare two or more models](#Evaluate-Model-Performance)

- - -

## Instructions

### Preprocess the Data

* Preprocess the dataset prior to fitting the model.
* Perform feature selection and remove unnecessary features.
* Use `MinMaxScaler` to scale the numerical data.
* Separate the data into training and testing data.

### Tune Model Parameters

* Use `GridSearch` to tune model parameters.
* Tune and compare at least two different classifiers.

- - -

## Resources

* [Exoplanet Data Source](https://www.kaggle.com/nasa/kepler-exoplanet-search-results)

* [Scikit-Learn Tutorial Part 1](https://www.youtube.com/watch?v=4PXAztQtoTg)

* [Scikit-Learn Tutorial Part 2](https://www.youtube.com/watch?v=gK43gtGh49o&t=5858s)

* [Grid Search](https://scikit-learn.org/stable/modules/grid_search.html)

- - -

## Hints and Considerations

* Start by cleaning the data, removing unnecessary columns, and scaling the data.

* Not all variables are significant be sure to remove any insignificant variables.

* Make sure your `sklearn` package is up to date.

* Try a simple model first, and then tune the model using `GridSearch`.

- - -

## Submission

* Create a Jupyter Notebook for each model and host the notebooks on GitHub.

* Create a file for your best model and push to GitHub

* Include a README.md file that summarises your assumptions and findings.

* Submit the link to your GitHub project to Bootcamp Spot.

?? 2021 Trilogy Education Services, LLC, a 2U, Inc. brand. Confidential and Proprietary. All Rights Reserved.
