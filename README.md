# Repository: worldbank-education-indicators-analysis  
**Description:** Exploratory analysis of World Bank education indicators to assess their suitability for understanding potential markets for online learning platforms.

## Project Overview
This project assesses whether the World Bank’s “EdStats All Indicator Query” dataset can inform the potential demand for online learning platforms. The analysis addresses:
- Data quality evaluation (missing values, duplicates)
- Summary of key education metrics by country and region
- Visualization of regional patterns to highlight promising markets for digital learning solutions

## Files and Contents
- **Notebook_data_processing.ipynb**  
  Details the data ingestion and cleaning workflow: loading the raw CSV, profiling missingness and duplicates, applying multiple imputation methods for high-missingness variables, and detecting outliers. The result is a clean, reproducible dataset ready for exploration.

- **Notebook_data_analysis.ipynb**  
  Presents the exploratory data analysis: univariate summaries of selected indicators, correlation heatmaps, and computation of summary statistics (mean, median, standard deviation) aggregated by country and by continent/income group. Geographic visualizations illustrate market patterns relevant to online learning.

- **Presentation_of_analysis.pdf**  
  A concise slide deck for stakeholders summarizing data quality findings, key indicator insights, and regional comparisons. It concludes with recommendations on which regions show the highest potential for online learning platforms.

## Data Source
- **Dataset:** EdStats All Indicator Query
- **Download:** Available in CSV format from the World Bank Data Catalog: https://datacatalog.worldbank.org/dataset/education-statistics
- **Scope:** Approximately 4,000 indicators covering enrollment, attainment, teacher statistics, and education expenditures, across all countries and time periods.
