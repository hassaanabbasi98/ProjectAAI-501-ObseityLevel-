# Machine Learning for Obesity Level Prediction and Lifestyle Pattern Discovery

This project is part of the **AAI-501-02 course** in the Applied Artificial Intelligence Program at the University of San Diego (USD).

-- Project Status: Completed


## Installation

To use this project, first clone the repo on your device using the command below:
```
git init
git clone https://github.com/hassaanabbasi98/ProjectAAI-501-ObseityLevel-.git
```

## Project Intro / Objective
The main purpose of this project is to identify lifestyle characteristics, specifically eating habits and physical activity patterns, that contribute to obesity. Obesity is a complex public health issue influenced by behavioral, environmental, and physiological factors, and this project aims to uncover patterns in everyday behaviors that help explain differences in obesity levels.

By combining unsupervised and supervised machine learning approaches, this project seeks to both discover hidden lifestyle clusters and predict obesity categories based on measurable habits. The findings have the potential to support more targeted health interventions, inform public health strategies, and highlight actionable behaviors associated with increased obesity risk.

## Contributors
- Dina Othman
- Erika Gallegos
- Hassaan Abbasi

## Methods Used
- Data Cleaning & Preparation
- Exploratory Data Analysis
- Data visualizations
- Supervised Machine Learning
- Unsupervised Machine learning

## Technologies
- Python  
- Pandas, NumPy, Matplotlib, Seaborn  
- Scikit-learn  
- Jupyter Notebook  

## Project Description
This project analyzes the *Estimation of Obesity Levels Based on Eating Habits and Physical Condition* dataset from the UC Irvine Machine Learning Repository (DOI: 10.24432/C5H31Z). The dataset contains 2,111 observations of individuals from Mexico, Peru, and Colombia, with 17 variables describing daily eating habits, physical activity routines, and self-reported obesity levels. These variables include attributes such as frequency of high-calorie food consumption, water intake, time spent on physical activity, transportation mode, and categorical labels for obesity status (e.g., underweight, normal weight, overweight, and obesity levels I-III).

We aim to answer the research question: How can lifestyle patterns based on eating and physical activity predict obesity risk levels? To explore this, the project applies both unsupervised and supervised learning methods. Supervised machine learning (specifically logistic regression, random forest, and XGBoost) are used to identify important features in predicting obesity levels. Unsupervised machine learning (specifically cluster analysis and principal component analysis) are used to group individuals into lifestyle and eating pattern clusters.

Throughout the analysis, descriptive statistics, visualizations, correlation analyses, and model interpretation outputs are generated to better understand which behaviors most strongly influence obesity risk. The combined approach provides a comprehensive view of behavioral factors related to obesity and offer interpretable insights into how lifestyle characteristics can be used to estimate obesity levels.
 
## License
This project is licensed under an adapted MIT License. See the LICENSE file for details.

## Acknowledgements
The authors want to acknowledge the original authors of the dataset, which can be found at: https://doi.org/10.24432/C5H31Z.
