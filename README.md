# Salary Prediction with Linear Regression

## Project Overview

This project demonstrates a simple yet powerful application of machine learning: predicting an employee's salary based on their years of experience. By leveraging a linear regression model, we can uncover the underlying relationship between these two variables and create a predictive tool. This project is an excellent introduction to the fundamentals of machine learning, including data loading, model training, evaluation, and visualization.

## Dataset

The project utilizes the `Salary_dataset.csv` file, a clean and straightforward dataset perfect for introductory machine learning tasks. The dataset consists of two primary columns:

*   **YearsExperience**: A numerical value representing the number of years of experience.
*   **Salary**: The corresponding salary for that level of experience.

## Modeling and Evaluation

A **Linear Regression** model, provided by the powerful scikit-learn library, was chosen for this task. The model was trained on a portion of the dataset and then evaluated on a separate, unseen portion to test its predictive accuracy. The model's performance was assessed using two key metrics:

*   **Mean Squared Error (MSE)**: This metric measures the average of the squares of the errors—that is, the average squared difference between the estimated values and the actual value.
*   **R-squared (R²)**: This metric provides an indication of the goodness of fit of a set of predictions to the actual values. In other words, it represents the proportion of the variance in the dependent variable that is predictable from the independent variable(s).

The model achieved a high **R-squared value of 0.94**, indicating that it explains 94% of the variance in salary based on years of experience, a strong indicator of a well-fitting model.

## How to Reproduce this Project

To run this project on your own machine, you'll need Python and a few essential libraries.

1.  **Clone the repository:**
