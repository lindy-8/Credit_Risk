# Credit Risk Predictions Models 
This is a jupyter notebook application that observes historical data to predict high risk loans. Some of the parameters fed to the predictor model include loan size, interest rate, debt to income, total debt, and borrower income. In relation to the parameters the model is trained to assign a 0 or a 1 to determine if it was high risk or not. 
---

## Technologies & Libraries

This project utilizes python 3.7 with the following:

* [Pandas](https://github.com/pandas-dev/pandas) - For the command line interface, help page, and entrypoint.

* [Numpy](https://github.com/numpy/numpy) - The fundamental package for scientific computing with Python.

* [Metaplot](https://github.com/matplotlib/matplotlib) - For entrypoint and help page.

* [Imblean.metrics](http://glemaitre.github.io/imbalanced-learn/generated/imblearn.metrics.classification_report_imbalanced.html) - Build a classification report based on metrics used with imbalanced dataset.

* [Sklean.metrics](https://github.com/scikit-learn/scikit-learn) - Simple and efficient tools for predictive data analysis

---

## Pre Installation Guide

Prior to running this application, please first install the following dependencies:

```
import numpy as np
import pandas as pd
from pathlib import Path
from sklearn.metrics import balanced_accuracy_score
from sklearn.metrics import confusion_matrix
from imblearn.metrics import classification_report_imbalanced
import matplotlib.pyplot as plt

import warnings
warnings.filterwarnings('ignore')
```

---

## Contributors

DU Starter Code

Ben Lindauer

---

## License

MIT
