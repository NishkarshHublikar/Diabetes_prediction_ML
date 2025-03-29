# Diabetes Prediction using Machine Learning

This project aims to predict diabetes using a machine learning model trained on the Pima Indians Diabetes Dataset.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Methodology](#methodology)
- [Results](#results)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Diabetes is a chronic disease that affects millions of people worldwide. Early detection and treatment are crucial to prevent serious complications. This project demonstrates how machine learning can be used to predict diabetes based on various health indicators.

## Dataset

The project utilizes the Pima Indians Diabetes Dataset, which contains medical information of female patients of Pima Indian heritage. The dataset includes features like pregnancies, glucose level, blood pressure, skin thickness, insulin level, BMI, diabetes pedigree function, and age. The target variable is a binary indicator of diabetes (0 or 1).

## Methodology

The project follows these steps:

1. **Data Loading and Exploration:** Load the dataset, explore its characteristics, and visualize data distributions.
2. **Data Cleaning:** Handle missing values (represented as zeros) and outliers using median imputation and winsorization, respectively.
3. **Data Preparation:** Normalize numerical features using StandardScaler.
4. **Feature Engineering:** Apply Principal Component Analysis (PCA) to reduce dimensionality.
5. **Model Training:** Train a Logistic Regression model on the PCA-transformed training data.
6. **Model Evaluation:** Evaluate the model's performance using metrics like accuracy, precision, recall, F1-score, and AUC.

## Results

The trained Logistic Regression model achieved an accuracy of 78% on the test set. Other evaluation metrics can be found in the Jupyter Notebook.

## Usage

To run this project:

1. Clone the repository.
2. Install the required dependencies (see below).
3. Open the Jupyter Notebook `Diabetes_Dataset.ipynb`.
4. Execute the cells in the notebook sequentially.

## Dependencies

- Python 3.x
- pandas
- scikit-learn
- matplotlib
- seaborn
- numpy
- scipy

You can install these dependencies using `pip install -r requirements.txt`. Create a `requirements.txt` file with the above package names and run the command in the terminal.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License.
