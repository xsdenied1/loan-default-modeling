# Loan Portfolio Prediction

## Executive Summary

The **Loan Portfolio Prediction** project centers around an automotive loan lender in the Malaysian market. Leveraging machine learning, the client aims to screen applicants and determine their probability of defaulting on motorcycle loans. This involves collecting various data points per applicant and using predictive models to assess both:

- Whether an applicant is likely to default
- When that default might occur

Additionally, the project includes a **causal analysis component** to investigate what differentiates defaulters from non-defaulters, using natural experiments and counterfactual techniques.

As a result of this effort, we developed two machine learning models:
- A classification model to predict **if** a borrower will default
- A survival model to predict **when** the default might happen

The causal analysis further uncovered hypotheses on behavioral traits tied to defaults.

---

## Project Objective & Scope

**Objective:**  
To enhance the client’s decision-making process by improving the accuracy of default prediction models for motorcycle loan applicants.

**Scope:**  
- Improve the client's existing risk-scoring model using historical loan application data  
- Develop a second model to predict the timing of a potential default  
- Conduct a causal analysis to explain **why** applicants may default  
- Limit project scope to **motorcycle loans** in **Malaysia**, due to their unique characteristics (details in appendix)

---

## Project Drivers

- The client faces a **17.4% annual default rate**, resulting in significant losses.
- Even marginal improvements in predictive accuracy could yield substantial financial benefits.
- Our goal is to **maximize return on investment** by reducing default-related losses through better applicant screening.

---

## Key Data Sources

1. **Client Dataset**
   - Applicant information (e.g., income, housing)
   - Loan performance history (including default labels defined as ≥3 missed payments)
2. **Financial Metrics**
   - Average profit/loss per loan provided by the client
   - Used for cost-benefit analysis of all models
3. **Market Research**
   - Independent analysis of Malaysia’s motorcycle loan market
   - Helped inform recommendations in a local context

---

## Methodology

1. **Business Understanding**
   - Learned the client’s current lending workflow and regulatory environment
2. **Problem Formulation**
   - Defined modeling goals: predicting **default** and **default timing**
3. **Data Preparation & Model Development**
   - Trained and evaluated multiple models:  
     - XGBoost  
     - Decision Tree  
     - Random Forest  
     - Logistic Regression  
   - Model selection based on both predictive performance and financial cost-benefit tradeoffs
4. **Causal Inference**
   - Applied natural experiments and counterfactual methods
   - Explored deeper patterns behind defaults beyond correlation

---

## Technologies Used

- **R** (data preprocessing, modeling, and causal inference)
---

> _This project reflects a culmination of our skills developed during the NYU MSBA program, combining data science, business analytics, and causal inference to address a real-world financial challenge._
