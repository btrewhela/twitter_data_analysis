# WeRateDogs Twitter Analysis
In this project, I analyze the WeRateDogs Twitter account and other databases to obtain 3 relevant insights using Jupyter Notebook.

## Installation Instructions
In order to use this code, you will need to install the following Python Libraries:
```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
import requests
import os
from bs4 import BeautifulSoup
import tweepy as tw
import json
import glob
import datetime as dt
import re
import seaborn as sns
```

## Notebook Structure

The notebook is structured as a typical data analysis workflow and includes:

1. Data Gathering
2. Data Assessing
3. Data Cleaning
4. Data Storing
5. Data Analysis

During each of these stages there are several python codes that execute different tasks including:

1. Data Gathering from locale, URL and Twitter API.
2. Assessing Quality and Tidiness Issues using descriptive analysis.
3. Data filtering, renaming, replacing, null values treatment and creating of new variables.
4. Regular expressions for tweet data cleaning.
5. Three different insights obtained from a clean database with visualizations.
