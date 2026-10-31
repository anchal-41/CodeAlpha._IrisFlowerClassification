# Car Price Prediction Using Machine Learning

## Project Overview
This project focuses on predicting the selling price of used cars using Machine Learning. A Random Forest Regression model is trained using car-related features such as present price, kilometres driven, fuel type, seller type, transmission, and car age.

## Objective
The main objective is to build a machine learning model that can estimate the selling price of a used car based on its characteristics.

## Dataset
- **Dataset:** CarDekho Used Car Dataset
- **Target Variable:** `Selling_Price`
- **Features:**
  - Present_Price
  - Kms_Driven
  - Fuel_Type
  - Seller_Type
  - Transmission
  - Owner
  - Car_Age

## Technologies Used
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Project Workflow

1. **Data Loading:** Loaded the CarDekho dataset using Pandas.
2. **Data Cleaning:** Checked and handled missing values and duplicate records.
3. **Feature Engineering:** Created a new feature called `Car_Age`.
4. **Exploratory Data Analysis:** Visualized car prices and explored relationships between features.
5. **Data Preprocessing:** Applied One-Hot Encoding to categorical features.
6. **Train-Test Split:** Divided the dataset into 80% training data and 20% testing data.
7. **Model Building:** Used Random Forest Regressor.
8. **Model Training:** Trained the model using the training dataset.
9. **Model Evaluation:** Evaluated performance using MAE, MSE, RMSE, and R² Score.
10. **Price Prediction:** Predicted the selling price of a new car.

## Machine Learning Algorithm
**Random Forest Regression**

Random Forest is an ensemble learning algorithm that combines multiple decision trees to produce predictions. It is used here for predicting continuous values such as car selling prices.

## Model Evaluation
The model is evaluated using:

- **MAE:** Mean Absolute Error
- **MSE:** Mean Squared Error
- **RMSE:** Root Mean Squared Error
- **R² Score:** Coefficient of Determination

## How to Run the Project

1. Clone or download this repository.
2. Open the notebook `car_price_prediction.ipynb` in Google Colab.
3. Run the notebook cells sequentially.
4. View the data analysis, model evaluation, graphs, and sample price prediction.

## Project Structure

```text
CodeAlpha_Project/
│
├── car_price_prediction.ipynb
└── README.md
```

## Conclusion
This project demonstrates how Machine Learning can be used to estimate used car prices. The Random Forest Regression model learns patterns from historical car data and predicts prices based on different car features.

## Internship
**CodeAlpha Data Science Internship**

**Task 3: Car Price Prediction with Machine Learning**
