🏥 Epic-Style EHR Analytics Pipeline Using MIMIC-IV Demo

Simulating Epic Clarity Workflows with Publicly Available ICU Data

📌 Overview

This project recreates core Epic EHR analytics workflows using the MIMIC-IV Demo dataset.
Although real Epic data is protected under HIPAA, this pipeline simulates:

Patient → Encounter → Diagnosis → Labs → Medications data flow

SQL joins similar to Epic Clarity tables

Clinical feature engineering

Readmission risk modeling

Power BI / Tableau dashboards

GenAI extensions for risk explanations and natural-language SQL

The goal is to practice realistic EHR analytics workflows and build strong interview-ready experience for healthcare data roles.

🧩 Project Components

MIMIC-IV Demo dataset (100 fully de-identified patients)

SQL pipelines recreating patient-level encounter data

Python notebooks for cleaning, modeling, and visualization

Machine learning model predicting 30-day readmission

Dashboard summarizing patient outcomes

GenAI agents for clinical reasoning and NLQ → SQL

⚙️ Data Model (Epic-Inspired)

PATIENT table

HOSPITAL_ENCOUNTERS

ICU_STAYS

DIAGNOSES_ICD

LAB_EVENTS

PRESCRIPTIONS

These mimic Epic Clarity tables and allow realistic clinical analytics workflows.

📊 Dashboard Output

Readmission Rate Overview

LOS Trends

Diagnosis Distribution

High-Risk Patient Identification

Key Clinical Indicators

🔮 GenAI Extensions

Risk Explainer Agent:
Explains readmission risk in simple clinical language.

NLQ SQL Agent:
Converts natural language prompts into SQL queries.

🎯 Why This Project Matters

Healthcare analysts rarely get access to real EHR data before joining a hospital.
This project bridges that gap by providing:

Hands-on experience with EHR-style relationships

SQL joins similar to Epic Clarity

Realistic clinical analytics

Machine learning in a healthcare context

A 2025-ready hybrid of analytics + GenAI
