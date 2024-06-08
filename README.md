# House-Price-Prediction
This repository offers a model for house price prediction by creating a pipeline for it using machine learning. Built with Python and libraries like pandas, scikit-learn, and matplotlib, it covers data loading, preprocessing, feature engineering, and model training, emphasizing robust validation and hyperparameter tuning.

## Features

**Data Loading:** Automatically downloads and extracts the housing dataset.

**Data Exploration:** Initial dataset insights through statistics and visualizations.

**Data Preprocessing:**

    Handling missing values.
    
    Feature scaling.
    
    Creating new derived features.
    
    Transforming numeric and categorical attributes.
    
**Model Training:** Uses a RandomForestRegressor for prediction.

**Model Evaluation:** Cross-validation and hyperparameter tuning for optimization.

## Project Steps
**Load the Housing Data:** Downloads and extracts the dataset if not already present.

**Initial Exploration:** Generates statistical summaries and visualizations.

**Income Category Attribute:** Creates a categorical attribute for stratified sampling.

**Stratified Sampling:** Ensures train/test sets reflect the population distribution.

**Feature Engineering:** Adds new features like rooms_per_house, bedrooms_ratio, and people_per_house.

**Pipeline Creation:** Constructs preprocessing pipelines for numerical and categorical attributes.

## Model Training and Evaluation

**Pipeline Integration:** Combines preprocessing steps with the RandomForestRegressor.

**Cross-Validation:** Evaluates model performance through cross-validation.

**Hyperparameter Tuning:** Uses RandomizedSearchCV for finding optimal model parameters.

**Model Saving:** Saves the trained model and evaluation metrics.

## How to Use

**Clone the Repository:**
   
    git clone https://github.com/yourusername/house-price-prediction.git
    cd house-price-prediction
    
**Install Dependencies:**

    pip install -r requirements.txt
    
**Run the Code:**

Ensure data files are in the datasets folder or let the script download them.
Execute the main script to train and evaluate the model.

    python main.py
    
**View Results:**

The script outputs RMSE and other evaluation metrics.

Use the saved model for predictions on new data.

## Dependencies

Python 3.x

pandas

numpy

scikit-learn

matplotlib

joblib

## Contributing

Contributions are welcome! Please open an issue or submit a pull request with suggestions or improvements.
