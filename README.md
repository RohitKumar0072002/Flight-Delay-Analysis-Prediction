# Flight Delay Analysis & Prediction
**US Airline Delay Root Cause Analysis (2013-2023)**

## Overview
Analyzed 171,000+ flight records to identify delay patterns across 
23 airlines and 395 airports over 10 years. Built a Random Forest 
model to predict whether a route will face high delays.

## Dataset
- Source: US Bureau of Transportation Statistics
- File: Airline_Delay_Cause.csv (171,666 rows, 21 columns)
- Period: 2013 to 2023

## Setup
pip install pandas numpy matplotlib seaborn scikit-learn

## How to Run
1. Place Airline_Delay_Cause.csv in same folder as notebook
2. Open Flight Delay Analysis.ipynb in VS Code or Jupyter
3. Run All Cells top to bottom

## Project Structure
- EDA, Delay Cause Breakdown, Yearly Trend, Monthly Seasonality
- Random Forest Classifier, 96% Accuracy
- Feature Importance, Confusion Matrix
- Key Insights + Business Recommendations

## Key Results
- Late Aircraft is #1 delay cause, 39% of total delays
- Frontier Airlines worst performer at 25.1% delay rate
- June/July peak delay months, September best month to fly
- COVID 2020 showed lowest delays, 9.2% only
- Model Accuracy: 96.21%
