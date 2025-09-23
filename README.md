📊 CORD-19 Data Explorer (Sample Project)
This project is a simplified analysis of the CORD-19 research dataset using Python and Streamlit.
It demonstrates the basic data science workflow: loading data, cleaning, analyzing, visualizing, and presenting results in an interactive web application.

🚀 Project Structure
metadata.csv → Sample dataset (COVID-19 research papers metadata)
app.py → Streamlit application
analysis.py (optional) → Script/Jupyter notebook for exploratory analysis
🛠 Tools Used
Python 3.7+
pandas → data loading & manipulation
matplotlib & seaborn → visualizations
streamlit → interactive web app
📂 Workflow
Data Loading

Load metadata.csv into a Pandas DataFrame
Convert publish_time into datetime
Extract publication year
Data Cleaning

Handle missing values
Create derived columns like year
Data Analysis

Count papers per year
Identify top publishing journals
Show publications by source
Preview a sample of the data
Visualization

Publications over time (bar chart)
Top journals (horizontal bar chart)
Publications by source (pie chart)
Streamlit App

Sidebar filters for year and journal
Interactive visualizations
Data preview
