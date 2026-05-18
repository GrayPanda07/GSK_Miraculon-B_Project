# Protein Levels Dataset

This folder contains the biomarker dataset used in the GSK DigData Step Up Career Challenge.

The dataset contains protein concentration values collected from patients participating in a fictional oncology clinical trial investigating the treatment **Miraculon-B**.

The protein concentration values were analysed to determine whether the biomarker could help predict patient response to treatment.

---

# Dataset Information

## File Name
`protein-levels.csv`

## Dataset Type
Clinical biomarker dataset

## Number of Rows
768 patient records

## Number of Columns
2 variables

---

# Dataset Purpose

This dataset was used to:

- Investigate predictive biomarkers
- Analyse relationships between protein concentration and treatment response
- Support subgroup analysis
- Merge with the primary clinical trial dataset
- Explore whether biomarker levels could help identify patients most likely to benefit from treatment

---

# Column Dictionary

| Column Name | Description |
|---|---|
| participant_id | Unique patient identifier |
| protein_concentration | Concentration of a blood protein biomarker (ug/L) |

---

# Biomarker Context

The protein concentration variable represents a potential predictive biomarker identified during the clinical trial.

Predictive biomarkers can help determine:

- Which patients are more likely to respond to treatment
- Which patients may derive greater clinical benefit
- How treatment outcomes differ across patient populations

The challenge focused on exploring whether higher or lower protein concentrations were associated with treatment response.

---

# Example Analysis Questions

The dataset was used to investigate questions such as:

- Do responders have different protein concentrations compared to non-responders?
- Can protein concentration predict treatment success?
- Is protein concentration linked to patient subgroups?
- Does biomarker concentration differ between treatment groups?

---

# Example Analytical Tasks

Typical analytical tasks included:

- Merging datasets using XLOOKUP or joins
- Calculating summary statistics
- Creating boxplots and comparative charts
- Exploring response distributions
- Investigating biomarker trends

---

# Technologies Used

This dataset was analysed using:

- Python
- R
- Excel
- Google Sheets

Common tools and libraries included:

- pandas
- seaborn
- matplotlib
- ggplot2
- Pivot Tables
- XLOOKUP

---

# Data Disclaimer

This dataset is fictional and was provided as part of the GSK DigData Step Up Career Challenge.

The data is intended for educational and portfolio purposes only.

The dataset should not be redistributed outside this repository without permission from the original challenge providers.

---

# Source

GSK DigData Step Up Career Challenge

The challenge materials described this dataset as a biomarker dataset linked to response prediction within a simulated late-phase oncology clinical trial.
