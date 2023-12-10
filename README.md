<img src="https://bit.ly/2VnXWr2" alt="Yara Logo" width="100"/>

# Final Project | Car Price Comparison and Prediction


## Introduction

The intent of this project is to provide a price comparison prediction tool for cars being sold in differnet countries so the potential customers has the best deal in the makrket. We had several challenges web scraping the information from reliable sites and reputable sites with a suficient inventory. in the end got results from 2 sites in Europe. It was important at this initial stage that the sites were from locations within the EU has currency facilitates comparisons. 

## Imports

We imported the below libraries.
import pandas as pd
import numpy as np
import requests
from bs4 import BeautifulSoup

import time
from getpass import getpass
import time
from bs4 import BeautifulSoup
import requests
from selenium import webdriver
from selenium.webdriver.common.by import By
import matplotlib.pyplot as plt
import seaborn as sns
from selenium.webdriver.common.keys import Keys
from selenium.webdriver.edge.options import Options
from selenium.webdriver.edge.service import Service
import pandas as pd
import re
options = Options()
options.add_argument("--headless")

from sklearn.preprocessing import LabelEncoder
from sklearn.metrics import mean_squared_error
from sklearn.ensemble import GradientBoostingRegressor
from sklearn.preprocessing import MinMaxScaler
from sklearn.preprocessing import StandardScaler
import pickle
from datetime import datetime


## Deliverables

- a dataframe that allowed to compare car prices from different countries
- a prediction model for car prices

## Ackowledgements

Federico Raposo and Ricardo Guedes for all the support in this project
the second dataset was obtained from kaagle kaggle: kernels output goyalshalini93/car-price-prediction-linear-regression-rfe -p /path/to/dest

## Resources

[Gocar site](https://gocar.be/)

[Stand Virtual](https://www.standvirtual.com/carros)



