# Phonepe-Pulse
## Domain: Fintech


#  Introduction

PhonePe has become one of the most popular digital payment platforms in India, with millions of users relying on it for their day-to-day transactions. The app is known for its simplicity, user-friendly interface, and fast and secure payment processing. It has also won several awards and accolades for its innovative features and contributions to the digital payments industry.
We create a web app to analyse the Phonepe transaction and users depending on various Years, Quarters, States, and Types of transaction and give a Geographical and Geo visualization output based on given requirements.

# Import Libraries
 1.import pandas as pd
 2.import numpy as np
 3.import os
 4.import json
 5.import sqlite3
 6.import streamlit as st
 7.import plotly.express as px

# E T L Process
a) Extract data
Initially, we Clone the data from the Phonepe GitHub repository by using Python libraries. 

https://github.com/PhonePe/pulse.git

b) Process and Transform the data
Process the clone data by using Python algorithms and transform the processed data into DataFrame formate.

c) Load data
Finally, create a connection to the MySQL  and create a Database and stored the Transformed data in the MySQL server by using the given method. df.to_sql('table_name', connection, if_exists = 'replace', index = False, dtype={'Col_name':sqlalchemy.types.datatype()})
# E D A Process and Frame work

a) Access MySQL DB
Create a connection to the MySQL server and access the specified MySQL DataBase by using pymysql library

b) Filter the data
Filter and process the collected data depending on the given requirements by using SQL queries

c) Visualization
Finally, create a Dashboard by using Streamlit and applying selection and dropdown options on the Dashboard and show the output are Geo visualization, bar chart, and Dataframe Table


# User Guide

Step 1.
Select any one option fron All India or State wise or Top Ten categories.

Step 2.
Select any one option fron Transaction or User.

Step 3.
Select any Year, Quarter and additional required option.

Step 4.
Finally, You get the Geo Visualization Analysis or Bar chart Analysis and Table format Analysis
        - Geo visualization: You will learn how to create and display data on a map using Plotly's built-in geo map functions.
