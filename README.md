# Palette - An Art Genre Classification model
#### - By Isaiah Westphalen
------
The Art world is rich in history, movements, and different forms of self expression. As someone without a background in, say, art history, this vast wealth of information may seem daunting at first.
## Problem Statement 
------
Palette, an art genre classification model, aims to help those that are interested in learning more about art. More specifically, the idea is to create a model that art museums could use to both attract and educate new members in an effort to retain them as patrons. 
## The Data
----
The data used for training palette comes from the Painter by Numbers dataset from [kaggle](https://www.kaggle.com/c/painter-by-numbers/data?select=train_3.zip), which contains ~ 80,000 image files. 
## The EDA
----
We'll be exploring how to fix the class imbalances caused by genres being extremely under represented in this dataset
## The Modeling 
----
We'll be utilizing a convolutional neural network in order to classify our genres. 