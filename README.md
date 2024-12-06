# Music Genre Classification

This repository contains code for classifying music genres using pre-extracted audio features. The approach employs an enhanced Feedforward Neural Network (FFN) with batch normalization and dropout layers, combined with SMOTE for class imbalance and hyperparameter tuning via Optuna.

## Key Features
- **Data Preprocessing:** Handles missing values, applies log transformations to skewed features, and scales input data.
- **Exploratory Analysis:** Uses PCA and t-SNE to visualize feature distributions and genre overlaps.
- **Model Architecture:** A customizable FFN leveraging batch normalization, dropout, and cross-entropy loss with class weights.
- **Hyperparameter Optimization:** Utilizes Optuna to systematically improve performance metrics.
- **Results:** Achieves improved accuracy, precision, recall, F1-score, and AUC-ROC after tuning.

## Getting Started
1. Clone the repository.
2. Install dependencies from `requirements.txt` (if provided).
3. Run the preprocessing and training scripts to reproduce results.

## Future Work
- Incorporate additional features or explore raw audio signals.
- Experiment with attention mechanisms or transformer-based architectures.

## License
Distributed under the MIT License. See `LICENSE` for more information.
