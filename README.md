# Credit Card Churn Prediction (Imbalanced Classification)

This repository contains a machine learning project for predicting customer churn in a credit card business setting.  
We reproduce and compare baseline methods from prior work, then improve performance by focusing on imbalanced-class handling, model selection, and threshold tuning.

## Overview
- Task: Binary classification (churn vs. non-churn)
- Key challenge: Severe **class imbalance** (churn is the minority class)
- Focus: Robust evaluation beyond accuracy (e.g., F1 / PR-AUC / Recall)

## Problem Statement
Customer churn has a direct impact on revenue and retention cost. The goal of this project is to identify customers likely to churn early enough to support targeted retention strategies.
Objective: Given customer features (e.g., usage patterns, transactions, demographics), predict whether the customer will churn.

