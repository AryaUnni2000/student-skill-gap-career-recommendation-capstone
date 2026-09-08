# Data Sources

This project integrates multiple public and project-generated datasets for career recommendation, skill-gap analysis, labour-market analytics, and explainable AI.

## 1. Government of Canada Job Bank
Used for:
- Job postings
- Advertised vacancies
- Province/territory coverage
- Canadian labour-market demand scoring

Dataset used:
- job_bank-open-data-all-job-postings-june-2026.csv

Note:
The original raw Job Bank file is not stored in this repository because of GitHub file-size limitations. The project uses a processed version for analysis.

## 2. O*NET Database
Used for:
- Occupational skills
- Skill importance and level
- Tasks
- Knowledge
- Abilities
- Work activities
- Software skills
- Education-related occupational information

Relevant files include:
- occupation_data.csv
- essential_skills.csv
- task_statements.csv
- task_ratings.csv
- knowledge.csv
- abilities.csv
- work_activities.csv
- software_skills.csv
- education.csv
- scales_reference.csv

## 3. Classification of Instructional Programs (CIP)
Used for:
- Educational program classification
- Education-to-career alignment

Dataset:
- CIPCode2020.csv

## 4. Processed Project Data
Processed datasets were created during the analytical workflow after:
- Cleaning
- Deduplication
- Standardization
- Occupational mapping
- Education mapping
- Dataset integration

Example:
- job_bank_preliminary_clean.csv

## 5. Occupational Crosswalks
Crosswalks were used to align occupational and educational classifications across:
- NOC
- SOC
- O*NET
- CIP

These mappings supported integration between Canadian labour-market data, U.S. occupational skill data, and education pathways.
