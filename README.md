# Pension Complaints Data Analysis

> **Portfolio project | Pension Administration • Data Quality • Python • Excel • Business Insight**

## Project overview

This project analyses a synthetic pension-company complaints dataset to identify recurring root causes, operational hand-offs and opportunities to improve complaint resolution.

It was designed to demonstrate how pension administration experience can be combined with **data analysis, data quality checks and business insight**.

### Business questions

- What are the main causes of pension complaints?
- Which teams are associated with complaint hand-offs?
- Where are communication and response processes creating avoidable issues?
- What operational improvements could reduce complaints and improve first-time resolution?

## Key findings

- **Poor communication** represents approximately 51% of complaints.
- **Misinformation** represents approximately 34%.
- **Delayed responses** represent approximately 15%.
- The analysis highlights complaint patterns associated with team hand-offs and unclear ownership.
- A pilot improvement scenario in the project report records an approximately **31.6% reduction in complaints within one month**.

> **Note:** These figures come from the project's synthetic/sample data and are not claims about any real pension provider.

## Analysis workflow

```text
Raw/sample data
      ↓
Data validation & cleaning
      ↓
Exploratory analysis
      ↓
Root-cause analysis
      ↓
Team hand-off analysis
      ↓
Pivot tables & visualisations
      ↓
Business recommendations
```

## Tools & technologies

| Area | Tools |
|---|---|
| Data analysis | Python, Pandas, NumPy |
| Visualisation | Matplotlib, Seaborn |
| Spreadsheet analysis | Microsoft Excel |
| Analysis environment | Jupyter Notebook |
| Business analysis | Root-cause analysis, KPI analysis, process improvement |

## Repository contents

| File | Purpose |
|---|---|
| `complaints_analysis.ipynb` | Reproducible Python analysis and visualisations |
| `pension_complaints_dataset.csv` | Synthetic/sample complaint dataset |
| `ComplaintAnalysis.xlsx` | Supporting Excel analysis and pivot tables |
| `Report.pdf` | Detailed project report |

## Data dictionary

| Column | Description |
|---|---|
| `complaint_id` | Unique complaint identifier |
| `policy_number` | Pension policy identifier |
| `responsible_team` | Team originally responsible for the policy |
| `handling_team` | Team that handled the complaint |
| `complainant_type` | Customer or agent/adviser |
| `root_cause` | Categorised complaint cause |
| `resolved` | Whether the complaint was resolved |
| `resolution_time_days` | Days taken to resolve the complaint |

## How to run

1. Clone the repository.
2. Install the Python dependencies.
3. Open `complaints_analysis.ipynb` in Jupyter Notebook or JupyterLab.
4. Run the notebook from top to bottom.

```bash
pip install -r requirements.txt
```

## Why this project matters

This project demonstrates a practical combination of:

**Pension domain knowledge + data quality + Python analysis + Excel + business recommendations.**

It is particularly relevant to roles involving **pension data, data quality, MI/reporting, pension administration, customer insight and business analysis**.

## Author

**Olayinka Fawehinmi**  
MSc Artificial Intelligence & Data Science | Pension Administration | Data Analysis

[GitHub profile](https://github.com/yinkatanko-a11y)
