# Hospital Patient EDA using Databricks & PySpark

##  Project Overview
This mini project performs **Exploratory Data Analysis (EDA)** on hospital patient data using **Databricks** and **PySpark**.  
The goal is to understand key patterns in hospital admissions, test results, and billing through simple yet powerful data exploration steps.

---

## Objectives
- Load and inspect hospital data using PySpark in Databricks  
- Explore schema, data types, and basic statistics  
- Perform categorical and numerical analysis  
- Analyze relationships between test results and admission types  
- Visualize distributions of patient data  

---

## Dataset Information

| Column Name | Description |
|--------------|-------------|
| **Name** | Patient’s name |
| **Age** | Patient’s age |
| **Blood Type** | Blood group (A, B, AB, O) |
| **Doctor** | Consulting doctor |
| **Admission Type** | Type of admission (Emergency, Elective, Urgent) |
| **Medication** | Prescribed medicine |
| **Insurance Provider** | Patient’s insurance company |
| **Admission Date** | Date of hospital admission |
| **Discharge Date** | Date of discharge |
| **Billing Amount** | Total bill for patient |
| **Test Result** | Result of medical tests (Normal, Abnormal, Inconclusive) |

---

## Steps Performed

###  Load and Inspect Data
df = spark.read.option('header',True).option('inferSchema',True).csv('/Volumes/workspace/default/practice/spark.csv')
df.show(10)

## Authour
Thiyagesh R S 
thiya2332@gmail.com 


