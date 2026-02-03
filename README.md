📉 Unemployment Rate Analysis in India (COVID-19 Impact)
📌 Project Overview

This project analyzes unemployment rate data in India to understand trends, seasonal patterns, and the impact of COVID-19. The goal is to practice data cleaning, exploratory data analysis (EDA), and visualization using Python, while learning how external shocks affect employment stability.

📂 Dataset

Unemployment in India.csv

The dataset contains time-based unemployment rate estimates across Indian states and regions.

🛠️ Tools & Libraries Used

Python

Pandas

NumPy

Matplotlib

🔍 Methodology
1. Data Cleaning

Removed extra spaces from column names

Converted date column to datetime

Verified missing values and data types

2. Data Aggregation

Aggregated unemployment rates by date using mean values

Ensured one unemployment value per time point for proper time-series analysis

3. Exploratory Data Analysis

Visualized average unemployment trends over time

Identified sharp changes during early 2020

Compared pre-COVID and post-COVID unemployment statistics

4. COVID-19 Impact Analysis

Split data into pre-COVID and post-COVID periods

Computed mean and standard deviation of unemployment rates

Observed significant increase in both average unemployment and volatility post-COVID

5. Seasonal Trend Analysis

Extracted month from date

Analyzed monthly average unemployment rates

Visualized seasonal patterns using bar charts

📊 Key Observations

A sharp spike in unemployment is observed around April–May 2020

Post-COVID unemployment shows significantly higher volatility

Seasonal patterns are visible but disrupted during the lockdown period

Job market stability decreased during the pandemic

🧠 Policy Implications

The sudden rise and increased volatility in unemployment during COVID-19 highlight the importance of employment continuity measures such as remote work support, wage protection, and crisis-response labor policies to reduce economic shocks.

▶️ How to Run the Project
pip install pandas numpy matplotlib


Run the analysis in Google Colab or Jupyter Notebook.

📚 Learning Outcome

This project strengthened understanding of:

Time-series aggregation

Interpreting volatility using standard deviation

Separating trends from seasonal patterns

Drawing data-supported economic insights
