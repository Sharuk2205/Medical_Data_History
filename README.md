#  SQL Project: Medical Data History

This project is focused on querying and analyzing a **hospital database** using SQL. The database includes patients, doctors, admissions, and province data, simulating real-world healthcare records. The project is ideal for practicing advanced SQL queries and improving data analysis skills.

---

##  Files Included

PRSQL-02-Medical Data History.sql – SQL queries solving various medical data problems

PRSQL-02 Medical_Data_History.docx – Problem statement describing each task

patients.csv – Contains patient demographic and health data

doctors.csv – Contains doctor profiles and specialties

admissions.csv – Admissions history and diagnosis

province_names.csv – Lookup table for province names

---

##  Project Objective

To apply SQL skills by solving 35 real-life healthcare data problems such as:

- Filtering patient data based on conditions (e.g., age, weight, diagnosis)
- Joining multiple tables (e.g., patient with admission and doctor info)
- Aggregating and grouping data (e.g., total admissions per city)
- Data transformation and conditional logic
- Creating temporary passwords and formatting output

---


> **Note:** For some queries, update the column name in the `admissions` table:
```sql
ALTER TABLE admissions CHANGE COLUMN attending_doctor_id doctor_id INT;
