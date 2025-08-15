# Car Price Prediction

This project predicts the selling price of used cars based on various features such as mileage, year of manufacture, fuel type, and other specifications.  
The model is built using **Python**, **pandas**, **scikit-learn**, and **matplotlib/seaborn** for visualization.

---

## 📌 Project Overview
The primary goal of this project is to:
1. Explore and clean a dataset of used cars.
2. Perform **Exploratory Data Analysis (EDA)** to understand trends and correlations.
3. Preprocess categorical and numerical features for model training.
4. Train regression models to predict car prices.
5. Evaluate model performance using suitable metrics.

---

## 📂 Dataset
The dataset contains information about various cars and their attributes.  
Common columns include:
- `Car_Name` — Name/Model of the car
- `Year` — Manufacturing year
- `Selling_Price` — Target variable (in lakhs or currency units)
- `Present_Price` — Price of the car when new
- `Driven_kms` — Total kilometers driven
- `Fuel_Type` — Petrol/Diesel/CNG
- `Seller_Type` — Dealer or Individual
- `Transmission` — Manual/Automatic
- `Owner` — Number of previous owners

> **Note:** If you are using a different dataset, update the column descriptions accordingly.

---

## ⚙️ Installation
Clone this repository and install the required dependencies:
```bash
git clone https://github.com/yourusername/car-price-prediction.git

cd car-price-prediction
pip install -r requirements.txt
```


🚀 Usage

Open the Jupyter Notebook:

jupyter notebook carprice.ipynb


Run all cells to:

Load and inspect the dataset.

Perform EDA and preprocessing.

Train machine learning models.

View predictions vs actual values.


🛠️ Machine Learning Models Used

The project may include:

Linear Regression


Random Forest Regressor



The final model is selected based on evaluation metrics such as:

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

R² Score

📊 Results

Example output (actual vs predicted):

Actual:    [4.5, 7.2, 3.0, 8.1]
Predicted: [4.3, 7.5, 2.8, 8.0]


A plot is included to visualize Actual vs Predicted Prices with a perfect prediction reference line.
