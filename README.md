# OIBSIP-DataScience-Task2-CarPricePrediction
## 📌 Project Overview

This project focuses on predicting the selling price of used cars using machine learning regression algorithms. The model analyzes vehicle-related features such as car name, manufacturing year, kilometres driven, fuel type, seller type, transmission, and ownership history to estimate the selling price.

The project demonstrates how machine learning can be used to analyze used-car data and support price estimation.

## 🎯 Objectives

- Analyze and understand the used-car dataset.
- Perform data cleaning and preprocessing.
- Conduct exploratory data analysis (EDA) using visualizations.
- Apply feature engineering to improve model inputs.
- Train and compare multiple regression algorithms.
- Evaluate model performance using standard regression metrics.
- Identify important features influencing car-price predictions.

## 📂 Dataset

The project uses a CarDekho used-car dataset containing vehicle details and their selling prices.

**Dataset features include:**
- `name` – Name of the car
- `year` – Manufacturing year
- `selling_price` – Selling price of the car (target variable)
- `km_driven` – Distance travelled by the car
- `fuel` – Fuel type
- `seller_type` – Type of seller
- `transmission` – Transmission type
- `owner` – Previous ownership information

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## ⚙️ Project Workflow

1. **Data Loading:** Import the dataset into a Pandas DataFrame.
2. **Data Cleaning:** Handle missing values, duplicate records, and invalid data.
3. **Feature Engineering:** Create additional features such as car age and brand.
4. **Exploratory Data Analysis:** Visualize price distributions and relationships between vehicle features.
5. **Data Preprocessing:** Apply scaling and one-hot encoding.
6. **Model Training:** Train multiple regression models.
7. **Model Evaluation:** Compare model performance using MAE, RMSE, and R² score.
8. **Feature Importance:** Identify features that contribute to prediction performance.
9. **Price Prediction:** Use the best-performing model to estimate car selling prices.

## 🤖 Machine Learning Algorithms

The following regression algorithms are implemented:

- **Linear Regression**
- **Random Forest Regressor**
- **Gradient Boosting Regressor**

## 📊 Model Evaluation

The models are evaluated using the following metrics:

- **Mean Absolute Error (MAE):** Measures the average absolute prediction error.
- **Root Mean Squared Error (RMSE):** Measures prediction error while giving greater weight to larger errors.
- **R² Score:** Measures how well the model explains variations in selling prices.

The models are compared to identify the best-performing algorithm on the test dataset.

## 📈 Results

The project produces a comparison of regression models based on their evaluation metrics. It also includes visualizations comparing actual and predicted prices, residual analysis, and feature importance.

The best-performing model is selected based on its test-set performance.

## 🚀 Future Improvements

- Include additional vehicle features to improve prediction accuracy.
- Experiment with advanced regression algorithms and hyperparameter tuning.
- Develop a web application for interactive car-price prediction.
- Use larger and more diverse datasets to improve model generalization.

## 📚 Learning Outcomes

- Understanding regression-based machine learning.
- Performing data cleaning and feature engineering.
- Conducting exploratory data analysis.
- Applying preprocessing techniques to numerical and categorical data.
- Training and evaluating multiple machine learning models.
- Interpreting model performance and feature importance.

## 🙌 Acknowledgement

This project was completed as part of the **Oasis Infobyte Summer Internship Program (SIP)** under the Data Science track.

## 📌 Disclaimer

This project is developed for educational and internship purposes. The predicted selling prices are estimates based on the available dataset and may differ from actual market prices.

---

**Internship:** Oasis Infobyte SIP  
**Track:** Data Science  
**Task:** Car Price Prediction Using Machine Learning
