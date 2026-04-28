# PensComplaintProject

## Overview
This project analyses customer complaints for a pension company and identifies root causes. It combines a cleaned CSV dataset with an interactive Jupyter notebook to reproduce the analysis reported in the accompanying PDF.

## Data dictionary

| Column | Description |
|---|---|
| complaint_id | Unique identifier for each complaint |
| policy_number | Identifier of the pension policy (alphanumeric string) |
| responsible_team | Team originally responsible for the policy (e.g., Onboarding, Claims) |
| handling_team | Team that handled the complaint |
| complainant_type | Whether the complainant is an 'agent' (advisor/broker) or 'customer' |
| root_cause | Categorised reason for the complaint (poor communication, misinformation, delayed response, etc.) |
| resolved | Whether the complaint was closed (yes/no) |
| resolution_time_days | Number of days taken to resolve the complaint |

## Running the analysis

1. Clone or download this repository.
2. Ensure you have Python and Jupyter installed (or use [Anaconda](https://www.anaconda.com)).
3. Open `complaints_analysis.ipynb` in Jupyter Notebook or JupyterLab.
4. Run all cells to load `pension_complaints_dataset.csv`, clean the data and generate the pivot tables and charts used in the report. The notebook outputs bar charts showing the frequency of each complaint cause and heatmaps illustrating hand‑offs between teams.

Alternatively, you can open the **Report.pdf** file for a narrative summary of the findings and recommendations.

## Key insights

- **Poor communication** accounts for ~51% of complaints; **misinformation** accounts for ~34%; **delayed responses** account for ~15%.
- Complaints peak during hand‑offs between teams. Misinformation is driven by inconsistent messaging, while delays stem from unclear ownership.
- A pilot implementation of the recommended improvements reduced complaints by approximately 31.6% within a month.

## Recommendations

- Improve team coordination through a shared customer relationship management (CRM) system.
- Introduce standardised response templates and a knowledge base to minimise misinformation.
- Monitor service level agreement (SLA) response times and empower teams to resolve issues at the first point of contact.

## Files

- `pension_complaints_dataset.csv` – cleaned dataset of customer complaints.
- `complaints_analysis.ipynb` – reproducible analysis notebook generating pivot tables and visualisations.
- `Report.pdf` – full project report.
- `ComplaintAnalysis.xlsx` – original Excel file used for initial pivot table analysis (still included for reference).

## Author

Olayinka Fawehinmi
