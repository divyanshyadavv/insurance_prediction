# insurance_prediction
Basic comparison between different models for insurance charge predction, regression model.
Here’s a clean, professional example of how you can write your `README.md` file for a GitHub project that involves EDA, traditional ML models (like SVR and Decision Trees), and neural networks:

---

# Medical Charges Prediction 🏥💰

This project focuses on predicting individual medical charges based on personal and demographic features using various machine learning models and a neural network.

## 🔍 Exploratory Data Analysis (EDA)

The project begins with thorough EDA to understand the relationships between features such as:

* Age, BMI, smoking status, and region with respect to insurance charges
* Distributions and outliers
* Correlations and patterns

Visualizations and summary statistics were used to derive insights and clean the dataset before modeling.

## ⚙️ Machine Learning Models

After EDA and preprocessing (including encoding categorical variables and splitting the data), several regression models were tested:

* **Support Vector Regressor (SVR)**
* **Decision Tree Regressor**
* **Random Forest Regressor**

Each model was evaluated using metrics such as:

* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

## 🤖 Neural Network Implementation

A deep learning model was built using TensorFlow and Keras. The architecture consisted of:

* **Input layer** with ReLU activation
* **Two hidden layers** with 64 and 32 neurons respectively
* **Output layer** with a single node for regression output

Before training, feature scaling was applied using `StandardScaler` for better performance.


---

