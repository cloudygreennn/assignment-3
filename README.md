# Assignment 3: Employment-Based Green Card Sponsorship Analysis

An interactive data visualization project analyzing **147,000+ employment-based green card (PERM) applications** from FY2025 to explore employer sponsorship trends, wages, occupations, and application outcomes.

## Overview

This project answers questions such as:

- Do larger companies pay higher sponsorship wages?
- Does company age affect wages?
- Which occupations receive the highest salaries?
- What are the most common sponsored job titles?
- Where are sponsoring employers located?
- Does processing time relate to application outcomes?

The project includes **six interactive visualizations** connected through shared dashboard filters.

## Built With

- Python
- Pandas
- Plotly
- ipywidgets
- Jupyter Notebook

## Dashboard Features

- Filter by State
- Filter by Company Size
- Filter by Job Function
- Six linked interactive charts that update simultaneously

## Repository Structure

```
├── assignment3.ipynb
├── perm_data.csv          # Automatically downloaded from the U.S. Department of Labor (DOL) on first run
├── df_clean.csv           # Pre-cleaned dataset for direct use (skip download and preprocessing)
└── README.md
```

> **Note:**  
> The notebook automatically downloads `perm_data.csv` from the **U.S. Department of Labor (DOL)** if it is not found locally. Alternatively, you can use the included `df_clean.csv` to run the analysis immediately without downloading or preprocessing the raw dataset.

## Running the Project

1. Clone this repository.
2. Install the required Python packages.
3. Open `assignment3.ipynb`.
4. Run all cells.
5. The dashboard will automatically:
   - Download the raw PERM dataset (first run only), **or**
   - Use the included `df_clean.csv` if you prefer to skip data preparation.
6. Explore the interactive dashboard.

## Dataset

Employment-Based Green Card (PERM) sponsorship data from the **U.S. Department of Labor (DOL)** containing over **147,000 employer filings** from Fiscal Year 2025.

## Key Insights

- Larger companies generally offer higher and more consistent wages.
- Company age has a smaller impact on wages than company size.
- Professional occupations command significantly higher salaries.
- Software Engineer is the most frequently sponsored job title.
- Employer sponsorship is concentrated in major technology hubs.
- Processing time shows little relationship with application outcomes.

## Author

**Yanjun Tan**

GitHub: https://github.com/cloudygreennn
