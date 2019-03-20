# fast-ai-machine-learning-1
Fast.ai Machine Learning course work and notes

## Linux Red Hat 7 setup

```
git clone https://github.com/fastai/fastai.git
cd fastai
conda env create -f environment.yml -n fastai-old
conda activate fastai-old
cd old
pip install -e .
```
Now you can use fastai everywhere where the `fastai-old` conda environment is
activated.

```
$ conda activate fastai-old
$ python
Python 3.6.8 |Anaconda, Inc.| (default, Dec 30 2018, 01:22:34) 
[GCC 7.3.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> import fastai
>>> fastai
<module 'fastai' from '/home/roessland/ds/fastai/old/fastai/__init__.py'>
>>> help(fastai)
>>> from fastai.imports import *
>>> 
```

## Data

### bulldozers

https://www.kaggle.com/c/bluebook-for-bulldozers/

### titanic

https://www.kaggle.com/c/titanic/


## Notebooks

**Lesson1**: Notes from lesson 1. Bulldozers sales price regression using
RandomForestRegressor, and some feature engineering with dates. Creating and
reordering categorical variables. Fixing missing values by replacing them with
their median.

**Lesson1-titanic**: [Predicting survivors of the Titanic on
Kaggle](https://www.kaggle.com/c/titanic/) using RandomForestClassifier and
very basic feature engineering. Achieving 0.775 accuracy on the test data,
which is around 50% on the leaderboard.
