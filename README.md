# 📊 Data Analysis & Visualization Projects

Welcome to my data science portfolio! This repository showcases a comprehensive series of data analysis and visualization projects. The primary objective is to demonstrate practical proficiency in Python's core data science ecosystem, specifically utilizing **NumPy**, **Pandas**, and **Matplotlib**.

---

## 📁 Repository Structure

    data-analysis-projects/
    │
    ├── 🛍️ project1_online_sales/
    │   ├── online_sales_analysis.ipynb
    │   └── data/
    │       └── Online_Sales_Data.csv
    │
    ├── 🌤️ project2_weather/
    │   └── weather_analysis.ipynb
    │
    └── 📱 project3_google_play/
        └── googleplay_analysis.ipynb

---

## 🛍️ Project 1: Online Sales Analysis

**Objective:** Clean and analyze real-world online sales data to discover hidden trends and identify top-performing products.

**Key Deliverables & Steps:**

- **Data Cleaning:** Handled missing values and preprocessed date formats.
- **Statistical Analysis:** Computed the mean and standard deviation of total sales.
- **Product Insights:** Identified the top 10 best-selling products based on quantity.
- **Data Visualization:** Built interactive and clean monthly sales trend charts.

---

## 🌤️ Project 2: Weather Data Analysis

**Objective:** Analyze historical weather records from Toronto to explore temperature patterns, wind speeds, and precipitation trends.

**Key Deliverables & Steps:**

- **Time-Series Setup:** Implemented a DatetimeIndex for efficient and advanced time slicing.
- **Descriptive Statistics:** Extracted mean temperatures, maximum wind speeds, and identified the hottest/most humid days.
- **Feature Engineering:** Created a custom binary Precipitation feature by parsing textual weather descriptions.
- **Advanced Visualization:** Designed a Dual-Axis Plot overlaying hourly temperature lines with precipitation bars for January 2012.

---

## 📱 Project 3: Google Play Store Apps Analysis

**Objective:** Clean and filter a dataset of 10,000+ applications to uncover the most popular genres among high-rated apps.

**Key Deliverables & Steps:**

- **Data Preprocessing:** Dropped incomplete entries in critical columns (Rating, Installs, Genres).
- **Data Transformation:** Cleaned string representations of install counts (removing `+` and `,`) and converted them to numerical types.
- **Filtering:** Isolated top-tier applications with a rating of 4.0 or higher.
- **Aggregation & Plotting:** Grouped data by genre and visualized the top 10 most installed genres using a tailored bar chart.

---

## 🛠️ Tech Stack & Ecosystem

- **Language:** Python 3.x
- **Data Manipulation:** Pandas, NumPy
- **Data Visualization:** Matplotlib

---

## 💻 How to Run & Explore

1. **Clone the Repository:**

        git clone https://github.com/Arian11z/data-analysis-projects.git

2. **Navigate to the project:**

        cd data-analysis-projects

3. Open any `.ipynb` file using Jupyter Notebook, VS Code, or Google Colab to inspect the code and generated plots.
