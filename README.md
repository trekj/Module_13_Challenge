# Venture Funding with Deep Learning

You work as a risk management associate at Alphabet Soup, a venture capital firm. Alphabet Soup’s business team receives many funding applications from startups every day. This team has asked you to help them create a model that predicts whether applicants will be successful if funded by Alphabet Soup.

The business team has given you a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. With your knowledge of machine learning and neural networks, you decide to use the features in the provided dataset to create a binary classifier model that will predict whether an applicant will become a successful business. The CSV file contains a variety of information about these businesses, including whether or not they ultimately became successful.

## Technologies
This project is written in Python 3.8 with the following libraries:

***panda*** -a Python package that provides fast, flexible, and expressive data structures designed to make working with "relational" or "labeled" data both easy and intuitive.

***sklearn*** -Scikit-Learn is a free machine learning library for Python. It supports both supervised and unsupervised machine learning, providing diverse algorithms for classification, regression, clustering, and dimensionality reduction. The library is built using many libraries you may already be familiar with, such as NumPy and SciPy. It also plays well with other libraries, such as Pandas and Seaborn.

***tensorflow*** - is a free and open-source software library for machine learning and artificial intelligence. It can be used across a range of tasks but has a particular focus on training and inference of deep neural networks.


## Installation Guide
Before running the application first install the following dependencies.

import pandas as pd

from pathlib import Path

import tensorflow as tf

from tensorflow.keras.layers import Dense

from tensorflow.keras.models import Sequential

from sklearn.model_selection import train_test_split

from sklearn.preprocessing import StandardScaler,OneHotEncoder

from path import Path



***Usage***
After cloning the repository, open the directory Starter Code and run the program by typing python venture_funding_with_deep_learning.ipynb

***Contributors***

James Tagapan

jtagapan@gmail.com

License

Licensed under the MIT License. Copyright 2020# Module_10_Challenge
