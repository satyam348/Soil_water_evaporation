# Soil_water_evaporation
Repository containging code and data for the prediction of soil water evaporation rate in differnet stages in soil covered with geotextile 
# README: AI-Based Prediction of Soil Water Evaporation Trends in Geotextile-Covered Soils

## Overview
This repository contains the dataset and code implementations for the ensemble machine learning models used in the study: **"AI-Based Prediction of Soil Water Evaporation Trends in Geotextile-Covered Soils"**. The study focuses on predicting soil water evaporation rates under geotextile cover using advanced AI models, including boosting-based ensemble techniques and explainable AI approaches.

## Dataset
The dataset used in this study is derived from experimental work conducted by Zhang et al. (2023). It includes data from three different fine-grained soils (Kaolin, Dredged Mud, and Red Mud) and four types of non-woven geotextiles. The dataset comprises the following feature variables:
- Liquid Limit (LL) [%]
- Specific Gravity (Gs)
- Soil Moisture Content (Wi) [%]
- Temperature (T) [°C]
- Relative Humidity (RH)
- Geotextile Thickness (d) [μm]
- Soil Particle Size (O95) [μm]
- Evaporation Rates for Stage 1 (ER1) and Stage 2 (ER2) [g/hr] (Target Variables)

## Code Implementation
The repository provides the implementation of ensemble-based machine learning models for evaporation rate prediction, including:
- **XGBoost** (Extreme Gradient Boosting)
- **GBM** (Gradient Boosting Machine)
- **AdaBoost** (Adaptive Boosting)
- **CatBoost** (Categorical Boosting)

### MGGP and ANN Implementations
The implementations of **Multi-Gene Genetic Programming (MGGP)** and **Artificial Neural Networks (ANN)** are not provided in this repository. Instead, users can refer to:
- **MGGP:** GPTIPS framework in MATLAB.
- **ANN:** MATLAB Neural Network Toolbox.

## Sensitivity Analysis
The study also includes sensitivity analysis to determine the importance of different features in evaporation prediction. Explainable AI techniques such as SHAP (SHapley Additive exPlanations) have been utilized to interpret model predictions.

## Results Summary
The study evaluates model performance using key statistical metrics such as R², RMSE, and MAE for both training and testing phases. The ensemble models demonstrated superior predictive capability compared to traditional regression and standalone ANN/MGGP models.

## Citation
If you use this dataset or code, please cite the original study appropriately.

## Contact
For any queries regarding this dataset or implementation, please reach out to the authors.

