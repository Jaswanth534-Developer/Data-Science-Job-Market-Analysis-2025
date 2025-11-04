# 🧠 Data Science Job Market Analysis 2025

A data-driven analysis of 944 job postings across the globe to uncover hiring trends, salary insights, and top in-demand skills in the data field using **Python, Pandas, Matplotlib, and Seaborn**.

---

## 📁 Project Overview

This project analyzes **real-world job market data** for Data Science roles (Data Scientist, Data Analyst, ML Engineer, etc.) collected in 2025.
The goal is to understand which **skills, locations, and companies** dominate the market and what factors influence demand.

---

## 🎯 Objectives

* Clean and preprocess raw job data
* Identify missing or inconsistent information
* Explore hiring trends by **role, region, and company**
* Analyze salary distribution and company insights
* Visualize **top skills** in demand for 2025

---

## 🧩 Tools & Libraries Used

* **Python 3**
* **Pandas** → data cleaning & manipulation
* **NumPy** → numerical operations
* **Matplotlib & Seaborn** → data visualization
* **WordCloud** → visual representation of top skills
* **Jupyter Notebook** → data analysis environment

---

## 🧹 Phase 1 – Data Understanding

* Loaded the dataset (`data_science_job_posts_2025.csv`)
* Checked dataset structure, column types, and missing values
* Cleaned redundant columns and formatted categorical values

---

## 🧼 Phase 2 – Data Cleaning

* Removed duplicate records and handled nulls using `fillna()` and `dropna()`
* Normalized text columns like location and job title
* Converted salary ranges to numeric values for analysis

---

## 📊 Phase 3 – Exploratory Data Analysis (EDA)

* Job distribution by **title**, **region**, and **company**
* Average salary by **role** and **region**
* Top 10 **industries** hiring data professionals
* Correlation between company size and salary

---

## 💡 Phase 4 – Skill Trends

* Extracted skills text column to analyze top keywords
* Created a **WordCloud** showing popular skills:

  > Python, SQL, Machine Learning, Power BI, Excel, Deep Learning

---

## 📈 Phase 5 – Visualization & Insights

* Created **bar plots**, **pie charts**, and **heatmaps** using Seaborn
* Visualized salary and location trends
* Key insights:

  * 85% of postings are **Data Scientist** roles
  * **Bengaluru, New York, Remote** are top hiring locations
  * **Python + SQL** remain the most demanded skills

---

## 📁 Project Files

| File                              | Description                |
| --------------------------------- | -------------------------- |
| `data_science_job_posts_2025.csv` | Raw dataset                |
| `data_analysis.ipynb`             | Main Jupyter notebook      |
| `cleaned_data.csv`                | Processed dataset          |
| `visualizations/`                 | Charts and plots generated |
| `README.md`                       | This documentation         |

---

## 🚀 How to Run This Project

1. Clone the repository

   ```bash
   git clone https://github.com/yourusername/data-science-job-analysis-2025.git
   ```
2. Navigate into the folder

   ```bash
   cd data-science-job-analysis-2025
   ```
3. Install required libraries

   ```bash
   pip install pandas numpy matplotlib seaborn wordcloud
   ```
4. Run the notebook in Jupyter

   ```bash
   jupyter notebook data_analysis.ipynb
   ```

---

## 🧭 Future Improvements

* Add time-based trend analysis (job postings over months)
* Use NLP to extract deeper skill relationships
* Build a Power BI dashboard for visual exploration

---

## ✍️ Author

**Jaswanth Reddy**
 Data Analyst Enthusiast
📧 [kjaswanthreddy534@gmail.com]


---
