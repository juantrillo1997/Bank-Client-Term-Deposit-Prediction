# Predicting Term Deposit Subscriptions: A Summary

## Overview

This project aims to predict whether a bank client will subscribe to a term deposit using the Bank Marketing Dataset from UCI.

## Key Steps

1. **Data Exploration & Preprocessing:** Clean data, engineer features, and normalize values.
2. **Handling Class Imbalance:** Use bias initialization and downsampling to balance class distribution.
3. **Model Training & Evaluation:** Implement dropout and early stopping to avoid overfitting, and assess model performance with metrics like precision, recall, and F1-score.

**Results:**
- **Before Downsampling:** High accuracy but poor minority class performance.
- **After Downsampling:** Improved minority class detection with slightly reduced overall accuracy.

**Strategy:**
- Use a dual-model approach for high precision on the majority class and enhanced detection for the minority class, balancing overall performance.
