# Audience Rating Prediction

## Overview
This project predicts audience ratings using machine learning and deep learning techniques. The dataset used is the **Rotten Tomatoes Dataset**, which contains movie-related metadata such as cast, director, critics' consensus, genres, and various scores.

## Features
- **Preprocessing:**
  - Handling missing values
  - Encoding categorical variables
  - Extracting and engineering features (e.g., movie age, studio size, genre count)
  - Normalizing numerical features
  - Processing textual data using TF-IDF vectorization

- **Modeling:**
  - **Traditional ML Models:** Random Forest, XGBoost, and CatBoost Regressors
  - **Deep Learning for Text Data:** A fully connected neural network trained on textual movie metadata
  - **Ensemble Stacking:** Combining predictions from all models for improved performance

## Performance Metrics
After implementing feature engineering and hyperparameter tuning, the model achieved the following results:

- **Mean Squared Error (MSE):** 1.4927
- **Mean Absolute Error (MAE):** 0.9018
- **R² Score:** 0.9099
- **Root Mean Squared Error (RMSE):** 1.2217

## Installation & Usage
### Prerequisites
Ensure you have Python 3.8+ installed along with the following libraries:

```bash
pip install pandas numpy scikit-learn xgboost catboost tensorflow tqdm joblib
```

### Running the Model
1. Load the dataset (`rotten-tomato-dataset.csv`).
2. Execute the Jupyter Notebook cells step-by-step for preprocessing, feature extraction, and model training.
3. Evaluate the performance of the final ensemble model.

## Future Improvements
- Experiment with additional NLP techniques like transformers for better text feature extraction.
- Fine-tune hyperparameters using Bayesian optimization.
- Explore deep learning-based regression models.

## Author
Developed by Shivam Shrivastava 🚀

## License
This project is licensed under the MIT License.

