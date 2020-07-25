# Bank_dataset_tech_challenge
Cleaning and analysis challenge of a multi-table data set of a dummy bank. The dataset is available here: https://drive.google.com/file/d/1XAC-bK29qppHwQHrwVGBa4yCH6ocD7iL/view?usp=sharing

Given is a dataset of eight csv files. The goal is to prepare the dataset for analysis and work through five questions in the analysis phase. For a better understanding all tasks are performed in Jupyter notebooks.

Programming language: Python 3
packages
import numpy as np
import pandas as pd
import datetime
import pickle
import numpy as np
import pandas as pd
import pickle
import matplotlib.pyplot as plt
import sqlite3
from sklearn.ensemble import AdaBoostClassifier
from sklearn.model_selection import train_test_split
from sklearn import metrics
from sklearn.preprocessing import MinMaxScaler

TASKS
Cleaning:
1. Find flaws in the trans table
Analysis:
1. Look at some basic statistics of the data (mean, variance, etc.) of the “trans” table to understand it better. Print and explain an aspect of your choice (that you think is interesting) in the notebook.
2a What district has the highest share of “withdrawal in cash”? Please use a SQL querie to get the required table.
2b Please calculate the correlation between number of cash withdrawals per district and a number of inhabitants in particular district. Specify which correlation measure did you choose and describe the result.
3. Visualize the average loan amount per district.
4. Build an ML model that classifies if a certain loan will be paid or not. You can use any classification model you think is suitable (hint: there are also some out of the box available in MLlib). Note that the goal is not to get the accuracy as high as possible – it is completely OK to choose a simple model and not spend days on parameter tuning. Think about questions like:
a) Which model do you choose and why?
b) How do you do the training and how do you measure the model accuracy?
c) Which are the variables contributing the most to the prediction?
d) How accurate does your model get?
e) If you think a higher accuracy is possible, what would be the next steps you take?
5. Imagine that you are invited to go to a bank on-site and all they ask you is: “We have this data set above lying around. Could you do something with it that brings us some value?”

Can you think of a use case you could build that gets the bank excited? You do not need to implement something for this question, it is enough to describe your idea. Questions to guide your description:

a) What’s your idea about?
b) How would do implement it (technologies, algorithms, additional data, …)?
c) What is the value for the bank (maybe that value could be even measured with some metric)?
If your idea is something bigger which needs too much text to explain in detail, try to limit your description to the most important points and explain the rest in the call with us. (If it is helpful, you can also include a drawing.)
