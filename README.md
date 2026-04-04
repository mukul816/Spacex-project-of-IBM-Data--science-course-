# 🚀 SpaceX Falcon 9 Landing Prediction
# IBM Data Science Capstone Project
# 📌 Project Overview

This project is part of the IBM Data Science Professional Certificate. The goal is to analyze SpaceX Falcon 9 launch data and build machine learning models to predict whether the first stage will land successfully.

SpaceX reduces launch costs by reusing rocket boosters. By predicting landing success, we can estimate launch costs and help competing companies make better business decisions.

# 🎯 Business Problem

SpaceX launches cost around $62 million, while competitors may charge over $165 million. The key reason is reusability of the first stage.

If we can predict landing success:

We can estimate launch costs
Help competitors bid effectively
Improve decision-making using data
# Objectives
Collect SpaceX launch data using API & web scraping
Perform data cleaning and preprocessing
Conduct exploratory data analysis (EDA)
Build interactive visualizations
Develop machine learning models for prediction
Evaluate model performance
# Technologies Used
Python
Pandas, NumPy
Matplotlib, Seaborn
Plotly Dash (Dashboard)
Folium (Maps Visualization)
Scikit-learn (ML Models)
SQL (EDA Analysis)
Jupyter Notebook
# Project Structure
├── Data Collection API.ipynb

├── Data Collection with Web Scraping.ipynb

├── Data Wrangling.ipynb

├── EDA with Data Visualization.ipynb

├── EDA with SQL.ipynb

├── Interactive Visual Analytics with Folium.ipynb

├── Machine Learning Prediction.ipynb

├── app.py (Dashboard)


├── dataset_part_1.csv

├── dataset_part_2.csv

├── dataset_part_3.csv

├── spacex_web_scraped.csv

└── README.md

# Project Workflow
1.Data Collection
SpaceX REST API
Web scraping (Wikipedia)
2️⃣ Data Wrangling
Handling missing values
Feature engineering
Data cleaning
3️⃣ Exploratory Data Analysis (EDA)
Launch success trends
Payload vs success rate
Launch site analysis
SQL-based insights
4️⃣ Data Visualization
Interactive plots
Geographic maps using Folium
5️⃣ Machine Learning

# Models used:

Logistic Regression
Decision Tree
Support Vector Machine
KNN
Hyperparameter tuning using GridSearchCV
Model evaluation using accuracy score
# Key Insights
Launch success rate improves over time
Certain launch sites have higher success rates
Payload mass affects landing success
Machine learning models can effectively predict landing outcomes
# Results
Built classification models for predicting landing success
Compared multiple models to find best performance
Developed interactive dashboard for visualization
# Dashboard

Interactive dashboard built using Plotly Dash to visualize:

Launch success rates
Payload vs success
Launch site comparisons
      This above you can see by open this link:https://github.com/mukul816/Spacex-project-of-IBM-Data--science-course-/blob/main/Data%20sciene%20capstone%20complete%20project.pdf
      also can  visualize by run dashboard given 
# How to Run the Project
Clone the repository
git clone https://github.com/mukul816/Spacex-project-of-IBM-Data--science-course-
Install dependencies
pip install -r requirements.txt
Run notebooks in Jupyter
Run dashboard
python app.py
# Future Improvements
Use advanced ML models (XGBoost, Random Forest)
Deploy dashboard online
Improve feature engineering
Use real-time data integration
# Author

Mukul Girdhar

🎓 Master’s in Economics
📊 Data Science Enthusiast
💻 Skills: Python, SQL, Machine Learning, Data Visualization
