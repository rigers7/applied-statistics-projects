# Birthweight Modeling 

## Project Overview
This project investigates predictors of infant birth weight using maternal health and demographic data.  
The goal is to build and evaluate linear regression models to identify key factors influencing birth weight and assess model performance through cross-validation.

## Methods & Tools

### Libraries
- `tidyverse` — data wrangling and visualization  
- `GGally` — pairwise plots  
- `stats::step()` — stepwise model selection  
- `tidymodels` — cross-validation workflows  

### Modeling Techniques
- Full linear regression model using all predictors  
- Stepwise selection to identify a reduced model  
- Train/test split for predictive performance  
- 5-fold cross-validation for robust RMSE comparison  

### Evaluation Metrics
- RMSE (Root Mean Squared Error)