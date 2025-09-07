# Strain, Victimisation, and Youth Offending  
*A Quantitative Analysis Using the Millennium Cohort Study (7th Sweep, 2018)*  

## Overview  
This project investigates the drivers of youth offending in England and Wales using data from the Millennium Cohort Study (MCS). The analysis is guided by **General Strain Theory (Agnew, 1992)** and supported by **Labelling Theory**, focusing on the role of victimisation in predicting both general and violent youth offending.  

The study applies statistical modelling techniques to explore whether young people who experience higher levels of victimisation are more likely to engage in offending behaviours.  

---

## Methods  
- **Data Source:** Millennium Cohort Study, 7th Sweep (2018) – nationally representative longitudinal dataset.  
- **Dependent Variables:**  
  - *Offending Scale* – summated index of self-reported offending (e.g., theft, criminal damage, graffiti, hacking, gang membership).  
  - *Violent Offending* – binary variable capturing knife carrying and physical aggression.  
- **Independent Variable:** Victimisation Scale (threats, physical violence, weapon use, theft).  
- **Control Variables:** Gender, Police Contact (stopped/arrested).  

### Statistical Techniques  
- Descriptive statistics & data visualisation  
- Bivariate Linear Regression  
- Multiple Linear Regression with controls  
- Logistic Regression for violent offending  
- Model diagnostics: multicollinearity (VIF), residual plots, predictive probabilities, confusion matrix  

**Software & Libraries:**  
- R: `dplyr`, `ggplot2`, `sjPlot`, `car`, `haven`  

---

## Key Findings  
- Victimisation was **positively and significantly associated** with both general offending and violent offending.  
- Each additional victimisation experience increased the odds of violent offending by ~170% (OR = 2.70).  
- Police contact and gender were also strong predictors, providing empirical support for **Labelling Theory** and gendered patterns of offending.  
- Models explained ~24% of variance, highlighting the role of other unmeasured factors (e.g., peer influence, school environment).  

---

## Limitations  
- Based on a single wave of MCS data (cross-sectional).  
- Reliant on self-reported offending → subject to recall bias and underreporting.  
- Logistic regression performance limited by class imbalance (violent offending less common).  

---

## Policy Implications  
- Early interventions should address youth victimisation as a pathway to offending.  
- Caution needed in police contact with young people, as it can reinforce deviant identities.  
- Gender differences must be accounted for in prevention and justice strategies.  

---

## Repository Contents  
- `report.pdf` – Full research paper  
- `analysis.R` – R code for data preparation, regression models, and diagnostics  
- `figures/` – Key visualisations (distributions, predictive probability plots)  

---

## Author  
Joseph Barker – University of Manchester, Data Analytics & Criminology (2025)  
