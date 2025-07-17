Hospital Patient Diagnosis and Health Risk Analysis System
This SQL project focuses on analyzing patient health data for risk classification based on common diagnostic metrics like blood pressure, sugar levels, and heart rate. It is designed for healthcare data analysis, suitable for freshers and aspiring data analysts.

📌 Project Overview
This project simulates a hospital system with two core entities:

patients: Basic patient demographic details.

diagnoses: Medical metrics like BP, sugar, and heart rate recorded per patient.

It enables SQL-based classification of health risks such as:

Blood pressure status

Sugar level status

Age group distribution

Overall health risk (based on multiple conditions)

🗄️ Database Schema
Database: hospital_analysis

1. patients
Column	Type
patient_id	INT (PK)
patient_name	VARCHAR(100)
age	INT
gender	ENUM
city	VARCHAR(50)

2. diagnoses
Column	Type
diagnosis_id	INT (PK, AI)
patient_id	INT (FK)
recorded_date	DATE
bp_systolic	INT
bp_diastolic	INT
sugar_level	INT
heart_rate	INT

📊 Analysis Queries
✅ 1. Blood Pressure Classification
Classify as Normal, Elevated, High BP, or Unknown using systolic and diastolic values.

✅ 2. Age Group Classification
Categorize patients as Young, Middle-aged, or Senior based on age.

✅ 3. Sugar Level Risk
Label patients as Normal, Pre-Diabetes, or Diabetic.

✅ 4. Overall Health Risk
Final risk label as High Risk, Medium Risk, or Low Risk based on:

Systolic BP ≥ 140

Sugar level ≥ 180

Heart rate > 100

🧪 Sample Data
Includes 4 patients with mock diagnosis entries to illustrate the logic.

🎯 Skills Demonstrated
SQL JOINs and CASE statements

Health data classification

Analytical logic for healthcare KPIs

Structured query writing for data-driven decisions

📂 How to Run
Copy the SQL script to your MySQL/MariaDB environment.

Run the commands step-by-step:

Create database and tables

Insert sample data

Run analysis queries

📚 Use Cases
Healthcare Analytics Projects

SQL Interview Practice

Data Analysis Portfolio

Real-time health risk classification logic

