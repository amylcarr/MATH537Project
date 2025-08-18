# Exploring Predictive Models for CDC Mortality Data

This repository contains code and analysis in partial fulfillment of requirements for a group project in our **MATH 537 - Topics in Data Science** course at the University of Alabama (Spring 2025).
The project investigates the predictive power of **Social Determinants of Health (SDoH)** in modeling opioid-related mortality rates for the state of North Carolina. For full analysis, refer to [full project report](./MATH_537_Team_Project_Report.pdf).
 ## Project Overview
 The opioid crisis remains one of the most urgent public health challenges in the United States. Our project examined whether county-level SDoH data can improve predictive models of opioid overdose mortality. Specifically, we compared:
- Linear regression models
- Polynomial regression models (degrees 2, 3, 4, 8)
- A **Vulnerability Index model** dervied from principal component analysis (PCA) of SDoH indicators
## Key Findings
- Linear regression using past crude mortality rates provided the lowest error (root MSE ≈ 3.93)
- Higher-degree polynomial models performed poorly, showing signs of overfitting
- The SDoH-based Vulnerability Index was less accurate (root MSE ≈ 13.08)
- Findings highlight the challenge of **suppressed/missing** CDC data and limitations of county-level modeling
## Data Sources
