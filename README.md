# 2017 U.S. Mortgage Lending Analysis | Tableau

## Project Overview

This project analyzes 2017 Home Mortgage Disclosure Act (HMDA) data to explore mortgage lending activity, application outcomes, denial rates, loan purposes, geographic lending patterns, and applicant income distributions across the United States.

Using **Tableau Public**, I developed interactive visualizations and a dashboard to identify patterns in mortgage applications and examine how lending outcomes vary across different geographic regions and applicant characteristics.

The goal of this project is to transform raw mortgage lending data into meaningful visual insights that can support data-driven decision-making in the financial services and banking industries.

## Business Objectives

The analysis focuses on answering the following business questions:

1. **Mortgage Application Outcomes:** What proportion of mortgage applications resulted in originated loans, denials, withdrawals, and other outcomes?
2. **Mortgage Denial Rates:** How do mortgage denial rates vary across different states?
3. **Geographic Lending Activity:** Which states experienced the highest volume of mortgage applications?
4. **Loan Purpose Analysis:** What were the most common purposes for mortgage applications?
5. **Applicant Income Analysis:** How does applicant income vary across mortgage applications, and how do outcomes differ across income groups?

## Dataset

**Source:** Consumer Financial Protection Bureau (CFPB) – Home Mortgage Disclosure Act (HMDA)

**Reporting Year:** 2017

**Dataset:** 2017 Nationwide Mortgage Loan Data

The dataset contains mortgage application records reported by financial institutions throughout the United States.

Some of the fields used in this analysis include:

| Field | Description |
|---|---|
| Action Taken | Identifies the outcome of a mortgage application |
| State Name | State associated with the reported mortgage application |
| Loan Purpose Name | Purpose of the mortgage application |
| Loan Type Name | Type of mortgage loan |
| Applicant Income 000S | Reported applicant income, in thousands of dollars |
| Applicant Ethnicity | Reported applicant ethnicity |
| Applicant Race 1 | Reported applicant race |
| Applicant Sex | Reported applicant sex |
| Application Count | Record count used for aggregate analysis |

**Note:** The analysis uses 2017 HMDA reporting definitions and should not be directly compared with later reporting years without accounting for changes in reporting requirements.

## Tools & Technologies

- **Tableau Public:** Data visualization, exploratory data analysis, calculated fields, and dashboard development.
- **Microsoft Excel:** Dataset inspection and preparation.
- **HMDA / CFPB Data:** Public mortgage lending data.

## Data Analysis & Visualizations

The project includes the following analytical components:

### 1. Mortgage Application Outcomes

Examines the distribution of mortgage application outcomes using the HMDA Action Taken field.

The analysis distinguishes between originated loans, approved applications that were not accepted, denials, withdrawals, incomplete applications, purchased loans, and preapproval outcomes.

**Key objective:** Understand the overall distribution of mortgage application outcomes.

### 2. Mortgage Denial Rate Analysis

Calculates the percentage of eligible mortgage applications that were denied.

The denial rate is calculated using:

```text
Denial Rate = (Denied Applications / Eligible Applications) × 100
```

For this project, eligible applications include originated loans, approved-but-not-accepted applications, and denied applications (HMDA Action Taken codes 1, 2, and 3).

**Key objective:** Compare mortgage denial rates across geographic regions and identify differences in lending outcomes.

### 3. Geographic Lending Activity

Uses geographic visualizations to examine mortgage application activity across U.S. states.

**Key objective:** Identify states with higher and lower mortgage application volumes and explore geographic differences in lending activity.

### 4. Loan Purpose Analysis

Examines mortgage applications by loan purpose, including home purchases, refinancing, and home improvements.

**Key objective:** Identify the most common reasons borrowers applied for mortgage financing.

### 5. Applicant Income Analysis

Explores the distribution of reported applicant income and examines differences in mortgage application outcomes across income groups.

**Key objective:** Investigate relationships between applicant income and mortgage lending outcomes.

## Tableau Dashboard

The final dashboard brings together the individual visualizations into a centralized analytical view.

Planned dashboard components include:

- Total mortgage application records.
- Total originated loans.
- Overall mortgage denial rate.
- Mortgage application outcome distribution.
- Geographic lending activity by state.
- Loan purpose distribution.
- Applicant income analysis.
- Interactive filters for exploring the data.

**Tableau Public Dashboard:** [Insert Tableau Public Link]

## Key Takeaways

The project is designed to identify and communicate patterns in mortgage lending activity, including:

- The distribution of mortgage application outcomes across the United States.
- Geographic differences in mortgage application volume and denial rates.
- Differences in lending activity across loan purposes.
- Variations in mortgage application outcomes across applicant income groups.

Final findings and numerical insights will be added after completing the dashboard and validating the calculations.

## Project Structure

```text
2017-Mortgage-Lending-Analysis/
│
├── README.md
│
├── Dataset/
│   └── HMDA_2017_Nationwide_Data.csv
│
├── Tableau/
│   └── Mortgage_Lending_Analysis.twbx
│
└── Screenshots/
    └── Dashboard.png
```

## Project Goals & Skills Demonstrated

This project demonstrates practical data analytics skills relevant to financial services and business intelligence roles:

- Exploratory Data Analysis (EDA)
- Data interpretation and validation
- Financial services and mortgage lending analysis
- Tableau calculated fields and aggregations
- Data visualization and dashboard development
- Geographic data analysis
- KPI development and reporting
- Communicating analytical findings

## Data Source & References

- [Consumer Financial Protection Bureau – HMDA Data](https://www.consumerfinance.gov/data-research/hmda/)
- [CFPB – Historical HMDA Data](https://www.consumerfinance.gov/data-research/hmda/historic-data/)

---

**Author:** Brandon Mercado Franco

**Project Category:** Data Analytics | Financial Services | Business Intelligence

**Primary Tool:** Tableau Public
