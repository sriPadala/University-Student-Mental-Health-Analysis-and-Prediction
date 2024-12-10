# University-Student-Mental-Health-Analysis-and-Prediction
## Overview
This project focuses on analyzing and predicting mental health issues among university students using machine learning models. Utilizing the University Student Mental Health dataset from the Borealis Database Repository, the study evaluates the impact of COVID-19 on stress levels, identifies key contributors to mental health challenges, and determines the most effective machine learning model for predicting mental health outcomes.

## Dataset
Source: Borealis Database Repository.
Description: Contains 1,659 records and 147 variables from a survey conducted at the University of Victoria, Canada, in 2020.
Key Features:
Pre- and Post-COVID-19 Perceived Stress Scale (PSS) scores.
Mental health attributes such as depression, anxiety, and mindfulness.
Demographic and lifestyle factors (e.g., disability, sleep, physical activity).
Objectives
Analyze the effects of COVID-19 on university students' mental health.
Identify major contributors to mental health challenges.
Compare the performance of machine learning models to predict mental health outcomes.
Recommend strategies for improving student well-being.
## Methodology
1. Data Preprocessing
Cleaned and prepared the dataset for analysis.
Managed missing values and outliers.
Applied feature scaling (e.g., standardization).
Split the data into training and testing subsets (80/20 split).
2. Machine Learning Models
The following machine learning models were implemented and evaluated:

  K-Nearest Neighbors (KNN) Classifier
  Tested with default and tuned parameters (e.g., number of neighbors, distance metrics).

  Decision Tree
  Experimented with pre-pruning, hyperparameter tuning, and post-pruning.

  Random Forest
  Hyperparameter tuning was performed to optimize model performance.

3. Statistical Analysis
Conducted a T-test to compare pre- and post-COVID-19 PSS scores.
Evaluated the statistical significance of changes in stress levels.

5. Evaluation Metrics
Accuracy
Precision
Recall
F1 Score
False Negative Rate (FNR)
ROC-AUC Curve

## Results
1. Machine Learning Model Comparison
Model	Accuracy	Precision	Recall	F1 Score	False Negative Rate
KNN Classifier	75.77%	73.33%	31.88%	0.44	5.06%
Decision Tree	75.33%	72.41%	30.43%	0.42	5.06%
Random Forest	77.53%	77.72%	94.93%	0.85	5.06%
Random Forest emerged as the best-performing model, with the highest scores across all metrics and an ROC-AUC of 0.80.
2. T-Test Analysis
Pre-COVID Mean PSS Score: 26.52
Post-COVID Mean PSS Score: 29.40
P-value: 4.83e-24
The analysis revealed a statistically significant increase in stress levels among students post-COVID.

3. Key Findings
Major contributors to mental health issues: disability, mindfulness, depression, and anxiety.
Mindfulness practices were linked to reduced stress susceptibility.
COVID-19 isolation and lifestyle changes significantly impacted student well-being.
## Visualizations
ROC-AUC Curves: Comparison of model performances.

Confusion Matrices: Insights into classification results.

Histogram: Pre- and Post-COVID stress level distributions.

Bar Chart: Increased stress levels post-COVID.

## Conclusion
The Random Forest model is the most suitable for predicting student mental health due to its superior performance metrics.

The significant increase in stress levels post-COVID highlights the need for targeted mental health support for students.

Future research should consider:
Physical activity and sleep patterns.
Multi-institutional datasets for broader insights.

Acknowledgments
Dataset Source: Borealis Database Repository.
Special thanks to the University of Victoria for the data.
