# ChurnGuard AI

A data-driven customer churn prediction and retention project developed as the **Final Assignment for GCI World April 2026**.

## Project Overview

The goal of this project is to help a telecom company identify customers who are more likely to churn and prioritize retention actions before they leave.

The analysis was performed on a dataset containing approximately **100,000 customer records**, including customer profiles, usage behavior, revenue, service quality, and churn information.

## What I Did

* Performed exploratory data analysis (EDA)
* Analyzed customer behavior and churn patterns
* Prepared and engineered features for machine learning
* Built an **XGBoost classification model**
* Evaluated the model using **ROC-AUC**
* Ranked customers by predicted churn risk
* Identified important churn drivers
* Developed targeted retention strategies for different customer segments
* Estimated the potential business impact of the proposed strategy

## Model Performance

* Model: XGBoost Gradient-Boosted Decision Trees
* ROC-AUC: **0.667**
* Average Precision: **0.651**
* Actual churn rate in the highest-risk decile: **75.6%**
* Overall churn rate: **49.6%**

The model is used as a prioritization tool rather than an automatic decision system.

## Business Proposal

The final proposal, **ChurnGuard AI**, focuses on four main retention groups:

* High-value customers at risk
* Customers with declining usage
* Customers with older devices
* Customers experiencing service-quality issues

The idea is to move from broad retention offers to targeted actions based on predicted churn risk and customer value.

## Repository Files

* `mohamed55.ipynb` — Full data analysis and machine learning workflow
* `mohamed55.pdf` — Final business proposal presentation

## Course

**GCI World April 2026**
Matsuo-Iwasawa Laboratory
Graduate School of Engineering
The University of Tokyo
