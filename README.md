# Used Car Price Analysis & Prediction

This project involves an **Exploratory Data Analysis (EDA)** and predictive modeling of a used car dataset from CarDekho. The goal is to identify the key factors that influence the resale value of vehicles and build a model to estimate prices.

## 📊 Dataset Overview

The dataset used in this project is the **Car details v3.csv** from [![Kaggle](https://img.shields.io/badge/Kaggle-035a7d?style=for-the-badge&logo=kaggle&logoColor=white)](https://www.kaggle.com/datasets/nehalbirla/vehicle-dataset-from-cardekho/data?select=Car+details+v3.csv). It contains information on over 8,000 used cars, including:
- **Selling Price:** The price at which the car is being sold (Target Variable).
- **Year:** The year of manufacture.
- **Kilometers Driven:** Total distance covered by the car.
- **Fuel Type:** Petrol, Diesel, CNG, or LPG.
- **Transmission:** Manual or Automatic.
- **Owner:** Number of previous owners.
- **Engine/Mileage/Max Power:** Technical specifications of the vehicle.



## 🚀 Key Features of the Analysis
- **Data Cleaning:** Handling missing values in engine specifications and mileage.
- **Feature Engineering:** Extracting the car brand from the `name` column and calculating the age of the vehicle.
- **Statistical Analysis:** Using heatmaps to find correlations between engine capacity and price.
- **Visualizations:** Detailed boxplots to analyze price outliers across different fuel types and transmissions.

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Tools:** Jupyter Notebook / Google Colab

## 📂 Project Structure
```text
├── data/
│   └── Car details v3.csv       # Raw dataset
├── notebooks/
│   └── car_price_eda.ipynb      # Main analysis notebook
├── README.md                    # Project documentation
└── requirements.txt             # List of dependencies
