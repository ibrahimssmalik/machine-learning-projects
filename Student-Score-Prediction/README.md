# Student Score Prediction with Machine Learning Using Python

This is a simple linear regression involving two variables. In this regression task we will predict the percentage of marks that a student is expected to score based upon the number of hours they studied. This is a simple linear regression task as it involves two variables.

## Project Overview

This project uses a Support Vector Machine (SVM) to predict loan approvals. The repository contains three files:

1. `README.md`: Documentation of the project.
2. `student_scores.csv`: The dataset used for training and testing the model.
3. `student_prediction.ipynb`: The Jupyter notebook containing the implementation of the Linear Regression model.

## Usage

1. Open the Jupyter notebook:
    ```bash
    jupyter notebook load_prediction.ipynb
    ```
2. Install dependencies using pip:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the cells in the notebook to:
    - Load and preprocess the dataset
    - Train the SVM model
    - Evaluate the model's performance
    - Make predictions

## Model Implementation

### Data Preprocessing

The dataset is preprocessed to handle missing values, encode categorical variables, and scale numerical features. This ensures that the data is in the right format for the SVM model.

### Support Vector Machine (SVM)

The SVM algorithm is used for training the model. SVM is chosen for its effectiveness in high-dimensional spaces and its ability to handle both linear and non-linear classification tasks.

### Model Evaluation

The model is evaluated using accuracy metric. This metric provides insights into the model's performance and its ability to generalize to unseen data.

## Results

The SVM model shows promising results in predicting loan approvals, with high accuracy and reliable performance metrics.

## Conclusion

This project demonstrates the application of machine learning in the finance domain, specifically in predicting loan approvals. By using historical data and SVM, financial institutions can enhance their decision-making processes, manage risks better, and improve operational efficiency.

## Future Work

- Explore other machine learning algorithms (e.g., Random Forest, Gradient Boosting) for improved performance.
- Implement hyperparameter tuning to optimize the SVM model.
- Expand the dataset with more features and records to increase the model's robustness.