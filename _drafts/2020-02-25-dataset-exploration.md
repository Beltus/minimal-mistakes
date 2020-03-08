---
layout: single
published: true
title: Simple Dataset Exploration Techniques For Machine Learning.
collection: sc
author_profile: true
read_time: true
categories: [Blog] #[tutorials]
excerpt : "It is mind-blowing and fascinating how every part of our daily lives is being affected by machine learning driven applications and most of us go by our mundane life routines oblivious to this."
header :
    overlay_image: "https://beltus.github.io/vision/images/galaxy.png"
    teaser: "https://beltus.github.io/vision/images/ml.png"

comments: true
toc: true
toc_sticky: true
---

We live in world where data is millions of new datasets are created and posted per day. The unwieldy challenge that arises is how can we manage this crazy inflow of data and make the most out of it. If you are new to data science, it can be daunting and overly overwhelming to know how to deal with so much information.
in this article, I will like to provide the very basic techniques which will get your feet wet and your saliva inflow activated to dive even deeper in to world of Big Data using the powerful python library pandas.

In this article I share with you the general format for which most datasets are stored with explicitly explanations for each section of the dataset. As an icing to the cake i will provide links to the sites that are considered the big guns of dataset collection You will be able to download your own datasets and perform diligently investigation of its contents and the relationships between the different facets that make it up.

Here is the pitfall
> Never dive head first into using any dataset without properly having a holistic understanding of how it was structured by the creators and how the independent variables relate with the dependent variable. This will cause you painful headaches in the later parts of your machine learning project and no one likes headaches.

Okay, lets get to it

## Step 1: Importing Revelant Libraries
```python
import numpy as np
from sklearn import model_selection
from sklearn import svm
import pandas as pd
import zipfile

```

## Side Step: List all Files in Dataset Folder
```python
from subprocess import check_output
print(check_output(["ls" , "/home/beltus/image/Data Science/datasets"]).decode("utf8")) #List all files in dataset folder
print(check_output(['ls', "/home/beltus/image/Data Science/datasets/"]).decode("utf8"))
```


## Step 2: Load Dataset into Code File - Jupyter NoteBook(For me)
```python
dataset = pd.read_csv("./datasets/airline-safety.csv")

```

## Step 3: Display the number of Observations(Samples) and the number of Features(Attributes) In your Dataset¶
```python
dataset = pd.read_csv("./datasets/airline-safety.csv")
```

## Step 4: Take a Quick Peak at the contents of your Dataset
```python
pd.dataset.head(10) # List the first 10 rows of dataset
```


## Step 5: Load Dataset into Code File - Jupyter NoteBook(For me)
```python
dataset = pd.read_csv("./datasets/airline-safety.csv")

```


## Step 2: Load Dataset into Code File - Jupyter NoteBook(For me)
```python
dataset = pd.read_csv("./datasets/airline-safety.csv")

```