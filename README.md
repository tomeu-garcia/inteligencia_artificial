# Intel·ligència Artificial

# Machine learning  2020-2021 - UIB 

This repository contains the practice of FIFA

## Install

We can install this repository with or without conda.

The first step is to download the repository
```
     git clone https://github.com/tomeu-garcia/inteligencia_artificial.git
```

**Conda**

Once we have the repository on our compute using conda prompt we create the 
environment with this commands.
```
    conda env create --file environment.yml
    
    pip install numpy
    pip install jupyter
    pip install pandas
```

**Libraries**

To run the application it is necessary to use the following libraries:
```
import os

from sklearn.model_selection import train_test_split
from sklearn import linear_model
from sklearn.metrics import mean_squared_error, mean_absolute_error, r2_score

import pandas as pd
import numpy as np
import matplotlib.pyplot as plt

%matplotlib inline
```
