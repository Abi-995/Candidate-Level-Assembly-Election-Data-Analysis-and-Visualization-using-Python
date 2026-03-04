Candidate-Level Assembly Election Data Analysis and Visualization using Python
Objective:
The objective of this project is to analyse candidate-level assembly election data to identify voting patterns, party performance, candidate demographics, and winning trends. The analysis aims to uncover insights into electoral competition, vote share distribution, margin of victory, and factors influencing election outcomes using data-driven techniques.
Detailed Objectives,
•	Maintain all candidate-level election information (candidates, parties, constituencies, vote counts, vote share, winning status) in one structured dataset.
•	Reduce data duplication and inconsistencies by cleaning and standardizing election records.
•	Monitor total votes, vote share percentage, winning margins, and seats won across constituencies.
•	Evaluate performance by candidate, political party, constituency, and region.
•	Identify top-performing parties and analyse constituency-wise competition levels.
•	Compare independent candidates and party-affiliated candidates’ performance.
•	Generate visual reports and dashboards for better understanding of election outcomes.
Data Information:
Source: Indian Open Data Portal
Dataset Name: Assembly Elections Data at Candidate Level
File Format: CSV (Structured Tabular Dataset)
Location: https://ckandev.indiadataportal.com/dataset/elections-in-india/resource/a3d7b841-90df-41dc-b786-95e9eb9cf7d0
Available Timeline: 2009-2016
Selected Timeline for Analysis: Latest available election period in the dataset (used for focused analysis)
The dataset contains candidate-level Assembly Election records, including details such as candidate name, political party, constituency, total votes secured, vote share percentage, winning status, and margin of victory.


Stage 1: Problem Definition and Data Understanding
 Problem Definition:
The objective of this project is to analyse Assembly Elections data at the candidate level to gain insights into voting patterns, candidate performance, and party-wise results.
The project aims to:
•	Identify winning candidates and analyse their vote margins.
•	Compare vote share percentages among candidates and parties.
•	Evaluate party performance across constituencies.
•	Detect closely contested seats.
•	Provide data-driven insights using statistical analysis and visualization.
The goal is to transform raw election data into meaningful insights that help understand electoral trends and outcomes.
Data Understanding:
The dataset contains candidate-level Assembly Election information with structured tabular data.
Key Attributes in the Dataset:
•	Candidate Name
•	Party Name
•	Constituency
•	Total Votes Secured
•	Vote Share (%)
•	Winning Status
•	Margin of Victory
•	State / Election Year (if available)
 Data Format:
•	CSV (Comma-Separated Values) file
•	Structured dataset suitable for analysis using Python (Pandas, NumPy, Matplotlib, Seaborn)
 Initial Observations:
•	The dataset may contain multiple candidates per constituency.
•	Only one candidate per constituency will have winning status.
•	Vote margins help identify closely contested elections.

Data Description:
•	The dataset contains candidate-level information from Assembly Elections in India. It includes details about candidates, their respective political parties, constituencies, total votes secured, vote share percentage, winning status, and margin of victory.
•	The dataset is structured in tabular format (CSV file) and is suitable for analysis using Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn.
•	Each row in the dataset represents a candidate contesting in a particular constituency, and multiple candidates may belong to the same constituency.
Initial Exploratory Data Analysis (EDA):
To understand the dataset structure and quality, the following initial EDA steps were performed.
Key Steps Performed in EDA,
Data Inspection
•	Used head() to view the first few records.
•	Checked column names and overall structure of the dataset.
Dataset Structure Analysis
•	Used shape to identify the number of rows and columns.
•	Used info () to examine data types and detect missing values.
Statistical Summary
•	Used describe () to generate summary statistics for numerical columns such as total votes and margin of victory.
•	Analysed mean, minimum, maximum, and quartile values.
Missing Value Analysis
•	Checked null values using isnull().sum().
•	Identified whether any columns required data cleaning.
Duplicate Record Check
•	Used duplicated(). sum() to detect repeated entries.
•	Ensured data integrity by removing duplicates if present.
Distribution & Trend Analysis
•	Analysed vote share distribution.
•	Examined party-wise seat counts.
•	Identified top-performing candidates and parties.

Outcome of EDA
EDA helped in:
•	Understanding dataset structure and quality
•	Identifying data cleaning requirements
•	Gaining initial insights into voting patterns
•	Preparing the dataset for further analysis and visualization
