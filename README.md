# Synthetic_Hospital_Data-Analysis

## 1. Problem Definition

Healthcare systems generate large volumes of patient and encounter data. However, this data is often fragmented across multiple tables and difficult to translate into actionable insights for decision-making.

A single patient may be associated with multiple encounters, each with different types, durations, and costs. This one-to-many relationship complicates cost analysis, resource planning, and the identification of high-impact areas within the healthcare system.

**Project Objective**

- To analyse patient utilisation patterns and healthcare costs by integrating patient-level and encounter-level data
- To identify cost concentration areas and utilisation trends that can support operational and policy-level decision-making

## 2. Data and Tools

### Dataset

- Synthetic healthcare dataset designed to replicate real-world healthcare data structures
- Key tables include:
    - Patients
    - Encounters
    - Conditions
    - Procedures
    - Cost and billing information

Synthetic data was used to enable realistic analysis while avoiding privacy and ethical concerns associated with real patient records.
[Basic Setup and Running](https://github.com/synthetichealth/synthea/wiki/Basic-Setup-and-Running)

### Tools and Technologies

- Python (Pandas, Matplotlib)
- Power BI (data visualisation and dashboarding)
- Jupyter Notebook

## 3. Data Engineering and Preparation

The project involved data preparation to transform raw tables into analysis-ready datasets.

Key steps included:

- Cleaning and validating multiple relational tables
- Resolving one-to-many relationships between patients and encounters
- Handling missing values and ensuring consistent data types
- Verifying cost units and identifying discrepancies between analytical tools

During this process, differences between Python-based calculations and Power BI aggregations were identified and investigated, highlighting the importance of data validation and unit consistency in real-world analytics workflows.

## 4. Analysis and Methodology

The analysis focused on descriptive and exploratory techniques to understand healthcare utilisation and cost distribution, rather than predictive modelling.

Key analyses included:

- Total and average healthcare costs by encounter type
- Patient-level encounter frequency analysis
- Identification of high-cost patient groups
- Visual comparison of utilisation and cost concentration across encounter categories

The methodology prioritised interpretability and relevance to decision-making contexts.

## 5. Results and Key Insights

The analysis revealed several important patterns:

- Inpatient and emergency encounters account for a disproportionate share of total healthcare costs
- A small proportion of patients contribute to a large share of overall expenditure
- Encounter type has a greater impact on total cost than visit frequency alone
- Structured data modelling is essential for generating meaningful insights from complex healthcare datasets

## 6. Visualisation and Dashboarding
<img width="2767" height="1600" alt="dashboard-2" src="https://github.com/user-attachments/assets/71fe76e1-ed67-4f16-86dd-bc57e2e7fb48" />
To complement the Python-based analysis, a Power BI dashboard was developed to present key findings in a clear and accessible format.

The dashboard provides:

- High-level cost summaries for stakeholders
- Visual comparisons of encounter types and cost distribution
- A decision-support view suitable for non-technical audiences
