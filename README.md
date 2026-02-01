**AI-Based Resume Screening System**


📌 Project Overview

This project builds a data-driven resume screening system that helps recruiters shortlist candidates efficiently using data analytics and machine learning.

The system analyzes candidate skills, experience, certifications, and project history to predict whether a candidate is likely to be hired.

🎯 Objective

To automate and improve resume screening by:

Cleaning and preparing candidate data

Extracting useful features from resumes

Applying SQL-based filtering

Using machine learning to predict hiring decisions

Visualizing insights using Power BI

❗ Problem Statement

Manual resume screening is time-consuming and subjective. Recruiters must review large numbers of resumes to find suitable candidates.

This project aims to:

Reduce manual effort

Improve candidate shortlisting efficiency

Use data-driven decision-making for hiring

🛠 Tech Stack

Python

Pandas & NumPy

SQL

Machine Learning (Scikit-learn)

Power BI

Excel

Jupyter Notebook

📂 Project Structure
Data Files

resumes.csv → Original dataset

cleaned_resumes.csv → Cleaned data after removing null values

feature_engineered_resumes.csv → Dataset with engineered features

resumes_with_predictions.csv → Final dataset including ML predictions

Notebooks

data_cleaning.ipynb → Handles missing values and prepares data

feature_engineering.ipynb → Creates skill and experience features

ML_model.ipynb → ML training, evaluation, and predictions

⚙ Steps Performed
1. Data Cleaning

Handled missing values

Standardized columns

Saved clean dataset

2. Feature Engineering

Extracted skills into binary features

Converted experience into numeric levels

Prepared data for ML models

3. SQL Analysis

Queried candidates based on skills and experience

Identified top candidate profiles

4. Machine Learning Model

Used:

Logistic Regression

Random Forest Classifier

Model predicts whether a candidate is likely to be hired.

Model accuracy achieved:
~95–96%

5. Power BI Dashboard

Dashboard shows:

Predicted hires vs rejects

Experience distribution

Top candidates

Hiring insights

📊 Key Insights

Candidates with Python, ML, and SQL skills have higher hire probability.

Experience level significantly influences hiring.

Candidates with more projects have better selection chances.

🚀 Outcome

Built an end-to-end pipeline for resume screening using analytics and ML, improving hiring decision efficiency.

🔮 Future Improvements

NLP-based resume parsing

Skill extraction automation

Real-time recruitment dashboard

👤 Author

Priya Gaikwad
