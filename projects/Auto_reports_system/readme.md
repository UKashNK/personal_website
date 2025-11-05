# Automated Reporting System

## Overview
A Python automation tool that generates and emails business KPI reports (PDF/HTML) from raw data.
It reduces manual report preparation and ensures consistent data delivery.

## Tools & Libraries
- Python, Pandas, NumPy
- Matplotlib / Plotly
- ReportLab or Jinja2 + WeasyPrint (for PDF/HTML generation)
- smtplib, schedule (for email automation)

## Dataset
- Example: [Superstore Sales Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)
- Contains sales, profit, region, and category data.

## Project Steps
1. **Data Extraction**
   - Load daily/weekly data from CSV or SQL database
2. **Data Transformation**
   - Compute KPIs: total sales, profit margin, YoY growth, top categories
3. **Visualization**
   - Generate charts (line, bar, pie) for KPIs
4. **Report Generation**
   - Insert KPIs and plots into a styled PDF/HTML template
5. **Automation**
   - Schedule weekly runs and email the generated report to stakeholders

## Example Output
`reports/report_2025-11-05.pdf`

Includes:
- Summary of key KPIs
- Visualized performance trends
- Highlighted top and bottom performers

## Screenshots
*(Include one or two sample report pages here)*

## Future Enhancements
- Add authentication and cloud storage (e.g. Google Drive upload)
- Integrate with BI tools (Power BI API, Tableau Extracts)
- Use natural language summaries with GPT models

## Author
**Katende Ukasha Ndugwa Kinene** – Data Analyst