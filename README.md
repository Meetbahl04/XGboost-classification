# Breast Cancer Prediction using XGBoost Classifier
This repository contains an implementation of a machine learning model using the XGBoost (Extreme Gradient Boosting) algorithm to classify whether a breast tumor is benign or malignant based on features extracted from cell samples.

#### Dataset Description
The dataset used for this classification task includes various features extracted from breast cancer cell nuclei. These features are:

<ul>
    <li><strong>Clump Thickness:</strong> Measures the thickness of cell clumps.</li>
    <li><strong>Uniformity of Cell Size:</strong> Consistency in the size of the cells.</li>
    <li><strong>Uniformity of Cell Shape:</strong> Consistency in the shape of the cells.</li>
    <li><strong>Marginal Adhesion:</strong> How closely the cells stick to one another.</li>
    <li><strong>Single Epithelial Cell Size:</strong> Size of single epithelial cells.</li>
    <li><strong>Bare Nuclei:</strong> Presence of bare nuclei.</li>
    <li><strong>Bland Chromatin:</strong> Texture of the chromatin in the cell.</li>
    <li><strong>Normal Nucleoli:</strong> Number of nucleoli present in the nucleus.</li>
    <li><strong>Mitosis:</strong> Frequency of cell division.</li>
</ul>

## Target Variable
#### Class: The target variable is binary:
</ul>
            <li><strong>2</strong> : Benign</li>
            <li><strong>4</strong> : Malignant</li>
</ul>

## XGBoost Classifier
XGBoost is an optimized gradient boosting framework that uses decision trees for classification and regression tasks. It is known for its speed and performance, making it an excellent choice for this type of binary classification problem.

## Steps in this Repository
#### Data Preprocessing:

Handle missing values and standardize the data for training.
Convert the target variable into a binary label (0: benign, 1: malignant).
Feature Engineering:

Perform basic exploratory data analysis (EDA) to understand the feature importance and relationships.
#### Model Training:

Utilize XGBoost to train the classification model on the dataset.
Perform hyperparameter tuning (using Grid Search or Randomized Search) to optimize the model's performance.
#### Model Evaluation:

Evaluate the model using common classification metrics such as accuracy, precision, recall, and F1-score.
Use a confusion matrix to visualize the performance of the model on the test data.
## Key Dependencies
xgboost: The core library for training the model.
scikit-learn: For preprocessing, model evaluation, and splitting the dataset.
pandas: For data manipulation.
matplotlib/seaborn: For visualizations.
