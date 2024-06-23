# Pet Adoption Prediction with Machine Learning Using Python

## Project Overview

This project aims to predict pet adoption based on various features using multiple machine learning models. The models evaluated in this project include:
- Logistic Regression
- Support Vector Classifier (SVC)
- Decision Tree
- Random Forest
- Extra Trees
- AdaBoost
- Gradient Boosting
- XGBoost
- LightGBM
- CatBoost

Additionally, ensemble methods such as voting and stacking classifiers are employed to improve prediction accuracy. The project files are:

1. `README.md`: Detailed documentation of the project.
2. `requirements.txt`: File listing all dependencies.
3. `pet_adoption_data.csv`: The dataset used for training and testing the models.
4. `adoption_prediction.ipynb`: The Jupyter notebook containing the implementation of the models.

## Usage

1. Open the Jupyter notebook:
    ```bash
    jupyter notebook adoption_prediction.ipynb
    ```
2. Install dependencies using pip:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the cells in the notebook to:
    - Load and preprocess the dataset
    - Train the models
    - Evaluate the model performances
    - Make predictions

## Results

The results indicate that CatBoost, RandomForest, and XGBoost achieved the highest F1 scores. The models were evaluated based on accuracy and F1 score metrics to determine the best-performing model.

## Conclusion

This project demonstrates the application of machine learning in predicting pet adoption. By comparing various models and employing ensemble methods, we identified the most effective models for this task.

## Future Work

- Explore deep learning algorithms (e.g., neural networks) for potentially improved performance.
- Expand the dataset with more features and records to increase the model's robustness and generalizability.