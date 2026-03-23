# Podium Predictor ML

A machine learning pipeline that predicts Formula 1 podium finishes using historical practice and qualifying session data. This project explores the application of ML in sports analytics, specifically for forecasting race outcomes based on pre-race performance metrics.

## Key Features
*   Ingests and processes historical F1 session timing data.
*   Trains classification models to predict the top three finishers.
*   Evaluates model performance using accuracy and log loss metrics.
*   Modular pipeline for easy experimentation with different features and algorithms.

## Tech Stack
Python, Pandas, Scikit-learn, XGBoost, Matplotlib

## Getting Started
1.  Clone the repository: `git clone https://github.com/zoreanuj/podium-predictor-ml.git`
2.  Install dependencies: `pip install -r requirements.txt`
3.  Run the training pipeline: `python src/train_model.py`