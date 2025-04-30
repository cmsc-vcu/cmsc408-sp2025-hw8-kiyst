# Homework 8 - World Bank Data Analysis 🌍

## Overview

This project is part of CMSC 408 and focuses on using SQL for real-world data analysis with the World Bank’s country dataset. We used SQL to explore, clean, and extract insights from the `wdi_country` table, including:

- Filtering out non-country entities (Task 3)
- Creating a clean table of valid countries (Task 4)
- Counting countries by region and income (Tasks 6–7)
- Investigating anomalies like missing income groups (Tasks 12–13)
- Building cross-tab and percentage breakdowns (Tasks 15, 19, 20)
- Identifying missing data combinations (Task 18)

If it sounds like SQL boot camp—you're not wrong. But we came out stronger (and more relational).

---

## Structure

- **`report.qmd`**: Contains all task queries and output, formatted using Quarto.
- **SQL Tasks 1–20**: Sequential exercises that build upon one another to refine and analyze the dataset.
- **Reflection Section**: A short write-up on what was learned, problem-solving methods, and SQL confidence levels.
- **README (this file)**: Summary of the project, goals, and what’s inside.

---

## Technologies Used

- SQL (MySQL-flavored)
- Python + Quarto (`run_sql_and_return_html`, `execute_ddl`)
- phpMyAdmin (for schema inspection)
- Pandas (CSV backup parsing during development)