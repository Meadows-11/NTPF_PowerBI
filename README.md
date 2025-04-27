# NTPF_PowerBI [ National Treatment Purchase Fund ] source data taken from "https://www.ntpf.ie/home/home.htm"
OVERALL OBJECTIVES
1. Track current status of patient waiting list
2. Analyze historical monthly trend of waiting list in Inpatient & Outpatient categories 3. Detailed specialty level & age profile analysis.
Data Scope: 2018-2021
Metrics Required -  1. Average & Median Waiting List, 2. Current Total Wait List
Views Required- 1. Summary Page, 2. Detailed Page for Granular Analysis

The data is primarily divided into Inpatients & Outpatients excels. In this project this segmented data is appended into a single table to get wholistic view and oversight on it's elements and to get the data ready for visualization. Glosary for some terms used in the dataset -
Inpatients : Patients who are admited in hospital while undergoing medical treatment.
Outpatitents: Patients who are not admited in hospital while undergoing medical treatment.
Case Type: Inpatients are those who are admitted for more than 1 day & Day Cases are those are there for 1 day and got dischardged on the same day.
Specialty_HIPE - The code used to identify the medical specialty, as per the HIPE (Hospital In-Patient Enquiry) system.
Time Bands - indicates how long a patient has been on a waitlist on a given date.

The data had empty spaces, null values, objects in the values, changed data type and had to replace some values to make the data ready for visual building. Used a couple of DAX functions to bring more utility to the project namely # AVERAGE, MEDIAN, SWITCH, VALUES, IF, ISBLANK, SUM, CALCULATE, EDATE and MAX.
