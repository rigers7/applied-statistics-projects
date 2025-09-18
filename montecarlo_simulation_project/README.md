# Blackjack - Monte Carlo Simulation

## Project Overview
This project explores two distinct probability scenarios using both analytical methods and Monte Carlo simulations:

1. **Vehicle Speeds on Interstate 5**: Estimating speeding probabilities and simulating waiting times until a speeding event.  
2. **Blackjack Hands**: Approximating the probability of being dealt a natural blackjack using repeated random sampling.

## Methods & Tools

### Libraries
- `tidyverse` — data manipulation and visualization  
- `infer` — bootstrap-based inference  
- `pROC` — ROC curve analysis  

### Statistical Concepts
- Normal distribution modeling of vehicle speeds  
- Bernoulli trials and geometric distribution  
- Monte Carlo simulation using `replicate()`  
- Bootstrap sampling and standard error estimation  
- ROC curve and threshold optimization  

### Simulation Techniques
- Estimating probabilities via repeated random sampling  
- Custom function creation for blackjack hand evaluation  
- Comparing simulated results with exact theoretical probabilities 