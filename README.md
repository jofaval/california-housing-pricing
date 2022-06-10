# Californa Housing Pricing #

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jofaval/california-housing-pricing/blob/master/California_Housing_Pricing.ipynb)

## Table of contents

1. [📁 Data](#-data)
1. [📓 Description](#-description)
1. [✔️ Objectives](#-objectives)
1. [🧱 Tech stack](#-tech-stack)
1. [💹 Algorithms](#-algorithms)
1. [📊 Visualization](#-visualization)
1. [🤓 Conclusions](#-conclusions)
1. [©️ Credits](#-credits)

## 📁 Data

The data is available at the `sample_data` folder that is available with every Google Colab Notebook.

Just in case, you could change the path to the data by using the .csv found in the [/data](./data) of this repository

## 📓 Description

This is a beginner notebook, made to illustrate a more junior approach to a dataset's exploration, analysis and explanation.

It's an introduction, my introduction, to explaining conclusions and showcasing my data science work, is it the first notebook I've ever made? No it is not, but I feel that it may be a simple enough starting point that it can serve as an example.

So, what is there to expect from this project? Just a newbie explaining a couple of concepts and reaching to some sort of conclusions just by exploring the data and it's patterns.

## ✔️ Objectives

In no specific order whatsoever:

- Put together the knowledge adquired in a more fashionable way.
- Explore the data correctly in a way that makes sense.
- Upload a starter project to my fill non-existent data science portfolio.
- Define and explore ways to present the conclusions and the process.
- Learn more about a specific topic, in this case, the housing market of California in 1990.
- Improving and polishing my skills as a junior data scientist and data analyst.

There may be more, but I feel that this showcase a broad grasp at what I was looking to achieved with the project.
As for the analysis, what were some of the main objectives?

- To be able to predict the outcome and median housing pricing value in California.
- Being able to explain the variability of the dependant variable.
- Explaining and understanding why the housing pricing takes the value it actually takes.
- Using supervised models to explain the conclusion, as to be able to justify the results.

## 🧱 Tech stack

Python, that's it! R is a programming language that, as for the moment being, I have no experience with, even though it's powerful and broadly used, but I'd dare to say that no more than Python.

And one of the strongest points, if not the most, about Python, are it's libraries, so... the libraries I've used are:

- Pandas, data manipulation with an ease of use and exploration data analysis.
- Numpy, a really strong linear algebra library, used in the project for it's statistics utilities, SciPy may be an alternative, but I have no experience at all with it.
- Matplotlib and Seaborn, both fantastic libraries for data visualization, and they complement each other.
- Scikit-Learn, the library used for Machine Learning and statistics models: Linear Regression, SVR, Lasso, Ridge, etc.
- Tensorflow and Keras, the industry standard for Deep Learning, the way to go, not really, it's just that for now I don't have that many experience with PyTorch

## 💹 Algorithms

After the exploration of the data, I concluded that Linear Regression with a Polynomial factor was the one that could predict the variable the best, so it is Polynomial Linear Regression that I wanted to use, but I did "try my luck" with a couple other algorithms, Supervised and Unsupervised.

RandomForest it's pure magic, it's incredible how it can get such as high score, and actually, kind of explain some of it's conclusions, such as feature importance. But it's unsupervised, why it did what it did is not crystal clear which is not what I personally wanted as the main goal.

Support Vector Machine Regressor was a welcomed surprised, it actually performed even better than the Polynomial Linear Regression, but it wasn't as consistent as I expected, it required some features to exist to get a high score, and a certain amount of data to actually perform well, which was expected.

## 📊 Visualization

Being honest, visualizations I feel that weren't the strongest point in my take. But I did try to plot important information in a way that simplified the concept I was trying to get across.

Scatter was the plot I used the most, it helped represent density and identify more easibly where the sparsing of the data happened, plus, with high volumes of unsorted data that do not follow a pattern, is an easier way to plot that with lines while protraying a similar concept.

## 🤓 Conclusions

With the models used, supervised and unsupervised, I managed to explain 60% - 80% of the dependant variable, which is great but I'm pretty sure it could be better. Still, I'm happy with that score.

It is true that unsupervised is, generally speaking, more powerful than supervsied models, but having unsupervised models reach 70% and get close to the outcome of unsupervised ones, that's pretty neat!

As for the value, it was concluded that the location, and, most importantly, the median income of the surrounding houses, are what actually matter the most to determine the price of a house, way more than the bedrooms, or rooms that it has, or the population around.

## ©️ Credits

All of the credits for the datasets goes to Pace, R. Kelley, and Ronald Barry, "Sparse Spatial Autoregressions," Statistics and Probability Letters, Volume 33, Number 3, May 5 1997, p. 291-297. And to Google, but any more details [at this link](https://developers.google.com/machine-learning/crash-course/california-housing-data-description?hl=es_419)