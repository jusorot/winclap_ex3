# Project: Report Generation using Spark and Pandas

This project aims to generate a report from the `applicationdata` dataset, meeting specific requirements for analysis and campaign metrics.

## Project Contents

1. **Main Files:**
   - `1.eda.ipynb`: Notebook used for Exploratory Data Analysis (EDA).
   - `2.reports.ipynb`: Notebook used for report generation using Spark and Pandas.

2. **Configuration Files:**
   - `requirements.txt`: File listing all dependencies required to run the project in a virtual environment.

3. **Data Files:**
   - `dataset.csv`: Original dataset used in the project.

4. **Output Files:**
   - `eda_output.html`: HTML report generated from the 1.eda.ipynb notebook: This report includes insights into dataset structure, quality assessment, distribution of values, handling of missing data, and conclusions drawn from the analysis.
   To view the HTML report, open `eda_output.html` in a web browser.

## Exploratory Data Analysis (EDA)

The `eda.ipynb` notebook contains detailed exploratory analysis of the `applicationdata` dataset, including:

- Description of dataset structure and quality.
- Analysis of categorical and numeric columns.
- Distribution of values and handling of missing data.
- Conclusions and assumptions made for analysis.

## Report Generation

The `reports.ipynb` notebook utilizes Spark and Pandas to process and analyze the dataset, generating a report that meets the following requirements:

- Date format in ISO format.
- Metrics grouped by campaign, including:
  - Number of impressions.
  - Number of clicks.
  - Number of installs.
  - Amount spent.
  - CTR (Click-Through Rate).
  - CPI (Cost Per Install).

The report also includes visualizations using matplotlib to aid in interpreting the results.

## Installation and Execution

1. **Activate your virtual environment:**

   ```bash
   # On Windows
   venv\Scripts\activate

   # On macOS/Linux
   source venv/bin/activate

2. **Install dependencies:**
   ```python
   pip install -U -r requirements.txt

3. **Run Notebooks:**

   You can now run the notebooks using the installed IPython kernel. 
   Open your notebook files (1.eda.ipynb and 2.reports.ipynb) and select the kernel associated with your virtual environment (venv)
   