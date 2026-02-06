# 🇯🇵 Japanese Students' Mental Health Analysis

![SQL](https://img.shields.io/badge/Language-SQL-blue)
![Tool](https://img.shields.io/badge/Tool-Quarto-green)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📄 Overview
This project is an **end-to-end SQL analysis** of mental health trends among international and domestic students in Japan. 

Using a dataset of ~268 records, I explored the impact of **length of stay**, **language proficiency**, and **social connectedness** on depression and acculturative stress. The final report identifies key risk factors and provides data-driven recommendations for student support systems.

> **Note:** This project acts as an independent replication of the study found in [https://www.mdpi.com/518772]. The queries and code implementation are original.

## ❓ Key Questions Analyzed
1.  **Culture Shock Curve:** How does the length of stay (in years) impact mental health scores?
2.  **Isolation:** Does higher social connectedness lead to lower depression scores?
3.  **Demographics:** Are specific groups (Gender/Academic Level) more at risk?
4.  **Language Barrier:** Is there a correlation between Japanese proficiency and social integration?

## 🛠️ Tech Stack
* **SQL (PostgreSQL Dialect):** Data cleaning, aggregation, `CASE` statements, subqueries, and window functions.
* **Quarto (R):** For reproducible reporting and weaving SQL queries with narrative.
* **Data Analysis:** Exploratory Data Analysis (EDA) and Logic Validation.

## 📂 Project Structure
```text
├── data/
│   └── students.csv        # Raw dataset
├── analysis/
│   └── studenthealth.qmd   # Main Quarto analysis file
├── docs/                   # Generated HTML report (for GitHub Pages)
└── README.md               # Project documentation

