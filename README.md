# Seven-Eleven--Risk-Assessment-
Seven Eleven - Risk Assessment 

This project provides a comprehensive analysis of enterprise risks faced by 7-Eleven using both quantitative simulation techniques and machine learning classification models. The goal is to identify, quantify, and prioritize potential risks using data-driven methods, enabling more effective strategic planning and mitigation.


🚀 Project Overview
The project is divided into two major components:

1. Quantitative Risk Analysis
Monte Carlo Simulation was applied to estimate the cost uncertainty associated with selected high-impact risks (R2, R6, R9).

Simulations were performed using the PERT (Program Evaluation and Review Technique) method to handle uncertainty in cost estimations.

Outputs included:

Summary statistics (mean, standard deviation)

Cumulative distribution plots

90% confidence threshold costs

Visualizations using Matplotlib and Seaborn

2. Predictive Risk Classification
A classification model was developed to predict the risk category (High, Medium, Low) based on Likelihood and Impact scores.

The workflow included:

Data preprocessing and risk scoring

Training a machine learning classifier (e.g., Decision Tree or Logistic Regression)

Evaluation using accuracy and classification metrics

Visualization of confusion matrix and decision regions

📂 Files in This Repository
risk_analysis_&_quantitative_analysis.ipynb – Complete Jupyter notebook with simulations, plots, and predictive modeling

README.md – Project documentation

risk_dataset.csv – (Optional) Sample dataset of risk statements and scores 


📌 Key Results
Risk R6 (Capital Investment) had the highest estimated cost at 90% confidence: $9,311

Monte Carlo simulations reinforced the reliability of cost estimates with near-normal distributions

The classification model accurately predicted risk categories using impact and likelihood scores, aiding prioritization

📉 Tools & Libraries
Python 3.x

NumPy, Pandas

Matplotlib, Seaborn

Scikit-learn

Altair (for optional interactive visualization)

📈 Use Case
This risk analysis framework can be adapted for other retail chains, franchises, or enterprises aiming to:

Prioritize strategic risks

Forecast cost exposure

Deploy ML for risk classification

