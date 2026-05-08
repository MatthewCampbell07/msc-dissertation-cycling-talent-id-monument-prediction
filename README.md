# 🚴‍♂️ Predictive Talent Identification in Professional Cycling
## Predicting 'Monument' Success from Junior Performance Metrics

## Project Overview
Talent identification in professional cycling is often unsystematic and financially risky. This study employs a longitudinal research design and Machine Learning to investigate whether junior one-day race metrics can predict future success in the five 'Monuments' of cycling.

## About the Author
I am an **MSc Sports Data Analytics** graduate and hold an **MA (Hons) in International Business Management**. This project represents a deep dive into the intersection of machine learning and high-performance talent strategy.

## The Data Science Challenge: Class Imbalance
Predicting an elite Top 10 finish is a "needle in a haystack" problem. To address this, I implemented:
* **SMOTE (Synthetic Minority Over-sampling Technique):** To balance the dataset for elite outcomes.
* **Feature Engineering:** Developed metrics like `Trend_Rank_Junior` and `Best_Junior_Rank_OneDay`.
* **Algorithms:** Evaluated Logistic Regression, Random Forest, and XGBoost.

## Key Findings
* **Predictability:** Moderate success in predicting Top 50 finishes (XGBoost AUC: 0.6414). 
* **The "Elite" Gap:** Predicting Top 10 finishes remains highly volatile (AUC: 0.553), supporting the **'Rocky Road' concept** of athlete development—where elite trajectories are rarely linear.
* **Accelerated Pathways:** Descriptive analysis revealed that Top 10 performers often have shorter junior careers and more rapid transitions to the pro ranks.

## Business & Strategic Implications
This study cautions professional teams against an over-reliance on raw junior data. Instead, it advocates for a **Dynamic Development Model** that prioritises long-term adaptability and "accelerated" indicators over immediate early-career results.

## Tech Stack
* **Language:** Python/R (whichever you used for the ML models)
* **Libraries:** Scikit-learn / XGBoost / SMOTE / ProCyclingStats API
* **Methodology:** VIF (Variance Inflation Factor) for feature selection, AUC-ROC evaluation.

