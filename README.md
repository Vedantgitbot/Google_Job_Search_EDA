# Google_Job_Search_EDA

📌 Overview

This project performs Exploratory Data Analysis (EDA) on a dataset of job postings scraped from Google Jobs.
The main goal is to clean, process, and analyze job market data to uncover trends in salaries, locations, companies, and posting dates.

By parsing salary ranges, normalizing job titles, and extracting temporal and geographic insights, this project highlights how structured analysis can reveal hidden patterns in unstructured job postings.

🔑 Key Features

Data Cleaning & Preprocessing

Removed duplicates and irrelevant columns

Handled missing values in text and numeric features

Standardized job titles and locations

Salary Parsing & Normalization

Extracted minimum and maximum salaries from messy text formats (e.g., 101K–143K a year)

Converted salaries into numeric values (K → 1,000, M → 1,000,000)

Computed an average salary for consistent analysis

Date Feature Engineering

Extracted year, month, day, and weekday from posting dates

Enabled time-based analysis of job posting trends

Location Cleaning

Split job locations into city and state for better geographic insights

Exploratory Visualizations (if included in your notebook)

Salary distributions across roles

Top hiring companies and locations

Posting frequency trends

📂 Project Structure
├── EDA.ipynb           # Jupyter Notebook with analysis
├── gsearch_jobs.csv    # Raw dataset of job postings
└── README.md           # Project documentation

⚙️ Tech Stack

Python (pandas, numpy, re, matplotlib, seaborn)

Jupyter Notebook for interactive analysis

📊 Insights (examples)

Normalizing salary ranges reveals realistic average salaries across industries.

Certain cities and states dominate hiring trends for specific roles.

Posting activity shows seasonal variations (e.g., spikes in Q1 and Q3).

🚀 How to Use

Clone this repository:

git clone https://github.com/your-username/job-market-eda.git
cd job-market-eda


Install dependencies:

pip install -r requirements.txt


Open the notebook:

jupyter notebook EDA.ipynb

🎯 Future Work

Apply NLP techniques to job descriptions for skill analysis

Build a salary prediction model using regression

Create a dashboard (Streamlit / Power BI) for interactive insights
