# Retail IRB PD Modeling Project

## Project Overview
This project implements a Probability of Default (PD) model for a retail portfolio (e.g., mortgages or credit cards) following the **Internal Ratings-Based (IRB)** approach.

## Key Features
*   **Data Preprocessing:** Handling missing values and outliers in financial time-series.
*   **Feature Engineering:** WOE (Weight of Evidence) transformation and Information Value (IV) filtering.
*   **Modeling:** Logistic Regression (Standard IRB) vs. XGBoost/LightGBM (Challenger models).
*   **Validation:** Calibration tests (Hosmer-Lemeshow), Discriminatory power (Gini/AUC), and Stability (PSI).
*   **Regulatory Focus:** Ensuring monotonicity and adherence to Basel standards.

## Project Structure

