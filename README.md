# Alzheimer's Disease: A Study of Predictors and Risks

## Overview
This project investigates the predictors and risk factors associated with Alzheimer’s disease using logistic regression modeling. The dataset includes various demographic, lifestyle, and health variables. The goal is to identify significant predictors that may aid in early detection and intervention strategies for Alzheimer's disease.

## Repository Structure

1. **`data/`**  
   Contains the dataset used in this project.  
   Example file: `alzheimers_data.csv`

2. **`report/`**  
   Includes the main analysis report in R Markdown (`report.Rmd`) and a compiled HTML or PDF version (`report.html` or `report.pdf`). This report details the exploratory data analysis, statistical modeling, and key findings.

3. **`presentation/`**  
   Final presentation slides summarizing the project's goals, methodology, and key results. Includes visuals like ROC curves, feature importance, and key predictors.

---

## Objectives
- **Analyze** key demographic, lifestyle, and health predictors of Alzheimer’s diagnosis.
- **Build and evaluate** a logistic regression model for prediction.
- **Visualize** findings through EDA, feature importance plots, and performance metrics.

## Dataset
The dataset contains records for 2,143 individuals and includes the following variables:
- **Demographics:** Age, gender, ethnicity, education.
- **Lifestyle:** Smoking status, physical activity, diet quality, sleep quality.
- **Health:** BMI, cholesterol levels, blood pressure.
- **Cognitive Assessments:** MMSE scores, ADL scores, memory complaints, and behavioral changes.
- **Response Variable:** Alzheimer’s diagnosis (binary; 0 = No, 1 = Yes).

---

## Key Results
1. **Model Performance:**
   - AUC (Area Under the Curve): **0.81**, indicating strong predictive performance.
   - ROC curve analysis shows a good balance between sensitivity and specificity.

2. **Significant Predictors:**
   - **Memory Complaints**: Strongest predictor of diagnosis.
   - **ADL Scores**: Reduced daily functionality is highly associated with Alzheimer's diagnosis.
   - **Sleep Quality and MMSE Scores**: Show moderate associations with diagnosis likelihood.

3. **Visualization Highlights:**
   - Feature importance plot showing the strongest predictors.
   - ROC curve illustrating model performance.
   - Distribution of predicted probabilities for diagnosed vs. non-diagnosed individuals.

---

## Getting Started
### Clone the Repository
```bash
git clone <repository-link>


