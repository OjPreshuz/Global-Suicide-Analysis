# 🌍 Global Suicide Rate Analysis (1985–2016)

This project explores global suicide trends using Python, pandas, and data visualization libraries like Matplotlib and Seaborn. It is part of my data analysis learning journey and contributes to my growing portfolio for data science and machine learning roles.

---

## 🎯 Project Motivation

- Understand suicide trends across age, gender, and countries.
- Apply Python skills (pandas, NumPy, visualization) to real-world data.
- Build a project that can be shared on GitHub, LinkedIn, and used for job/internship applications.
- Practice end-to-end exploratory data analysis (EDA).

---

## 📦 Dataset

- **Source**: [WHO Suicide Statistics (Kaggle)](https://www.kaggle.com/datasets/szamil/who-suicide-statistics)
- **Rows**: 27,820
- **Columns**: 12
- **Years Covered**: 1985 to 2016
- **Features**:
  - `country`, `year`, `sex`, `age`, `suicides_no`, `population`
  - `suicides/100k pop`, `country-year`, `HDI for year`, `gdp_for_year ($)`, `gdp_per_capita ($)`, `generation`

---

## 🧹 Data Cleaning Process

- Dropped columns with too many missing values (`HDI for year`, `country-year`)
- Renamed and standardized column names
- Converted `year` to `datetime` for plotting
- Added calculated column for **suicide rate per 100k population**:


## 📈 Exploratory Visualizations
1. Global Suicide Trend Over Time
Shows the average suicide rate trend globally between 1985 and 2016.
📍 Insight: Rates peaked in the 1990s and slightly declined after the early 2000s.

2. Suicide Rate by Gender
Compares the suicide rate for males and females over time.
📍 Insight: Males have significantly higher suicide rates across all years.

3. Suicide Rate by Age Group
Displays which age groups experience the highest suicide rates.
📍 Insight: Older adults (75+) show the highest vulnerability.

4. Suicide Rate by Generation
Explores generational patterns and trends.

5. Barchat: Top 20 Countries by Average Suicide Rate
Visualizes suicide rates over time for countries with the highest averages.
📍 Insight: Countries like Lithuania, Russia, and South Korea consistently appeared at the top.

---

## 🔍 Summary of Insights
Gender: Males have 3–5x higher suicide rates than females globally.

Age: People aged 75+ show the highest suicide rates.

Countries: A few countries consistently lead in average suicide rates.

Economic: Suicide trends sometimes correlate with GDP and other indicators.

---

## 🛠️ Tools Used
Python 3.10+

pandas & NumPy for data wrangling

Matplotlib & Seaborn for plotting

Jupyter Notebook

GitHub for version control and documentation

---

## ✅ Key Skills Demonstrated
1. Exploratory data analysis (EDA)

2. Handling and cleaning real-world datasets

3. Visualization and storytelling with data

4. Preparing a GitHub portfolio-ready project

---

## 📘 Credits
Data: https://www.kaggle.com/datasets/russellyates88/suicide-rates-overview-1985-to-2016 (Kaggle)

Author: Ojie Precious







