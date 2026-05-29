📌 Project Overview

This project focuses on analyzing the Tamil Nadu Election Dataset using Python. The objective of this project is to perform data cleaning, exploratory data analysis (EDA), and visualization to understand election trends, party-wise performance, winning margins, and constituency-level insights.

The project demonstrates practical data analytics skills using real-world election data.

🎯 Objectives
Perform data cleaning and preprocessing
Analyze party-wise seat distribution
Identify top-performing political parties
Analyze constituency-wise winning margins
Create visual dashboards using Python
Generate meaningful election insights

📂 Dataset Information

The dataset contains the following columns:

Column Name	Description
Constituency	Name of constituency
Const. No.	Constituency number
Leading Candidate	Winning candidate
Leading Party	Winning political party
Trailing Candidate	Runner-up candidate
Trailing Party	Runner-up political party
Margin	Difference in votes
Round	Counting round status
Status	Election result status

🛠️ Technologies Used
Python
Pandas
Matplotlib
Jupyter Notebook

🧹 Data Cleaning Performed

The following preprocessing steps were performed:

✅ Handled missing values
✅ Removed duplicate records
✅ Cleaned messy data formats
✅ Converted datatypes
✅ Processed Round column values (31/31 → 31)
✅ Standardized dataset structure

Example:

df['Round'] = df['Round'].astype(str).str.split('/').str[0].astype(int)

📊 Exploratory Data Analysis (EDA)

The following analyses were performed:

Party-wise seat analysis
Winning margin analysis
Constituency comparison
Frequency distribution analysis
Election trend visualization

📈 Visualizations Created
1. Party-wise Winners Bar Chart

Shows the number of seats won by each political party.

2. Party Seat Share Pie Chart

Displays percentage contribution of top political parties.

3. Winning Margin Histogram

Analyzes distribution of winning margins across constituencies.

4. Top Constituencies Chart

Shows constituencies with highest winning margins.

🔍 Key Insights

Tamilaga Vettri Kazhagam secured the highest seat share.
DMK and AIADMK emerged as major competitors.
Some constituencies showed very close electoral competition.
Margin analysis revealed both dominant victories and competitive contests.

📚 Libraries Used

import pandas as pd
import matplotlib.pyplot as plt

🚀 Project Outcome

This project helped in understanding:

Real-world data cleaning
Exploratory Data Analysis (EDA)
Data visualization techniques
Election trend analysis
Dashboard creation using Python

🔮 Future Improvements

Create interactive dashboard using Power BI/Tableau
Add live election data integration
Perform predictive analytics
Build constituency-level interactive filters

✅ Conclusion

This project demonstrates the practical implementation of Python for data analytics using a real-world election dataset. It showcases skills in data cleaning, analysis, visualization, and insight generation, which are essential for Data Analyst roles.

👨‍💻 Author

Rohit Tayde
Aspiring Data Analyst
