# Insurance Cost Prediction Using Regression

## Project Overview
This project explores regression algorithms to predict individual medical insurance charges based on personal and demographic features. It was developed as part of a Machine Learning mini project using Python and Scikit-learn.

The project focuses on data exploration, preprocessing, model training, and evaluation to understand how different regression techniques perform on the insurance cost prediction task.

## Algorithms
The project explores the following regression algorithms:

- **Ridge Regression (L2):** Uses L2 regularization to reduce the impact of large model coefficients.
- **Lasso Regression (L1):** Uses L1 regularization and can reduce some coefficients to zero.
- **Elastic Net:** Combines L1 and L2 regularization.

## Dataset
The project uses the Medical Cost Personal Dataset, which contains information about individuals and their medical insurance charges.

Example features include:
- `age`
- `sex`
- `bmi`
- `children`
- `smoker`
- `region`

**Target variable:** `charges`

## Project Objectives
- Explore the dataset using Exploratory Data Analysis (EDA).
- Identify features and the target variable.
- Visualize important relationships in the data.
- Handle missing values and preprocess features as needed.
- Train and evaluate the regression models.
- Compare model performance and interpret the results.

## Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Model Evaluation
The models are evaluated using regression metrics:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

These metrics help assess prediction errors and compare model performance.

## Project Structure

```text
Insurance-Cost-Regression/
├── Mini_project1.ipynb
└── README.md
```

## How to Run the Project

1. Clone or download this repository.
2. Install the required Python libraries.
3. Open the Jupyter Notebook.
4. Run the cells in order to explore the data, train the models, and evaluate their performance.

Install the main dependencies using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

## Team Members
- Basmah Al-Muntasir
- Fahad Al-Nahi
- Reham Al-Faqiri
- Raghad Al-Harbi

## Conclusion
This project provides practical experience in applying regularized regression algorithms to a real-world prediction problem. It demonstrates the machine learning workflow, from exploratory data analysis and preprocessing to model evaluation and comparison.
