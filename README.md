# Data Analysis & Visualization Projects

This repository contains a series of data analysis and visualization projects designed to practice and demonstrate proficiency in Python's data science ecosystem, specifically using **NumPy**, **Pandas**, and **Matplotlib**.

---

## 📁 Repository Structure

```text
data-analysis-projects/
│
├── project1_online_sales/
│   ├── online_sales_analysis.ipynb
│   └── data/
│       └── Online_Sales_Data.csv
│
├── project2_weather/
│   └── weather_analysis.ipynb
│
├── project3_google_play/
│   └── googleplay_analysis.ipynb
│
├── .gitignore
└── README.md
📊 Projects Overview
🛍️ Project 1: Online Sales Analysis
Objective: Clean and analyze a real-world online sales dataset to discover trends and identify top-performing products.

Key Steps:

Handled missing values and preprocessed date formats.

Computed mean and standard deviation of total sales.

Identified the top 10 best-selling products.

Visualized monthly sales trends and product performance using bar charts.

🌤️ Project 2: Weather Data Analysis
Objective: Analyze one year of historical weather data (Toronto) to explore temperature patterns, wind speeds, and precipitation trends.

Key Steps:

Set a Datetime index for advanced time-series slicing.

Extracted descriptive statistics (mean temperature, max wind speed, hottest/most humid days).

Created a custom precipitation feature by scanning textual weather descriptions.

Built an advanced Dual-Axis plot overlaying hourly temperature line charts with rainfall bar charts for January 2012.

📱 Project 3: Google Play Store Apps Analysis
Objective: Clean a dataset of over 10,000 apps to identify the most popular genres among high-rated applications.

Key Steps:

Dropped missing entries in critical columns (Rating, Installs, Genres).

Processed string representations of install counts (removing + and ,) and converted them to pure numeric values.

Filtered applications with ratings of 4.0 or higher.

Grouped data by genre and visualized the top 10 most installed genres using a clean bar plot.

🛠️ Tech Stack & Libraries
Language: Python 3

Libraries: Pandas, NumPy, Matplotlib

🚀 How to Run
Clone this repository:

Bash
   git clone [https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git)
Navigate to the project directory and open any Jupyter Notebook using VS Code, JupyterLab, or Google Colab.