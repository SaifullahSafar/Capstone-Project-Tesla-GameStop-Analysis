# 🚀 Capstone Project: Predicting Falcon 9 First Stage Landing Success

## 🧩 Project Overview

This capstone project is part of the IBM Data Science Professional Certificate. The focus of this project is to analyze the historical launch data of SpaceX’s Falcon 9 rockets and predict whether the **first stage** of the rocket will successfully **land and be reusable**.

Throughout this project, I applied the complete data science workflow including data collection, data wrangling, exploratory data analysis (EDA), SQL-based querying, classification modeling, and building an interactive dashboard with Plotly Dash.

---

## 🔍 Problem Statement

How can we use historical Falcon 9 launch data to determine the key factors influencing successful landings and develop a model to **predict landing outcomes**?

---

## 🧠 Key Tasks and Techniques

- ✅ **Data Collection & Wrangling**  
  Collected and cleaned SpaceX Falcon 9 launch data, handling nulls, types, and derived features like `landing_class`.

- ✅ **Exploratory Data Analysis (EDA)**  
  Used `Matplotlib`, `Seaborn`, and `Plotly` to analyze launch sites, landing types, orbit types, and success ratios.

- ✅ **SQL Queries**  
  Performed analytical queries on the launch dataset to extract meaningful insights using SQL via SQLite.

- ✅ **Geospatial Mapping (Folium)**  
  Created an interactive map displaying SpaceX launch sites and locations.

- ✅ **Predictive Modeling**  
  Built classification models (Logistic Regression, Decision Tree) to predict the probability of a successful landing.

- ✅ **Interactive Dashboard (Dash)**  
  Developed a live web-based dashboard using Plotly Dash to visualize and interact with launch success data.

---

## 📁 Project Structure

Capstone-Project-Falcon9-Landing-Prediction/
│
├── data/ # Cleaned data files
│   └── spacex_launch_data.csv
│
├── notebooks/ # Jupyter notebooks for each step
│   ├── 01_data_collection_and_wrangling.ipynb
│   ├── 02_eda_visualizations.ipynb
│   ├── 03_sql_analysis.ipynb
│   ├── 04_classification_model.ipynb
│   └── 05_dash_dashboard_code.ipynb
│
├── app/ # Dash app files
│   └── dash_app.py
│
├── images/ # Plots and screenshots
│   ├── folium_map.png
│   ├── dashboard_screenshot.png
│   └── model_results.png
│
├── outputs/ # Final presentation
│   └── final_presentation.pdf
│
└── README.md # This file
📊 Sample Visuals
📈 Launch success per site

🗺️ Folium map of launch locations

📉 Classification model performance (confusion matrix, accuracy)

📊 SQL-based orbit and landing outcome charts

📺 Dash dashboard screenshots

🚀 Tools and Libraries Used
Python (Pandas, NumPy, Matplotlib, Seaborn, Plotly, Dash, Folium)

Jupyter Notebooks

SQL (SQLite)

Scikit-learn (Logistic Regression, Decision Tree)

Git & GitHub

PowerPoint / Google Slides

📌 Key Outcomes
Cleaned and analyzed launch data from SpaceX Falcon 9 missions

Discovered key patterns in successful landings

Developed predictive models to classify landing success

Built a professional interactive dashboard for launch data visualization

Created a comprehensive data science report with presentation-ready visuals

👤 Author
Saifullah Safar
Data Scientist | Dashboard Designer  | Data Analyst

📧 saifullahsafar@gmail.com
🌐 LinkedIn | Portfolio | GitHub

🏁 Final Note
This project represents a real-world data science application using actual launch data from SpaceX. From raw data to predictive insight, it reflects the practical power of Python, data analysis, and machine learning.

"Data becomes powerful when it lands successfully—just like Falcon 9."
