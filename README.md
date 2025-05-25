### Final Project: Survey-Based Income and Expense Analysis Web App ###

## Overview

This project is a full-stack data analytics solution built with Flask, MongoDB, Python, and Render to collect, store, analyze, and visualize user income and expense data. The project is designed to support a healthcare product launch by understanding spending patterns across demographics.

## Features

-  A Flask web app to collect survey data.
-  A MongoDB database to store age, gender, income, and categorized expenses.
-  A Python data processing pipeline to export data to CSV.
- Visual analytics with charts for:
  - Ages with the highest average income
  - Gender-wise spending patterns
- Deployed on Render.com

## 📂 Project Structure

Final-Project/
├── app.py                     # Flask web app
├── requirements.txt           # Python dependencies
├── survey_export.py           # Python class for exporting data from MongoDB
├── Data Analysis Notebook for Final Project.ipynb      # Jupyter notebook for analysis & visualization
├── templates/
│   └── form.html              # HTML survey form
├── survey_data.csv            # Exported CSV (after running survey_export.py)
├── top_10_income_by_age.png   # Exported chart
└── gender_expense_distribution.png   # Exported chart

## How to Run the App Locally

## 1. Clone the Repo

## 2. Create a Virtual Environment and Activate It

## 3. Install Requirements

## 4. Start MongoDB
Ensure MongoDB is installed and running:

## 5. Run the Flask App
Visit: [http://127.0.0.1:5000](http://127.0.0.1:5000)

## Data Export & Analysis

## 1. Export Survey Responses
After collecting submissions, run:
"python survey_export.py"
This will export `survey_data.csv`.

### 2. Run Analysis
Open "Data Analysis Notebook for Final Project.ipynb" in Jupyter Notebook to:
- Clean and structure the dataset
- Analyze income by age
- Compare expenses by gender
- Export charts for presentation

## Visualizations

1. Ages with Highest Average Income
![Income by Age](top_10_income_by_age.png)

2. Gender-wise Spending Patterns
![Gender Spending](gender_expense_distribution.png)

## Deployment

The application is deployed on Render.com with the following settings:

- Build Command: "pip install -r requirements.txt"
- Start Command: "gunicorn app:app"

Live URL: https://final-project-bta7.onrender.com

## Tech Stack

- Python (Flask, Pandas, Matplotlib, Seaborn)
- MongoDB (pymongo)
- Render (deployment)
- Jupyter Notebook

## Author

- Name: Kayode Emeka Oladele
- GitHub: [Olkae17](https://github.com/Olkae17)

## Status
Project Completed — Deployed, Functional, and Ready for Review.
