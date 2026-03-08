# Patient Engagement & Experience Analytics
## Project Overview
This project analyses U.S. Healthcare Patient Experience data using publicy available datasets from the Centers for Medicare & Medicaid Services (CMS).
The goal of the analysis is to identify key drivers of patient satisfaction, engagement, and healthcare experience using stat analysis, ML (machine learning), and viz tehniques.
Understanding the factors that influence patient experience can help healthcare orgs. improve service delivery, patient engagement, and overall health outcomes.

## Research Questions
1. What factors most strongly influence patient satisfaction?
2. How does hospital responsiveness affect patient experience?
3. Are there geographic differences in patient satisfaction?
4. Can we predict poor patient experience using operational metrics?

## Data Sources
Data used in this analysis is from the CMS Open / PUF (Public Use Files) data:
- Hospital Consumer Assessment of Healthcare Providers and Systems (HCAHPS)
- Medicare Hospital Quality Data

Sources: https://data.cms.gov

## Tools
Python
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn
  - statsmodels

Viz
  - plotly
  - (Optional) Tableau / Power BI

## Workflow
1. Data ingestion and cleaning
2. Exploratory data analysis
3. Statistical Modeling
4. Machine Learning models
5. Visualization and insights

## Project Structure
patient-experience-analytics
|
|- README.md
|- requirements.txt
|
|- data
|   |- raw
|   |_ processed
|
├── notebooks
│   └── patient_experience_analysis.ipynb
│
├── src
│   ├── data_cleaning.py
│   ├── analysis.py
│   └── modeling.py
│
├── visuals
│   └── charts
│
└── report
    └── patient_experience_report.pdf
