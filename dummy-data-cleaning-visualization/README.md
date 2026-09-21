# Dummy Data Cleaning and Visualization

A Python project focused on cleaning a messy, real-world-style dataset and visualizing key trends through statistical charts. This project demonstrates a complete data preprocessing pipeline — from identifying data quality issues to presenting clean, interpretable insights.

##  Project Overview

- **Objective:** Clean a raw, dummy dataset containing missing values, duplicate records, and inconsistent formatting, then build visualizations to uncover meaningful trends and patterns.
- **Type:** Data Cleaning & Exploratory Visualization
- **Libraries Used:** Pandas, NumPy, Matplotlib, Seaborn

##  Dataset

A synthetic dataset containing 200+ records with intentional data quality issues, including:
- Missing values across multiple columns
- Duplicate rows
- Inconsistent text formatting (casing, whitespace)

This mimics common real-world data problems encountered before any meaningful analysis can begin.

##  Key Steps Completed

**1. Data Inspection**
- Reviewed dataset structure, data types, and summary statistics using `.info()` and `.describe()`
- Identified the extent of missing values and duplicate records

**2. Data Cleaning**
- Removed duplicate rows to prevent skewed analysis
- Handled missing values using appropriate strategies (median/mode imputation for numeric and categorical columns)
- Standardized inconsistent text formatting (e.g. trimmed whitespace, unified casing)
- Corrected data types where necessary

**3. Data Visualization**
- Built histograms to examine the distribution of numeric variables
- Created bar/count plots to analyze category frequency
- Used box plots to identify potential outliers across groups

**4. Insights & Reporting**
- Summarized findings on data quality issues resolved and key patterns observed in the cleaned dataset

##  Tools & Libraries

- Python 3.13
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

##  How to Run

1. Clone this repository
```bash
   git clone <https://github.com/SNiveshh/Thiranex-Internship/tree/main/dummy-data-cleaning-visualization>
   cd dummy-data-cleaning-visualization
```

2. (Optional) Create and activate a virtual environment
```bash
   python -m venv venv
   venv\Scripts\activate        # Windows
   source venv/bin/activate     # macOS/Linux
```

3. Install required dependencies
```bash
   pip install pandas numpy matplotlib seaborn jupyter
```

4. Open `analysis.ipynb` in Jupyter Notebook or VS Code

5. Run all cells to reproduce the full cleaning and visualization workflow

##  Outcome

This project demonstrates practical data preprocessing skills essential to any data science workflow — identifying and resolving common data quality issues, and transforming raw data into clean, visualized insights ready for further analysis or modeling.

##  Author

Nivesh Somanaboina — Data Science Intern
