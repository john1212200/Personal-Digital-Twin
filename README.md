# Personal-Digital-Twin
A Data Engineering Platform for Personal Behavior Analytics and What-if Simulation 

---

##  About the Project
The **Personal Digital Twin** is a data engineering project designed to create a digital representation of an individual's daily habits, activities, and behavioral patterns.
The system collects personal lifestyle data—such as sleep duration, study hours, physical activity, screen time, task completion, and daily productivity—and transforms it into structured,
meaningful information that can be used for analysis, visualization, and exploratory prediction.

---

##  Main Features
* **Personal Data Collection:** Collects daily routine data (sleep, study, physical activity, screen time, and tasks) manually or via CSV files.
* **Data Cleaning & Validation:** Identifies duplicate records, invalid numerical values, missing fields, and inconsistent formats before storage.
* **ETL Pipeline:** Implements a structured pipeline handling Extraction, Transformation, and Loading of records.
* **Relational Database Storage:** Organizes historical data efficiently using a relational database schema.
* **Interactive Dashboard:** Visualizes key performance indicators and weekly/daily averages using Streamlit and Plotly.
* **What-if Scenario Simulation:** Allows users to explore hypothetical routine changes (like an extra hour of sleep) and compare them against historical baselines.

---

## Proposed Technologies
* **Python:** For data processing, ETL development, validation, and analytics.
* **Pandas:** For reading CSV files, cleaning data, and transforming records.
* **SQL & PostgreSQL/MySQL:** For relational data storage and querying.
* **Streamlit & Plotly:** For building the interactive analytics dashboard.
* **Git & GitHub:** For version control and project documentation.

---

## Project Architecture & Data Flow
Raw Data (CSV / Manual) 
   ↓
Data Ingestion 
   ↓
ETL Pipeline & Data Validation 
   ↓
Relational Database Storage 
   ↓
Analytics & Metrics Calculation 
   ↓
Dashboard Visualization & What-if Scenario Analysis

---

## Key Analytical Metrics
* **Average Study Duration:** Average study hours recorded per day.
* **Average Sleep Duration:** Average sleep duration over a selected period.
* **Task Completion Rate:** Completed tasks divided by planned tasks (multiplied by 100).
* **Daily Screen Time:** Total recorded screen time for a selected day.
* **Routine Consistency & Productivity Trend:** Tracking habit regularity and self-reported productivity over time.

---

## Project Team
* Ahmed Mohamed Khalaf
* Ahmed Mohamed Shehata
* Badr Mostafa
* John Samy Hanna
* Mariam Essam
* Ayat Khalaf
