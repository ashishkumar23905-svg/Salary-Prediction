# Salary-Prediction
Salary prediction project using ensemble learning models such as Random Forest, Gradient Boosting, and Voting Regressor. Includes data preprocessing, exploratory analysis, visualizations, model evaluation with MAE, RMSE, and R² score, and comparison of predicted versus actual salaries.
# Salary Prediction Using Ensemble Learning

A machine learning project that predicts employee salaries using ensemble regression techniques. The project applies data preprocessing, exploratory data analysis, feature engineering, model training, and evaluation to identify the most accurate salary prediction model.

## Project Overview

Salary prediction is a regression problem where the goal is to estimate an employee’s salary based on available input features such as experience, education, job role, age, location, and other relevant factors in the dataset.

This project uses ensemble learning methods to improve prediction performance. Ensemble models combine multiple machine learning algorithms or decision trees to produce more reliable and accurate predictions than a single model.

## Objectives

* Load and explore the salary dataset.
* Clean missing or inconsistent data.
* Perform exploratory data analysis and visualize important patterns.
* Prepare numerical and categorical features for machine learning.
* Split the dataset into training and testing sets.
* Train multiple regression models.
* Compare model performance using regression evaluation metrics.
* Select the best-performing model for salary prediction.

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## Machine Learning Models Used

The project uses ensemble regression models such as:

* **Random Forest Regressor**
  Builds multiple decision trees and combines their predictions to reduce overfitting and improve accuracy.

* **Gradient Boosting Regressor**
  Builds models sequentially, where each new model attempts to correct errors made by the previous model.

* **Voting Regressor**
  Combines predictions from multiple regression models and produces a final average prediction.

## Project Workflow

1. **Data Collection**
   The salary dataset is loaded into a Pandas DataFrame.

2. **Data Preprocessing**
   Missing values, duplicate records, incorrect data types, and categorical variables are handled before training.

3. **Exploratory Data Analysis**
   Visualizations are created to understand salary distribution, feature relationships, and possible trends in the dataset.

4. **Feature Engineering**
   Relevant features are selected and transformed into a format suitable for machine learning models.

5. **Train-Test Split**
   The dataset is divided into training and testing data to evaluate model performance on unseen records.

6. **Model Training**
   Ensemble regression models are trained using the prepared training dataset.

7. **Model Evaluation**
   Models are evaluated using standard regression metrics.

8. **Prediction and Comparison**
   Actual salary values are compared with predicted salary values to determine the best model.

## Evaluation Metrics

The following metrics are used to evaluate the performance of the models:

* **Mean Absolute Error (MAE):** Measures the average absolute difference between actual and predicted salaries.
* **Mean Squared Error (MSE):** Measures the average squared difference between actual and predicted salaries.
* **Root Mean Squared Error (RMSE):** Shows the average prediction error in the same unit as salary.
* **R² Score:** Measures how well the model explains the variation in salary values.

A lower MAE, MSE, and RMSE indicates better model performance, while a higher R² score indicates a stronger model.

## Visualizations Included

The notebook includes visualizations such as:

* Salary distribution plot
* Correlation heatmap
* Feature relationship plots
* Model comparison chart
* Actual vs. predicted salary plot
* Residual or prediction error analysis

These graphs help interpret the dataset and understand the performance of each model.

## Installation and Usage

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/salary-prediction-ensemble-learning.git
cd salary-prediction-ensemble-learning
```

### 2. Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### 3. Run the Notebook

```bash
jupyter notebook
```

Open the `Salary Prediction.ipynb` file and run all cells sequentially.

## Project Structure

```text
salary-prediction-ensemble-learning/
│
├── Salary Prediction.ipynb
├── Salary Data.csv
├── README.md
└── requirements.txt
```

## Key Findings

* Ensemble learning models can provide more accurate salary predictions than basic regression models.
* Random Forest and Gradient Boosting are effective for handling complex relationships between salary-related features.
* Proper data cleaning and feature preprocessing significantly improve model performance.
* Comparing multiple models helps select the best model based on RMSE, MAE, and R² score.
* Actual versus predicted salary plots provide a clear visual understanding of prediction quality.

## Future Improvements

* Use hyperparameter tuning with GridSearchCV or RandomizedSearchCV.
* Add more salary-related features such as skills, company size, industry, and location.
* Deploy the trained model using Flask, Streamlit, or FastAPI.
* Create an interactive dashboard for salary prediction.
* Save the best-performing model using Joblib or Pickle.
* Use larger and more diverse datasets to improve generalization.

## Conclusion

This project demonstrates how ensemble learning can be used to build an effective salary prediction system. By preprocessing the data, training multiple regression models, and comparing their evaluation metrics, the project identifies a reliable model for predicting salaries. The approach can be extended further for real-world recruitment, compensation analysis, and workforce planning applications.

## Author

**Ashish Kumar**

## License

This project is available for educational and learning purposes.
