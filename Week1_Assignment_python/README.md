# California Housing Price Prediction using Linear Regression

## Project Overview

This project analyzes the California Housing dataset and builds machine learning models to predict median house values.

The project follows the complete Data Science workflow:

- Data Import and Inspection
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Insights and Observations
- Simple Linear Regression
- Multiple Linear Regression
- Data Visualization
- Model Evaluation
- Conclusion and Reflection

The dataset used is the California Housing dataset available in the Scikit-learn library.

---

## Dataset

Source:
California Housing Dataset (Scikit-learn)

Target Variable:
- MedHouseVal (Median House Value)

Features:
- MedInc
- HouseAge
- AveRooms
- AveBedrms
- Population
- AveOccup
- Latitude
- Longitude

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## How to Run the Project

### 1. Clone the repository

```bash
git clone <repository-link>
```

### 2. Open the project folder

```bash
cd California-Housing-Regression
```

### 3. Install the required libraries

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 5. Open

```
California_Housing_Regression.ipynb
```

Run all cells from top to bottom.

---

## Project Workflow

1. Import Dataset
2. Inspect Data
3. Clean Data
4. Perform EDA
5. Build Simple Linear Regression Model
6. Evaluate Model
7. Build Multiple Linear Regression Model
8. Compare Models
9. Draw Conclusions

---

## Model Evaluation Metrics

The models were evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## Key Findings

1. Median Income has the strongest positive correlation with Median House Value.

2. The dataset was mostly clean, but missing values, duplicates, and invalid values were intentionally introduced and handled to practice data cleaning.

3. Exploratory Data Analysis showed that most numerical features are positively skewed and contain several outliers.

4. Simple Linear Regression using only Median Income explained approximately 46% of the variation in house prices (R² ≈ 0.46).

5. Multiple Linear Regression performed better than Simple Linear Regression because it used all available features to make predictions.

6. Latitude and Longitude also influence house prices, showing that geographical location is an important factor.

7. Proper data cleaning and feature selection significantly improve the quality and reliability of machine learning models.

---

## Learning Outcomes

Through this project, I learned how to:

- Import and inspect datasets
- Clean real-world data
- Perform Exploratory Data Analysis
- Visualize data effectively
- Build Simple and Multiple Linear Regression models
- Evaluate machine learning models using different performance metrics
- Interpret regression results and model performance

---
