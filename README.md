# Purpose and Overview
The purpose of this project is to develop a model for a mobile carrier that will pick the right plan (Smart or Ultra), based on behavior data from subscribers who have already switched to the new plans.

The project is split into an Introduction section and 2 main segments: a brief overview and general analysis of the original data, and then choosing and developing a model, split into sub-sections, finishing with a brief conclusion. There is a table of contents that can be used to skip to a listed section and points throughout the project that link back to the table of contents.

# Required libraries and modules
import pandas as pd <br>
import numpy as np <br>
import plotly.express as px <br>
from sklearn.model_selection import train_test_split <br>
from sklearn.metrics import mean_squared_error <br>
from sklearn.ensemble import RandomForestClassifier <br>
from sklearn.model_selection import learning_curve <br>
import matplotlib.pyplot as plt <br>
import plotly.graph_objects as go <br>
from sklearn.tree import DecisionTreeClassifier <br>
from sklearn.ensemble import RandomForestRegressor <br>
from sklearn.metrics import accuracy_score <br>
from sklearn.linear_model import LogisticRegression <br>
from sklearn.model_selection import cross_val_score

# Dataset
'datasets/users_behavior.csv'
