# Difference in Differences Analysis

## Overview
This repository contains a comprehensive analysis of program effectiveness using Difference-in-Differences (DiD) methodology. The analysis examines panel data from seven countries over 1990-1999, evaluating the impact of a program implemented in 1995.

## Key Features
- Panel data analysis across 7 countries (1990-1999)
- Treatment effect estimation using DiD
- Parallel trends testing
- Robust statistical diagnostics
- Visual analysis components

## Data Structure
```
Panel101.csv
- country: Country identifier (A-G)
- year: Time period (1990-1999)
- y: Outcome variable
- y_bin: Binary outcome indicator
- x1, x2, x3: Control variables
- opinion: Categorical opinion measure
- op: Binary opinion indicator
```

## Main Results
- Treatment Group: Countries C and F
- Control Group: Countries A, B, D, E, G
- Treatment Effect: -879,580,059.49
- P-value: 0.5943

## Requirements
```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
import statsmodels.api as sm
```

## Key Findings
1. The program shows a negative effect, though not statistically significant
2. Parallel trends assumption is satisfied
3. Results are robust across multiple specifications
