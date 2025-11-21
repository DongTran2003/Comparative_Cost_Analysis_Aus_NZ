# AUS vs NZ Salary Analysis

This project analyzes salary data for comparable roles in Australia and New Zealand to estimate potential cost differences and validate data quality.

## Project Files

- **Report**: [`AUS_NZ_Analysis.ipynb`](AUS_NZ_Analysis.ipynb)  
  Jupyter Notebook containing the full analysis, including data cleaning, calculations, cost comparisons, and statistical tests.  

- **Original Data**: [`data.csv`](data.csv)  
  Raw salary data as provided, including both Australian and New Zealand roles.  

- **Clean Data**: [`clean_output.csv`](clean_output.csv)  
  Cleaned and processed dataset after removing invalid rows, duplicates, and correcting data types.  

- **Audit Trail / Documentation Table**: [`final_output.csv`](final_output.csv)  
  A detailed table documenting all records processed, their validation status, and the reasons for inclusion or exclusion in the analysis. Includes flags for valid IRD, duplicates, and data usage.  

## Purpose

- Estimate total costs for comparable roles in both countries.  
- Identify potential savings if roles were shifted between Australia and New Zealand.  
- Validate the dataset using national tax rules and IRD/employee number checks.  
- Provide a complete audit trail for transparency and reproducibility.  

## How to Use

1. Open `AUS_NZ_Analysis.ipynb` to follow the full analysis workflow.  
2. Review `clean_output.csv` for the cleaned dataset ready for calculations.  
3. Review `final_output.csv` for a detailed audit trail of all records.
