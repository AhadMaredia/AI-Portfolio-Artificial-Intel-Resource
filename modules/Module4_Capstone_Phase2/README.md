# Capstone Project — Phase 2

Model Development & Evaluation*

This module required building and evaluating multiple ML models for forecasting.

## Dataset

Cleaned Walmart sales dataset

Features included:

Store type/size

Economic indicators (CPI, unemployment)

Markdown events

Week, month

Lag & rolling sales features

## Models Developed

1. Linear Regression

RMSE: 21,752

R²: 0.093

Poor for nonlinear data

2. Gradient Boosting

RMSE: 11,524

R²: 0.745

3. Random Forest (Baseline Winner)

RMSE: 3,421

R²: 0.978

## Advanced Modeling: XGBoost

Base: RMSE 6,871 | R² 0.909

Grid Search R² ≈ 0.928

Random Search R² ≈ 0.938

## Final Tuned Model

RMSE: 4,858.70

R²: 0.9547

Chosen as final deployment model
