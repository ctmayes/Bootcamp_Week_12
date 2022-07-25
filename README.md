# Bootcamp_Week_12

# Credit Risk Resampling

## Overview of the Analysis

The main objective of this code is to utilize machine learning methods to evaluate the credit worthiness of potential borrowers with a high degree of certainty. To do this we analyzed two different datasets one imbalanced set and another resampled. Our imabalanced data set includes a mismatched ratio of approved and declined loans, while our resampled set includes an equal quantity of each subsection. 

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models:

* Machine Learning Model 1:
        Accuracy Score: 95%
        Precision: 85%
        Recall: 91%

* Machine Learning Model 2:
        Accuracy Score: 99%
        Precision: 84%
        Recall: 99%

## Summary

Baed upon the results, I would suggest making use of the second machine learning model. This model made us of the resampled data and a logistic regression to find overall better results. The only area where it is lacking is in precision, but 1% gap in that category is offset by significant gains in accuract and recall. The first model utilized the imbalanced dataset, and made use of linear regression, but the results were not quite as promising as what the second model produced.

## Technologies

Within this program, we will make use of the following external python modules:

  -- pandas
  -- holoviews
  -- pathlib
  -- sklearn.metrics
  -- imblearn.metrics
  -- numpy

  
  Additionally, this program was created within a python v3.7 build, and its relevant dependencies.

---

## Installation Guide

To utilize this program, within your terminal you will have to install the required libraries. Within your terminal, input the following commands:

```python
conda install pandas
```

```python
conda install numpy
```

```python
pip install -U scikit-learn
```

At the beginning of the *credit_risk_resampling.ipynb* file, the technologies are calling in with this code:

```
# Import the modules
import numpy as np
import pandas as pd
from pathlib import Path
from sklearn.metrics import balanced_accuracy_score
from sklearn.metrics import confusion_matrix
from imblearn.metrics import classification_report_imbalanced

import warnings
warnings.filterwarnings('ignore')
```

---

## Usage

To operate this program, open up your terminal of choice and navigate to the directory in which you have downloaded the files within this repository. Open Jupyter Lab with the command: 

```python
jupyter lab
```  

This should open jupyter lab to the filepath in which you have the repo file, and you simply need double click the *credit_risk_resampling.ipynb* file to open it. Upon opening, select the menu button with two right facing arrows at the top of the notebook, which will run the entire file. It will ask you to confirm you wish to restart the file, to which you will confirm. Wait a few moments for the program to operate as intended, and peruse the resulting data at your leisure. If you wish, simply skip to the end for my analysis of the preceding information. 

---

## Contributors

Colton Mayes ctmayes@gmail.com

---

## License

This code is created for educational purposes, and it usage therein has no commerical application. It is designated as free-use thusly, and shall remain as such.
