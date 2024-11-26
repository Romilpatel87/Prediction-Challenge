# Airbnb Deal Quality Prediction Challenge

## Project Purpose

This project involves analyzing Airbnb data to predict "Deal Quality" (Good, Bad, or Unknown) using advanced feature engineering and modeling techniques. The work demonstrates the use of derived attributes, sophisticated patterns, and predictive models to achieve meaningful insights and high accuracy.

The project is divided into two parts:

1. **Prediction Challenge**: Build a model to classify Airbnb listings' deal quality using the `predictionChallenge.csv` dataset and additional attributes derived from external data (e.g., `Attractions.csv`).
2. **Custom Prediction Challenge**: Create a new prediction challenge based on a custom-designed decision column, incorporating derived attributes and complex patterns to make the solution non-trivial.

## Key Features

### Part 1: Prediction Challenge
- **Objective**: Predict whether a listing's deal quality is "Good," "Bad," or "Unknown."
- **Techniques Used**:
  - Derived attributes, such as proximity to attractions and number of reviews per month.
  - Logistic Regression and Random Forest models for classification.
  - Visualizations to explore relationships between price, proximity, and deal quality.
- **Outcome**: Achieved a predictive accuracy of up to 91% using the Random Forest model.

### Part 2: Custom Prediction Challenge
- **Objective**: Design a custom decision column based on derived attributes and sophisticated patterns, ensuring non-detectability by basic decision trees.
- **Techniques Used**:
  - Created new features: Proximity Score, Attractiveness Index, Demand-Supply Ratio, and Seasonal Adjustment.
  - Integrated external data (e.g., points of interest) for advanced feature engineering.
  - Used logistic regression to validate the model, highlighting significant predictors like location and room features.

## Files in This Repository

### Data
- `data/predictionChallenge.csv`: Dataset used for the first part of the project.
- `data/Attractions.csv`: Supplementary data for proximity-related features.
- `data/Updated_Airbnb.csv`: Dataset with added features and derived attributes used in the analysis.

### Code and Reports
- `PredictionChallenge.Rmd`: R Markdown file containing the analysis and code for Part 1.
- `Prediction Challenge Pt.2.Rmd`: R Markdown file containing the analysis and code for Part 2.

### Reports
- `Prediction Challenge Pt.1.pdf`: Detailed report for the first part of the project.
- `Prediction Challenge Pt.2.pdf`: Comprehensive report for the custom prediction challenge.

### PPT (Presentation)
- `ppt/`: Folder containing PowerPoint presentations for the project.

### Rstudio Code (Code for Development)
- `Rstudio_code/`: Folder containing additional studio code files related to the project.

## How to Use

### Run the Analysis
- **For Part 1**: Open and run `PredictionChallenge.Rmd` in RStudio.
- **For Part 2**: Open and run `Prediction Challenge Pt.2.Rmd` in RStudio.

### Explore the Reports
- `Prediction Challenge Pt.1.pdf` and `Prediction Challenge Pt.2.pdf` contain detailed explanations, visualizations, and results.

## Key Insights

- Listings closer to attractions with higher attractiveness indices tend to have better deal quality.
- The Random Forest model achieved superior accuracy compared to Logistic Regression.
- Sophisticated feature engineering and pattern design significantly improve prediction accuracy.

## Acknowledgments

- Dataset sourced from [Kaggle: New York City Airbnb Open Data](https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data).
- The work is purely for educational purposes, showcasing feature engineering, modeling, and analysis.
