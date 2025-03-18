# SNAP-Gun-Violence
## Research Question
To what extent is food security, a basic need, through SNAP associated with mass shootings gun violence in the United States?
## Overview
This project explores the relationship between access to basic food benefits, provided by the Supplemental Nutrition Assistance Program (SNAP), and gun violence rates. We hypothesize that food security fosters society stability and reduces gun violence. Using data from 2017 to 2019, we analyse mass shootings at the county level, incorporating data from the U.S. Census and SNAP participation records.
## Data Sources
- [Gun Violence Data](https://www.gunviolencearchive.org/reports/mass-shooting?year=2023): Mass shooting data (2017-2019) retrieved from  the Gun Violence Archive
- [City and Census Data](https://data.census.gov/table/ACSST1Y2016.S1701?q=percent%20of%20population%20below%20the%20poverty%20line%20by%20county&g=040XX00US06): US Census Burea's data on poverty status and other demographic information by county
- [SNAP Data](https://www.fns.usda.gov/pd/supplemental-nutrition-assistance-program-snap): Statistics on the number of individuals recieving SNAP benefits
## Methodology
- Machine Learning Models
  - Regression models (predicting proportion of mass shooting victims): Ordinary Least Squares, Decision Tree Regression, AdaBoost Regression
  - Classification models (predicting high or low gun violence): Logistic Regression, Decision Tree Classifier, AdaBoost Classifier
## Key Findings
Classification models outperformed regression models, suggesting that mass shooting gun violence is better categorized than predicted as a continuous variable. Education levels and race were the most predictive features for mass shooting rates. SNAP participation had high correlation with gun violence rates, but was not as strong a predictor as other demographic features with classification models. The Adaboost Classifier performed best, achieving: 85% accuracy, 76% AUC-ROC score, and 80% precision. Further policy discussions could explore the effects of educational funding and social programs on reducing gun violence.
## Notes
Information on accessing chloropeth map.
