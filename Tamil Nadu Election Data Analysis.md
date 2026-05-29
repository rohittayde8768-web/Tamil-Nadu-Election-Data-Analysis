**Tamil Nadu Election Data Analysis Using Python**



**Project Overview**



This project focuses on analyzing the Tamil Nadu Election Dataset using Python.

The objective of this project is to perform data cleaning, exploratory data analysis (EDA), and visualization to understand party-wise performance, winning margins, and constituency-level election trends.



**Objectives**

Analyze party-wise seat distribution

Identify winning parties and strong constituencies

Perform margin analysis

Create election dashboard visualizations

Understand election trends using data analytics

Dataset Information



**The dataset contains the following columns:**



**Column Name	Description**

Constituency	Name of constituency

Const. No.	Constituency number

Leading Candidate	Winning candidate

Leading Party	Winning party

Trailing Candidate	Runner-up candidate

Trailing Party	Runner-up party

Margin	Vote difference between winner and runner-up

Round	Counting round status

Status	Election result status



**Technologies Used**

Python

Pandas

Matplotlib

Jupyter Notebook



**Data Cleaning Performed**



**The following cleaning operations were performed:**



Handled missing values

Removed duplicate records

Converted data types

Cleaned messy Round column values (31/31)

Converted margin values into numeric format

Standardized dataset structure



**Example:**



df\['Round'] = df\['Round'].str.split('/').str\[0].astype(int)

Exploratory Data Analysis (EDA)



**The following analyses were performed:**



Party-wise winners analysis

Seat share analysis

Winning margin analysis

Constituency comparison

Frequency distribution analysis

Visualizations Created

1\. Party-wise Winners Bar Chart



Shows the number of seats won by each political party.



2\. Party Seat Share Pie Chart



Visualizes percentage contribution of top political parties.



3\. Winning Margin Histogram



Shows distribution of winning margins across constituencies.



4\. Top Constituencies Chart



**Displays constituencies with highest winning margins.**



**Key Insights**

Tamilaga Vettri Kazhagam secured the highest seat share.

DMK and AIADMK emerged as strong competitors.

Several constituencies showed close electoral competition.

Margin analysis revealed both dominant and tightly contested victories.

Sample Libraries Used

import pandas as pd

import matplotlib.pyplot as plt

Project Outcome



**This project helped in understanding:**



Real-world data cleaning

Exploratory Data Analysis (EDA)

Data visualization techniques

Election trend analysis

Dashboard creation using Python



**Future Improvements**

Create interactive dashboard using Power BI/Tableau

Add live election data integration

Perform predictive analytics

Add constituency-wise filtering



**Conclusion**



This project demonstrates practical implementation of Python for data analytics using a real election dataset. It showcases data cleaning, analysis, visualization, and insight generation skills important for Data Analyst roles.



**Author**



**Gaurav Katre**



Aspiring Data Analyst | Python | Pandas | Data Visualization

