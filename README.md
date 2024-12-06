# Music Genre Classification

This repository contains code for classifying music genres using pre-extracted audio features. The approach employs an enhanced Feedforward Neural Network (FFN) with batch normalization and dropout layers, combined with SMOTE for class imbalance and hyperparameter tuning via Optuna.

## Key Features
- **Data Preprocessing:** Handles missing values, applies log transformations to skewed features, and scales input data.
- **Exploratory Analysis:** Uses PCA and t-SNE to visualize feature distributions and genre overlaps.
- **Model Architecture:** A customizable FFN leveraging batch normalization, dropout, and cross-entropy loss with class weights.
- **Hyperparameter Optimization:** Utilizes Optuna to systematically improve performance metrics.
- **Results:** Achieves improved accuracy, precision, recall, F1-score, and AUC-ROC after tuning.
