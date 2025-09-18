## A Longitudinal Analysis of Whickham Data Project

## Project Overview
This project analyzes longitudinal data from Whickham, England, to explore the relationship between **smoking status**, **age**, and **mortality** over a 20-year period. The goal is to assess how smoking affects health outcomes and how age may confound this relationship.

---

## Methods & Tools Used

### Libraries
- `tidyverse` for data wrangling and visualization  
- `mosaicData` for accessing the Whickham dataset  

### Statistical Techniques
- Exploratory data analysis with bar plots and density plots  
- Conditional proportion calculations using `table()` and `prop.table()`  
- Age stratification using `case_when()` to create `age_cat`  
- Faceted visualizations to reveal confounding effects  

### Key Concepts
- Observational study design  
- Confounding and stratification  
- Misleading aggregated trends vs. subgroup analysis  

---