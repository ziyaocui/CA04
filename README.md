## Name of project
Ensemble Model

## Project Overview 
The data Census Bureau and represents salaries of people along with seven demographic variables. Set data into different categories and use train data to build a model for test data. Finally purpose is to find the best model and decision tree.

## Instruction
Please use the census data to run the code in Google Colab

## Installation instructions
Use the following packages:

```bash
pandas
numpy
os
matplotlib pyplot
sklearn.metrics
```
## Usage 
```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt

from sklearn.tree import DecisionTreeClassifier
from sklearn.ensemble import RandomForestClassifier
from sklearn.ensemble import AdaBoostClassifier
from sklearn.ensemble import GradientBoostingClassifier
from xgboost import XGBClassifier

from sklearn.metrics import roc_curve
from sklearn.metrics import auc
from sklearn.metrics import roc_auc_score
from sklearn.metrics import accuracy_score
from sklearn.metrics import precision_score
from sklearn.metrics import f1_score
from sklearn.metrics import recall_score
```

## Operating instructions
1. First step is to improt all packages that will use later.
2. Next step is to optimal value for a Hyper parameter and build a random forest model and plot.
3. Next part is to make 3 different models and plot. 
4. Choose the best hyper parameter and compare accuracy sore and auc for each model.

## Conclusion
Using 50 as optimal value gives higher accuracy and auc.

## Colab access
https://colab.research.google.com/drive/1XD22eC2QwhLd91HBps_fOaKNah2p95mn?usp=sharing

## Data
"census_data.csv"

## Contact information
Name: Ziyao Cui
