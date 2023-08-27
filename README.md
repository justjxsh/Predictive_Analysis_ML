# Predictive_Analysis_ML
Dust Level Prediction Using ML Algorithms

Overview
This project focuses on predicting and analyzing dust concentration levels in a specific environment. The goal is to develop a predictive model using machine learning techniques to anticipate future dust levels based on various factors. By employing this model, we aim to enhance real-time monitoring and mitigation efforts to minimize health risks associated with high dust levels.

Table of Contents
Background
Project Structure
Data Collection
Data Preprocessing
Machine Learning
Results
Usage
Future Improvements
Contributors
License
Background
Dust levels can have serious implications for human health, particularly in work environments with high levels of dust exposure. This project leverages machine learning algorithms, specifically Polynomial Regression, to predict future dust concentrations. The aim is to provide timely alerts and insights to minimize health risks for workers and individuals in such environments.

Project Structure
The project is organized into the following components:

Data Collection: Gathering dust concentration data along with relevant factors such as time, location, and weather conditions.
Data Preprocessing: Cleaning the data, handling missing values, and removing outliers for accurate model training.
Machine Learning: Using Polynomial Regression to model the relationship between dust concentrations and various independent variables.
Results and Visualization: Evaluating the model's performance and visualizing predictions against actual data.
Usage: Guidelines on how to use the project, run scripts, and interpret results.
Data Collection
The project collects data from sensors that measure dust concentrations in a specific environment. Alongside dust concentration levels, data on time, location (coordinates), temperature, humidity, wind speed, and particle sizes (0.3um, 0.5um, 1um, 2.5um, 5um, 10um) is recorded.

Data Preprocessing
Data is cleaned to remove rows with missing values (NaN).
Outliers are detected and removed to ensure accurate modeling.
Data is indexed by date for temporal analysis.
Machine Learning
Polynomial Regression is employed to model the relationship between dust concentrations and index values.
Polynomial features are generated from index values.
Models are trained and tested for each particle size and particle matter (PM) parameter.
Model performance is evaluated using R-squared scores.
Results
The project provides predictions for future dust concentrations based on the trained models.
Visualizations compare actual data with model predictions.
