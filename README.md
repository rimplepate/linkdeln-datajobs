📊 LinkedIn Data Jobs Analysis
This project analyzes a dataset of LinkedIn job postings related to data roles such as Data Analyst, Data Scientist, and Data Engineer. It combines SQL querying and data visualization using Python to explore job market trends.

📁 Dataset
The dataset (clean_jobs.csv) contains scraped LinkedIn job postings with the following key columns:

title – Job title (e.g., "Data Analyst", "Data Scientist")

company – Company name

location – Job location (city/country)

description – Full job description text

work_type and employment_type – (Note: Empty in this version)
This script performs:

✅ SQL Analysis (via SQLite)
Top 10 Most Common Job Titles

Top 10 Locations with Most Jobs

Jobs mentioning "Python" in the description

📊 Visualizations (via matplotlib and seaborn)
Bar charts of the top job titles and top job locations

📌 Output
Bar plots showing the most common job titles and locations

A printed table of job listings that mention Python

Easy to extend with additional SQL queries or visualizations

🚀 Possible Extensions
NLP-based skill extraction (e.g., top mentioned tools: SQL, Python, Excel)

Resume or cover letter generator based on job descriptions

Trend analysis (by posting date or job type)

