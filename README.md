# Fundamentals of Supervised Machine Learning: Linear Regression

## Overview
This project explores the fundamentals of supervised machine learning through the lens of linear regression, one of the most foundational models in the field. Our journey encompasses the construction of a linear regression model, the application of feature selection techniques, and the evaluation of model performance. By integrating both machine learning algorithms and statistical methods, we aim to present a structured approach for developing predictive models that are both accurate and interpretable.

## Objectives
- To demonstrate the process of building a linear regression model from scratch.
- To apply Exploratory Data Analysis (EDA) for understanding dataset characteristics.
- To utilize feature selection methods, specifically Recursive Feature Elimination (RFE), for enhancing model performance.
- To evaluate the model using standard metrics and ensure its generalizability to unseen data.

## Dataset
The dataset focuses on customer data and includes various features with the target variable being `Yearly Amount Spent`. It is ideally structured for regression analysis, providing a mix of continuous numerical variables without missing values.

## Key Steps
1. **Exploratory Data Analysis (EDA):** Initial examination of the dataset to understand its distribution, identify potential outliers, and assess linearity and correlation among features.
2. **Data Split:** Segregation of the dataset into training and testing sets to facilitate unbiased model evaluation.
3. **Linear Regression Model Construction:** Development of a linear regression model to predict `Yearly Amount Spent` based on relevant predictors.
4. **Feature Selection:** Application of Recursive Feature Elimination (RFE) to identify and retain the most significant predictors, enhancing model simplicity and performance.
5. **Model Evaluation:** Assessment of the model's performance on test data to validate its effectiveness and generalizability.

## Tools and Libraries
- Python: Primary programming language.
- Pandas & NumPy: Data manipulation and numerical computations.
- Matplotlib & Seaborn: Data visualization.
- Statsmodels: Statistical modeling and hypothesis testing.
- Scikit-learn: Machine learning algorithms and data preprocessing.

## Installation and Usage
Before starting, ensure Python 3.11 is installed on your system. Clone this repository and navigate to the project directory. Install the required dependencies by running:
```bash
pip install -r requirements.txt
```
Navigate to the project directory and launch the Jupyter Notebook to explore the analysis:
```bash
jupyter notebook
```

## Conclusion
This project underscores the importance of a meticulous analytical approach in machine learning. Through the application of linear regression, we demonstrate how strategic feature selection and thorough model evaluation can significantly improve model accuracy and interpretability, providing valuable insights for both simple and complex predictive tasks.

## Contributing
Contributions to this project are welcome!

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.