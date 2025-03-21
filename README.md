# Wine Quality Analysis and Prediction

This project focuses on analyzing and predicting the quality of wine based on various physicochemical properties. The dataset used contains information about different types of wine, including their fixed acidity, volatile acidity, citric acid, residual sugar, chlorides, free sulfur dioxide, total sulfur dioxide, density, pH, sulphates, alcohol content, and quality ratings.
# Dataset
The dataset used in this project is named wine.csv and contains 6497 entries with 13 columns. The columns include:

type: Type of wine (e.g., white, red)

fixed acidity: Fixed acidity content

volatile acidity: Volatile acidity content

citric acid: Citric acid content

residual sugar: Residual sugar content

chlorides: Chlorides content

free sulfur dioxide: Free sulfur dioxide content

total sulfur dioxide: Total sulfur dioxide content

density: Density of the wine

pH: pH level

sulphates: Sulphates content

alcohol: Alcohol content

quality: Quality rating of the wine
# Dependencies
The project requires the following Python libraries:

numpy

pandas

matplotlib

seaborn

scikit-learn

xgboost
# Usage
Data Loading and Exploration:

Load the dataset and perform initial exploration to understand the structure and content of the data.

Data Cleaning:

Handle missing values by filling them with the mean of the respective columns.

Data Visualization:

Visualize the distribution of the data using histograms.

Model Training and Evaluation:

Split the data into training and testing sets.

Normalize the data.

Train and evaluate different machine learning models.
# Conclusion
This project provides a comprehensive analysis of the wine quality dataset and demonstrates the process of training and evaluating machine learning models to predict wine quality. The results can be used to gain insights into the factors that influence wine quality and to build predictive models for quality assessment.
