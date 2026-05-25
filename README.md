# Math-4
# Spread Locator: A Statistical Distribution Analysis Model

## Project Overview

This project focuses on analyzing transaction data using different statistical distributions and probability models. The main objective is to identify patterns, understand transaction behavior, and determine the best statistical distribution for the dataset.

The project applies concepts such as Bernoulli Distribution, Binomial Distribution, Poisson Distribution, Log-Normal Distribution, Power Law Distribution, Q-Q Plot, Box-Cox Transformation, PDF, CDF, and Z-Score Analysis.

---

# Objectives

- Understand statistical distributions
- Analyze transaction behavior
- Detect skewness and outliers
- Apply probability models
- Perform distribution fitting
- Visualize data using graphs
- Improve normality using transformations

---

# Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- SciPy
- Statsmodels
- Jupyter Notebook

---

# Project Workflow

## Step 1: Import Required Libraries

Import all required Python libraries for data analysis, visualization, and statistical modeling.

```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

from scipy import stats
from scipy.stats import bernoulli
from scipy.stats import binom
from scipy.stats import poisson
from scipy.stats import zscore
from scipy.stats import lognorm
from scipy.stats import powerlaw

from statsmodels.graphics.gofplots import qqplot

import warnings
warnings.filterwarnings('ignore')
