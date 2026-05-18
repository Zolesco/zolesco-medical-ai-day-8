# Zolesco Solutions — Medical AI 90-Day Journey: Day 8

Welcome to **Day 8** of Zolesco Solutions’ 90-day journey into Medical AI. As a team, we are building full-stack, practical AI and HealthTech solutions, learning together, and sharing insights publicly to document our progress.

---

## **Objective — Day 8**

Today we focused on **SQL and clinical datasets**:

- Understanding structured clinical data in hospitals  
- Extracting patient cohorts based on **risk factors and lab results**  
- Cleaning, structuring, and documenting patient data  
- Preparing for cohort queries and downstream ML workflows

---

## **Dataset**

We created a CSV file (`patients_day8.csv`) with **30 realistic patient records**. Each row includes:

| Column | Description |
|--------|-------------|
| id | Unique patient ID |
| name | Patient name |
| age | Age in years |
| gender | Male/Female |
| cholesterol | Cholesterol level (mg/dL) |
| blood_pressure | Blood pressure (systolic/diastolic) |
| diabetes | TRUE/FALSE |
| heart_disease | TRUE/FALSE |
| smoker | TRUE/FALSE |
| last_visit | Date of last clinical visit |
| risk_score | Calculated risk score (example) |
| notes | Free text notes / observations |

This dataset allows us to practice SQL operations like:

- SELECT, WHERE, GROUP BY, ORDER BY, LIMIT  
- Filtering for high-risk patients  
- Aggregating statistics by condition or demographic  
- Preparing structured data for ML pipelines  

---
