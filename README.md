![img](https://github.com/Kohkitos/ironhack-kaggle-competition/blob/main/img/header.jpg)

# Airbnb Price Prediction Project ↗

This project was completed as part of the data analysis bootcamp at Ironhack and focused on a Kaggle machine learning competition centered around predicting Airbnb prices based on provided data.

## Overview 🔎

The goal of the project was to develop a predictive model for Airbnb prices using machine learning techniques. The dataset comprised two main CSV files:

- `train.csv`: This file contained the dataset used for training the model. It included various features along with corresponding Airbnb prices.
- `test.csv`: This file lacked the price information and was used to make predictions based on the trained model.

## Tools and Libraries 👨‍💻

- **Python**: The primary programming language used for data analysis and model building.
- **Pandas**: Utilized for reading and manipulating the CSV files.
- **Seaborn and Matplotlib**: These libraries were employed for data exploration, visualization, and transformation.

## Workflow 👷‍♂️

1. **Data Exploration**: The project initiated with the exploration of the provided Airbnb dataset. Pandas, Seaborn, and Matplotlib were used to understand the features, distributions, and correlations within the data.

2. **Data Preprocessing**: This step involved cleaning the dataset, handling missing values, encoding categorical variables, and performing any necessary feature engineering.

3. **Model Training**: Utilized `train.csv` to train a machine learning model. The `LinearRegression` algorithm was chosen for its simplicity and initial predictive capability.

4. **Predictions**: Applied the trained model to `test.csv` to predict Airbnb prices based on the features present in the test dataset.

5. **Evaluation and Optimization**: Evaluated the model's performance metrics and iteratively optimized the model by potentially exploring other algorithms, hyperparameter tuning, or feature selection techniques.

## Instructions ☝🤓

To replicate or work on this project:
1. Ensure you have Python installed.
2. Clone this repository.
3. Run the Jupyter notebooks or Python scripts provided to explore the code and data.
4. Feel free to experiment, modify, or extend the project as needed.

## Files Included 📝

- `train.csv`: Dataset used for model training.
- `test.csv`: Dataset for predicting Airbnb prices.
- `0-exploration.ipynb`: Exploration of process of the dataset.
- `1-Training_and_predicting.ipynb`: Training and predicting process.
