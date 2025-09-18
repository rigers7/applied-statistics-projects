# Credit defaults and the bootstrap approach

## Project Overview
This project analyzes credit default probabilities using logistic regression and bootstrap resampling.  
It begins with estimating the overall default rate, then builds predictive models based on customer features.  
The second half explores bootstrap theory and simulations to understand sampling variability and inclusion probabilities.

## Methods & Tools

### Libraries
- `tidyverse` — data manipulation and visualization  
- `tidymodels` — model training and evaluation  
- `infer` — bootstrap resampling and statistical inference  
- `pROC` — ROC curve analysis  

### Modeling Techniques
- Logistic regression with forward stepwise selection  
- Confusion matrix, sensitivity, and specificity at threshold 0.5  
- ROC curve and Youden’s J statistic for optimal threshold  

### Bootstrap Concepts
- Sampling distribution of point estimators  
- Probability of inclusion in bootstrap samples  
- Analytical and simulated comparisons across sample sizes  