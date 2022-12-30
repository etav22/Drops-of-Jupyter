# Drops-of-Jupyter
This repo houses several different jupyter notebooks to demonstrate my growing skillset. Mainly centered around modeling, data exploration and new python packages.

## Setup
For this repository, I used a `conda` virtual env to house all my dependencies. Nevertheless, a regular virtualenv can be used and the dependencies can be installed via the `requirements.txt`:
```
$ python3 -m venv env
$ source env/bin/activate
$ pip install -r requirements.txt
```

## Notebooks
Where all the magic happens! All the jupyter notebooks are housed in the `notebooks` directory. As the repo grows, I will most likely add more directories to house different sorts of notebooks. Regardless, here is a quick summary of the current notebooks found in this repo:

|Notebook Title | Type | Goal |
| -------------- | ---- | ---- | 
| [regression-classification](notebooks/regression-classification.ipynb) | Instructional | Demonstrate two popular problems with custom data in supervised learning: **regression** and **classifcaiton**. |
| [spaceship-titanic](notebooks/spaceship-titanic.ipynb) | Modeling/New Packages | Using the spaceship titanic dataset from Kaggle, I tested fitting different models with **lightgbm** and **xgboost** (also tried out **optuna** as an optimization tool) |
| [supervised-unsupervised](notebooks/supervised-unsupervised.ipynb) | Instructional | Similar to the regression-classification notebook, but here I focus on unsupervised learning (and more specifically solely **k-means clustering**)|
| [naive-bayes](notebooks/naive-bayes.ipynb) | Educational | A notebook using the heart failure dataset from Kaggle to better educate myself on **naive-bayes** models |
| [torched-fruits](notebooks/torched-fruits.ipynb) | Modeling/New Package | One of the very first notebooks I created after going through a **pytorch** intro course. This notebook uses the fruits dataset from kaggle and a custom built **CNN** to classify fruits. |