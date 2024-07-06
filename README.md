# Stroke-prediction-

## Overview

Welcome to the **Stroke Prediction** project. This repository contains the code and documentation for an end-to-end data analysis and machine learning workflow aimed at predicting the occurrence of strokes based on various health and demographic factors. The project encompasses Exploratory Data Analysis (EDA) and the development of multiple classification models to identify the most effective approach for stroke prediction.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Usage](#usage)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Model Building](#model-building)
- [Results](#results)

## Introduction

Strokes are a leading cause of death and disability worldwide. Early detection and prevention are crucial in reducing the impact of strokes. This project leverages machine learning techniques to predict the likelihood of a stroke based on individual health data, enabling timely intervention and potentially saving lives.

## Dataset

The dataset used for this project contains various health and demographic attributes, including:

- Age
- Gender
- Hypertension
- Heart Disease
- Ever Married
- Work Type
- Residence Type
- Average Glucose Level
- BMI
- Smoking Status
- Stroke (target variable)

## Usage
## Exploratory Data Analysis

The EDA notebook (`notebooks/eda.ipynb`) provides an in-depth analysis of the dataset, including:

- Data cleaning and preprocessing
- Statistical summaries and visualizations
- Identification of patterns and correlations
- Handling missing values and outliers

## Model Building

The model building process involves:

- Data preprocessing and feature engineering (`notebooks/data_preprocessing.ipynb`)
- Training multiple classification models (`notebooks/model_building.ipynb`), including:
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - Gradient Boosting
  - Support Vector Machine
  - Neural Network
- Hyperparameter tuning and model selection
- Model evaluation and comparison

## Results

The results of the analysis and model performance metrics are documented in the `results` directory. Key findings and performance of different models are summarized in the `model_building.ipynb` notebook.
