# Lion_Studios_Data_Analyst_Exercise

This repository contains analysis for the Lion Studios Data Analyst exercise.  
The project focuses on designing and evaluating an A/B test for a new shop icon in a mobile game.

## Project Overview
- **Experiment design**: sample size estimation, runtime calculation, and definition of primary KPI, secondary KPIs, and guardrails.  
- **Statistical testing**:  
  - Stratified two-proportion z-test (for binary KPIs)  
  - Stratified Welch t-test with inverse-variance weighting (for continuous KPIs)  
- **Data quality checks**:  
  - Sample Ratio Mismatch (SRM) test  
  - Balance checks across country, platform, and install date using chi-square tests  

## KPIs and Guardrails
- **Primary KPI**: shop opens via icon (24h)  
- **Additional KPIs**: shop opens, purchases, and revenue across 24h and 7d windows  
- **Guardrails**: engagement and retention proxies (minutes played, levels played, RVS watched)  

This repository demonstrates how to approach an end-to-end product experiment: from design and statistical testing to interpretation and business recommendations.
