#Importing libraries 
import pandas as pd
import numpy as np 
import matplotlib.pyplot as plt 
%matplotlib inline

#Reading file
df=pd.read_csv('Position_Salaries.csv')

#
X = df.iloc[:, 1:2].values
y = df.iloc[:, 2].values
