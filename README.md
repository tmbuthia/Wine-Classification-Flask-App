# Wine-Classification-Flask-App
This project is a Flask web application that uses a machine learning model to predict the type of wine based on a set of chemical properties. Users can select values for different features from dropdown lists to predict the wine type, providing an intuitive interface for non-technical users.
# Table of Contents
1. Project Overview
2. Features
3. Installation
4. Usage
5. Model Information
6. Contributing

# Project Overview
The Wine Classification Flask App is designed to demonstrate a basic machine learning model deployment using Flask. It classifies wine into one of three categories based on its chemical composition, including alcohol content, malic acid, ash, magnesium, and other features. The model was trained on a dataset of wine samples, making predictions accessible through an interactive web interface.

# Features
Predicts wine type (Class 0, Class 1, or Class 2) based on 13 chemical properties.
User-friendly input form with dropdown selections for each feature.
Displays the predicted wine type and the model’s confidence level.
Simple, intuitive interface for exploring wine classification.
# Installation
To set up and run this project locally, follow these steps:
# Usage
Open the app in your web browser.
Enter values for each of the 13 features using the dropdown lists.
Click "Predict" to submit the form.
The prediction result will show the most likely wine type and the confidence level for that prediction.
# Model Information
The classification model was trained on the UCI Wine Dataset, which includes 13 continuous attributes for 178 instances of wine. The model was saved as a pickle file (model.pkl) and loaded within the Flask app to make predictions.

# Feature List
> Alcohol: Alcohol content (continuous).
> Malic Acid: Malic acid concentration (continuous).
> Ash: Ash content (continuous).
> Alcalinity of Ash: Alcalinity of ash (continuous).
> Magnesium: Magnesium concentration (continuous).
> Total Phenols: Total phenols content (continuous).
> Flavanoids: Flavonoid concentration (continuous).
> Nonflavanoid Phenols: Nonflavanoid phenols content (continuous).
> Proanthocyanins: Proanthocyanins content (continuous).
> Color Intensity: Color intensity (continuous).
> Hue: Hue of wine (continuous).
> OD280/OD315 of Diluted Wines: Diluted wine measure (continuous).
> Proline: Proline content (continuous).

# Model Performance
The model's performance may vary depending on the dataset and the chemical properties entered. The application displays the predicted class along with a confidence percentage, offering insights into the model’s prediction reliability.
