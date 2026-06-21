#  Agency21 Real Estate Price Prediction

> End-to-end machine learning solution developed as a simulated client project for Agency21 to predict residential property prices using multiple regression models.


# Business Problem

Agency21 is a real estate company that needs a reliable and data-driven approach to estimate residential property prices. Traditional manual valuation methods can be inconsistent, time-consuming, and influenced by human judgment.

To address this challenge, a machine learning solution was developed to predict house prices based on property features. This enables faster, more consistent, and data-driven pricing decisions.

> **Note:** This project is a simulated industry case study created for learning and portfolio purposes. It is not an official project of Agency21.


# Project Objectives

- Build an accurate house price prediction model.
- Compare multiple machine learning regression algorithms.
- Select the best-performing model based on evaluation metrics.
- Save the trained model for future use.
- Demonstrate how the model can be deployed for real-world predictions.


# Machine Learning Models Used

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor


# Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Joblib
- Jupyter Notebook


# Project Workflow

1. Data collection and loading
2. Data preprocessing
3. Feature selection
4. Model training
5. Model evaluation
6. Performance comparison
7. Model serialization using Joblib
8. Prediction using the saved model


# Project Structure

```
ML PROJECT/
│
├── Agency21_Price_Prediction.ipynb         # Main notebook containing the complete ML pipeline
├── Agency21.joblib                     # Saved trained machine learning model
├── data.csv                            # Housing dataset
├── housing_dataset.xlsx                   # Housing dataset (Excel format)
├── housing.names.txt                   # Dataset description
├── Model_Usage.ipynb                   # Demonstrates how to load and use the trained model
└── model_comparison_results.txt   # Performance comparison of all trained models
```


# Model Evaluation

Three regression algorithms were trained and evaluated to determine the most suitable model for predicting house prices.

The project compares:

- Decision Tree Regression
- Linear Regression
- Random Forest Regression

Their evaluation results are included in the **outputs from different models.txt** file.


# Using the Trained Model

The repository includes a separate notebook demonstrating how to load the saved model and make predictions.

Example:

```python
from joblib import load

model = load("Agency21.joblib")

prediction = model.predict(new_data)
```


# Business Impact

This solution demonstrates how machine learning can support a real estate agency by:

- Improving property price estimation accuracy.
- Reducing manual valuation effort.
- Supporting faster pricing decisions.
- Assisting agents with data-driven recommendations.
- Providing a scalable solution for future property listings.


# Future Improvements

- Hyperparameter tuning for improved accuracy.
- Feature engineering using additional property information.
- Deployment as a web application using Flask or Streamlit.
- Integration with real-time property databases.
- Interactive dashboard for price prediction.


# Author

**Iman Fatima**

BS Software Engineering

Machine Learning | Data Science Enthusiast
