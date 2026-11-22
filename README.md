# Medical Data History Analysis

**DataMites capstone project | MySQL**

## Problem Statement
Solve 34 problem queries on a hospital database (patients, admissions and doctors) to retrieve, summarise and clean patient data.

## Dataset
Practice medical history database provided by DataMites: 9,637 records across linked patients, admissions, doctors and province tables.

## Sample Queries and Results

**Patients with their province names (JOIN)**

![Province join](Medical_Analysis_Screenshot(1).png)

**Epilepsy patients treated by a doctor named Lisa (3-table JOIN)**

![Three table join](Medical_Analysis_Screenshot(2).png)

## Project Steps
1. Connected to the database and wrote queries using SELECT, WHERE filtering, string functions and date functions.
2. Used aggregate functions with GROUP BY and HAVING for counts, totals and groupings.
3. Used JOINs across the patient, admission and doctor tables.
4. Checked for missing data with IS NULL and prepared UPDATE logic to replace missing allergy values with "NKA" (No Known Allergies).

## What the Queries Cover
- Patient counts by city
- Most common allergies
- Patients admitted repeatedly for the same diagnosis
- Admissions by day of month
- Weight groups and an obesity flag
- Replacing missing allergy values with "NKA"

## Business Impact
Complete, consistent patient records make reporting and lookups across patients, admissions and doctors more reliable.

## Files
- `Medical_Data_Queries.sql`: all 34 queries
- `query_screenshot.png`: sample queries and results

## Tools
MySQL

## Author
Peddabandi Sreelekha | [LinkedIn](https://www.linkedin.com/in/peddabandisreelekha)
