# Real Estate Price Prediction
![Project Logo](https://github.com/aka-0803/real-estate-price-prediction/blob/main/images/project_img.png?raw=true)
## Overview

This project focuses on predicting real estate prices in Bangalore using a linear regression model. The backend is built with Python Flask, and the frontend utilizes HTML, CSS, and JS. The linear regression model is implemented using scikit-learn, and data processing involves NumPy, pandas, and matplotlib.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Data Preprocessing](#data-preprocessing)
- [Model Training](#model-training)
- [Evaluation](#evaluation)
- [Tech Stack](#tech-stack)

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/aka-0803/real-estate-price-prediction.git
    cd real-estate-prediction
    ```

3. **Run Flask application:**

    ```bash
    python server.py
    ```

    Visit [http://localhost:5000](http://localhost:5000) in your browser to access the application.

## Usage

- Navigate to the web interface and input relevant features to get a predicted real estate price.

![Predicted Logo](https://github.com/aka-0803/real-estate-price-prediction/blob/main/images/price_predicted.png?raw=true)

## Data Preprocessing

Before training the model, the dataset (`bangalore_house_prices.csv`) undergoes data cleaning and outlier removal to ensure the model's robustness.

![data clean](https://github.com/aka-0803/real-estate-price-prediction/blob/main/images/na_val.png?raw=true)

## Model Training

The linear regression model is trained using scikit-learn. K-fold cross-validation and grid search CV methods are employed to find the best hyperparameters.
- **score**
![score](https://github.com/aka-0803/real-estate-price-prediction/blob/main/images/score.png?raw=true)

## Evaluation

The model is evaluated on various metrics to ensure its predictive performance. Visualizations using matplotlib aid in understanding the model's behavior.

## Tech Stack

- **Backend:** Python Flask
- **Frontend:** HTML, CSS, JS
- **Machine Learning:** scikit-learn
- **Data Processing:** NumPy, pandas, matplotlib
