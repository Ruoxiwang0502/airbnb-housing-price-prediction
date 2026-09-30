# Airbnb & Housing Price Prediction

An end-to-end data science project for predicting Airbnb rental prices and residential housing prices.

The project demonstrates a complete machine learning workflow, from data preprocessing and feature engineering to model development, API integration, and a web-based prediction interface.

## Project Overview

This repository contains two predictive systems:

- **Airbnb Price Prediction** — estimates Airbnb listing prices using property, location, and listing-related features.
- **Housing Price Prediction** — estimates residential property prices using housing, demographic, geographic, and socioeconomic features.

The project combines statistical modeling, machine learning, API development, and front-end integration to turn predictive models into usable applications.

## Key Skills

- Python
- Pandas & NumPy
- Scikit-learn
- Data Cleaning
- Feature Engineering
- Regression & Machine Learning
- Model Training and Evaluation
- FastAPI
- REST APIs
- HTML / Web Integration
- Git & GitHub

## Project Workflow

Data Collection  
→ Data Cleaning  
→ Feature Engineering  
→ Model Training  
→ Model Evaluation  
→ API Development  
→ Web Application Integration

## Repository Structure

```text
airbnb-housing-price-prediction/
│
├── airbnb-api/
│   ├── airbnb_predict.py
│   ├── api.py
│   ├── airbnb_metadata.pkl
│   └── requirements.txt
│
├── housing-api/
│   ├── main.py
│   ├── train_and_save_county_models.py
│   ├── STA160FINALTWOMODELS.ipynb
│   ├── housingvars.csv
│   └── requirements.txt
│
├── web-app/
│   ├── index.html
│   ├── map.html
│   ├── trends.html
│   ├── airbnb_predictor.html
│   └── predictor.html
│
└── README.md