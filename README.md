# Titanic Survival Prediction

This repository contains a machine learning model to predict whether a passenger survived the Titanic disaster based on various features like age, gender, ticket class, fare, and more.

## Task Objectives
- Preprocess the Titanic dataset, handling missing values and encoding categorical features.
- Train multiple models (RandomForest, Logistic Regression, XGBoost) and evaluate their performance.
- Perform hyperparameter tuning for the best-performing model.
- Analyze feature importance using SHAP.

## Steps to Run the Project
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd titanic-survival-prediction
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Place the Titanic dataset (`titanic.csv`) in the project directory.
4. Run the main script to train and evaluate models:
   ```bash
   python titanic_model.py
   ```
5. View the best model parameters and SHAP feature importance plots.

## Model Performance Metrics
After training, the script prints the evaluation metrics for each model, including accuracy, precision, recall, and F1 score.

## File Structure
- `titanic_model.py`: Main script for data preprocessing, training, evaluation, and feature analysis.
- `requirements.txt`: List of required Python libraries.
- `README.md`: Project overview and instructions.

## Notes
- The dataset must be in CSV format with expected feature names.
- The best-trained models are saved as `.pkl` files for reuse.
- SHAP analysis provides insights into feature importance.

