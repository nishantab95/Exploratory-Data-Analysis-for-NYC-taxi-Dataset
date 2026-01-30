📊 NYC Taxi Trip Data – Exploratory Data Analysis (EDA)
📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on the NYC Yellow Taxi Trip Dataset to understand travel patterns, fare behavior, tipping trends, and data quality issues.
The analysis focuses on cleaning raw data, handling missing values and outliers, and deriving insights using visualizations.

This project demonstrates practical data cleaning, feature engineering, and analysis skills using Python and Pandas, which are essential for real-world data analytics and machine learning workflows.

🗂 Dataset

Source: NYC Yellow Taxi Trip Records

Key Features Used:

Pickup & drop-off datetime

Trip distance

Passenger count

Fare amount

Tip amount

Rate code

Payment type

🔧 Data Cleaning & Preprocessing

The following steps were performed to improve data quality:

Converted pickup and drop-off timestamps to datetime format

Created trip_duration feature from pickup and drop-off time

Handled missing values using mean, median, or mode based on data distribution

Removed or capped outliers (e.g., trip duration > 5000 seconds)

Fixed invalid values such as:

Negative fares

Zero or unrealistic passenger counts

Dropped unnecessary or redundant columns

📊 Exploratory Analysis Performed

Distribution analysis of:

Trip distance

Fare amount

Trip duration

Tip percentage analysis based on:

Trip distance

Passenger count

Time of pickup

Comparison between low-tip vs high-tip trips

Group-by analysis to identify patterns in passenger behavior

📈 Visualizations

Histograms for numerical distributions

Boxplots to detect outliers

Bar charts for categorical comparisons

Time-based analysis of trip and tip behavior

🛠 Tools & Technologies

Python

Pandas

NumPy

Matplotlib / Seaborn

Jupyter Notebook

🎯 Key Learnings

Importance of data cleaning before analysis

How outliers impact real-world datasets

Feature engineering using datetime columns

Interpreting business insights from taxi trip data

Writing structured, reproducible EDA workflows

🚀 Future Improvements

Apply statistical tests for deeper insights

Build predictive models for fare or tip amount

Extend analysis using machine learning techniques

Automate EDA using reusable functions
