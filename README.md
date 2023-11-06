# Stop By Decision Prediction Project

## Overview

This project focuses on predicting drivers' stop-by decisions in response to in-vehicle radio advertisements. It leverages machine learning techniques to make predictions based on a dataset of driver characteristics, preferences, and external factors. The primary objective is to determine whether a driver will stop at a nearby store after hearing a radio advertisement while driving.

## Dataset

The dataset used for this project is "dataset.csv." It contains 21 features that capture various aspects of drivers' behavior and preferences. These features include both categorical and numerical variables, making data preprocessing an important step in the project.

### Features

- Categorical Variables: Gender, Marital Status, Education, Income, Destination, Passengers, Weather, Visiting Preferences, Store Type, and Offer Endings.
- Numerical Variables: Age, Number of Children, Temperature, Time of Day, and Binary Indicators.
- Prediction Output: "stopBy(y)" - A binary indicator of whether the driver will stop at a nearby store.

## Project Objectives

The key goals of this project are:

1. In-depth data exploration and feature analysis to identify feature importance.
2. Data preprocessing, including handling missing data, encoding categorical variables, and scaling numerical features.
3. Implementation and evaluation of machine learning models for stop-by decision prediction.
4. Model selection and performance evaluation using accuracy, precision, recall, and F1-score.
5. Hyperparameter tuning, regularization, and feature selection for model improvement.
6. Comparative study of different models to understand their advantages and disadvantages.

## Project Structure

The project directory is structured as follows:

- `data/`: Contains the dataset "dataset.csv."
- `notebooks/`: Jupyter notebooks for data exploration, preprocessing, and modeling.
- `src/`: Python source code for data preprocessing, model implementation, and evaluation.
- `README.md`: The project's main README file.
- `LICENSE`: Project license information.

## Getting Started

To replicate and experiment with this project, you can follow the Jupyter notebooks in the `notebooks/` directory. The Python source code for data preprocessing and model implementation is available in the `src/` directory.

## Dependencies

- Python 3.x
- Jupyter Notebook (for running the notebooks)
- NumPy
- pandas
- scikit-learn
- matplotlib
- seaborn

Make sure to install the required dependencies before running the project.
