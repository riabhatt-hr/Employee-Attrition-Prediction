HR Analytics: Attrition Prediction and Hiring Optimization
This repository contains an end-to-end data science project designed to enhance Human Resources decision-making. By leveraging machine learning, the project identifies key drivers of employee turnover and automates candidate screening while maintaining a focus on ethical AI and bias mitigation.

Project Files
2.ipynb: The main Jupyter Notebook containing data preprocessing, exploratory analysis, model training, and ethical evaluation.

2.csv: The primary dataset featuring employee demographics, job roles, satisfaction levels, and attrition status.

Visualizations: Several image files (2.png through 2 (5).png) representing:

Exploratory Data Analysis (EDA) dashboards.

Feature importance and hiring decision drivers.

Model performance metrics (ROC-AUC, Confusion Matrix).

Bias audit results for DEI equity analysis.

Core Objectives
Attrition Analysis: Identifying why employees leave the organization and which factors (e.g., overtime, monthly income, job involvement) contribute most to turnover.

Predictive Modeling: Building a classification system to predict the likelihood of attrition with high precision and recall.

Business Impact: Reducing manual screening time and estimating cost savings per recruitment cycle.

Governance and Ethics: Conducting bias audits to ensure the model does not propagate unfair treatment based on gender or other protected attributes.

Technical Implementation
Data Processing: Handling imbalanced datasets using specialized sampling techniques and feature scaling.

Algorithms: Implementation of Random Forest and other classification benchmarks.

Key Metrics:

Accuracy: 90.14%

F1 Score: 85.59%

ROC-AUC: 93.09%

How to Use
Environment Setup:
Ensure Python is installed along with the following libraries:

pandas

scikit-learn

imbalanced-learn

matplotlib

seaborn

Execution:
Run the 2.ipynb notebook to reproduce the analysis. The notebook is structured to walk through data loading, cleaning, visualization, and finally, model deployment.

Ethical Notice
This tool is intended as a decision-support system. All AI-generated recommendations should be reviewed by a qualified HR professional to ensure human-in-the-loop oversight.
