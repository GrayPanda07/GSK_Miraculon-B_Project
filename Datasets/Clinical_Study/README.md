# Clinical Study Dataset

This folder contains the primary clinical trial dataset used throughout the GSK DigData Step Up Career Challenge.

The dataset simulates data collected from a late-phase oncology clinical trial investigating the effectiveness of a fictional treatment called **Miraculon-B** compared to the current standard of care.

---

# Dataset Information

## File Name
`clinical-study.csv`

## Dataset Type
Clinical trial patient dataset

## Number of Rows
772 patient records

## Number of Columns
7 variables

---

# Dataset Purpose

The dataset was used to:

- Analyse treatment effectiveness
- Compare response rates between treatment groups
- Explore patient characteristics linked to treatment response
- Perform subgroup analysis
- Create visualisations and presentations
- Support exploratory and statistical analysis workflows

---

# Column Dictionary

| Column Name | Description |
|---|---|
| subject_id | Unique patient identifier |
| sex | Patient sex |
| age | Patient age |
| weight | Patient weight |
| height | Patient height |
| trt_grp | Treatment group (Miraculon-B or Control) |
| response | Whether the patient responded to treatment |

---

# Response Definition

Patients were classified as:

- **Responder (Y)** → Tumour shrank during treatment
- **Non-responder (N)** → Tumour remained stable or progressed

---

# Data Preparation Tasks

As part of the challenge, the dataset required preprocessing and cleaning before analysis.

Tasks included:

- Removing duplicate patient records
- Filtering paediatric patients (under 18)
- Handling missing values
- Creating BMI variables
- Preparing the dataset for merging with biomarker data


---

# Example Analysis Questions

The dataset was used to investigate questions such as:

- Does Miraculon-B outperform the standard of care?
- Are responders generally younger or older?
- Does BMI impact treatment response?
- Can protein concentration predict response likelihood?
- Which patient subgroups benefit most from treatment?

---

# Technologies Used

This dataset was analysed using:

- Python
- R
- Excel
- Google Sheets

Common libraries and tools included:

- pandas
- matplotlib
- seaborn
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

Challenge materials described the dataset as part of a simulated late-phase oncology clinical trial analysis project focused on evaluating Miraculon-B treatment outcomes.
