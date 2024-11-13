# Predicting Startup Outcomes

This project focuses on predicting the success or failure of startups using Big Data tools, specifically leveraging PySpark for large-scale data processing and machine learning models.

## Table of Contents

- [Introduction](#introduction)
- [Project Structure](#project-structure)
- [Data](#data)
- [Technologies Used](#technologies-used)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Results](#results)
- [Future Work](#future-work)
- [Contributors](#contributors)

## Introduction

Startups often face high uncertainty, and predicting their success or failure can help investors make informed decisions. This project utilizes historical startup data to build predictive models. We use PySpark for data preprocessing and machine learning due to its ability to handle large datasets efficiently.

## Project Structure

The project consists of the following components:

- **Data Preparation**: Includes data cleaning, feature engineering, and exploratory data analysis (`Data_Prep.ipynb`).
- **Modeling**:
  - **Decision Tree Classifier** (`Decision_tree_BDA.ipynb`)
  - **Logistic Regression** (`Logistic_Regression_BDA.ipynb`)
- **Evaluation**: Model performance metrics are used to assess the effectiveness of each algorithm.
- **Deployment**: (Optional) Deployment instructions for real-time prediction.

## Data

The dataset contains various features such as:

- Startup details (industry, location, etc.)
- Financial metrics (funding amount, rounds, etc.)
- Team composition
- Outcome (success or failure)

The data is processed in distributed fashion using PySpark to handle its size and complexity.

## Technologies Used

- **PySpark**: For data preprocessing and machine learning.
- **Jupyter Notebooks**: For interactive analysis and model building.
- **Python**: For scripting and model evaluation.
- **Big Data Cluster**: (Optional) for distributed computing.

## Setup and Installation

To run this project locally:

1. **Install Dependencies**:
   - Python 3.x
   - PySpark
   - Jupyter Notebook

   You can install PySpark using pip:
   ```bash
   pip install pyspark
   ```

2. **Clone the Repository**:
   ```bash
   git clone <(https://github.com/Kanan-Bedi/Predicting-Startup-Outcomes.git)>
   cd predicting-startup-outcomes
   ```

3. **Run Jupyter Notebook**:
   ```bash
   jupyter notebook
   ```

4. Open the relevant notebooks in your browser.

## Usage

1. **Data Preparation**:
   - Run `Data_Prep.ipynb` to preprocess and explore the data.
   
2. **Model Building**:
   - Use `Decision_tree_BDA.ipynb` to train and evaluate a Decision Tree model.
   - Use `Logistic_Regression_BDA.ipynb` to train and evaluate a Logistic Regression model.

3. **Evaluation**:
   - Compare the models based on metrics like accuracy, precision, recall, and F1-score.


## Future Work

- Incorporate more advanced models like Random Forest and Gradient Boosted Trees.
- Perform hyperparameter tuning to improve model performance.
- Explore ensemble methods for better predictions.
- Deploy the model for real-time prediction using Spark Streaming or a similar framework.
