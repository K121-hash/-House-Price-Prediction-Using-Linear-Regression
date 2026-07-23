# 🏠 House Price Prediction Using Linear Regression

## 📌 Project Overview

This project focuses on predicting house prices using machine learning techniques, specifically Linear Regression. The Ames Housing dataset was used to analyze the relationship between various housing features and property prices. The project covers the complete machine learning workflow, including data exploration, preprocessing, model training, evaluation, and interpretation.

The primary objective is to build a model capable of estimating house prices based on characteristics such as neighborhood, living area, garage size, basement quality, and other property attributes.

---

## 🎯 Objectives

The objectives of this project are to:

- Explore and understand the Ames Housing dataset.
- Perform data cleaning and preprocessing.
- Handle missing values and encode categorical features.
- Identify the features most correlated with house prices.
- Build and train a Linear Regression model.
- Evaluate the model using standard regression metrics.
- Visualize the model's predictions and residuals.
- Analyze feature coefficients to understand their impact on house prices.
- Compare Linear Regression with Ridge Regression.

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📂 Dataset

The dataset used for this project is the Ames Housing Dataset, which contains information about residential properties and their sale prices.

### Dataset Features

The dataset includes information such as:

- Lot area
- Neighborhood
- House style
- Exterior materials
- Basement quality
- Garage capacity
- Number of rooms
- Year built
- Kitchen quality
- Sale price

### Target Variable

- SalePrice

---

## 🔍 Exploratory Data Analysis (EDA)

The following analyses were performed:

- Dataset overview and structure
- Descriptive statistics
- Missing value analysis
- Duplicate check
- Distribution of house prices
- Correlation analysis
- Feature selection discussion

### Key Findings

- House prices exhibit a positively skewed distribution.
- No duplicate records were found.
- Several features contained missing values and were cleaned appropriately.
- Neighborhood, overall quality, garage capacity, and basement features showed strong relationships with house prices.

---

## 🧹 Data Preprocessing

The preprocessing stage involved:

- Handling missing values
  - Numerical features were filled using the median.
  - Categorical features were filled using the mode.
- Separating features and target variables.
- Applying One-Hot Encoding to categorical variables.
- Splitting the data into training and testing sets using an 80/20 ratio.

---

## 📊 Correlation Analysis

Correlation analysis revealed that several features strongly influence house prices, including:

- Overall quality (OverallQual)
- Living area (GrLivArea)
- Garage capacity (GarageCars)
- Garage area (GarageArea)
- Basement area (TotalBsmtSF)
- First-floor area (1stFlrSF)
- Neighborhood
- Kitchen quality

---

## 🤖 Models Used

### 1. Linear Regression

Linear Regression was used as the primary model for predicting house prices.

#### Performance Metrics

| Metric | Value |
|----------|----------:|
| Mean Squared Error (MSE) | 952,794,590.52 |
| Root Mean Squared Error (RMSE) | 30,867.37 |
| R² Score | 0.876 |

---

### 2. Ridge Regression (Bonus)

Ridge Regression was implemented to compare its performance with Linear Regression.

#### Performance Metrics

| Metric | Value |
|----------|----------:|
| Mean Squared Error (MSE) | 1,180,415,704.44 |
| Root Mean Squared Error (RMSE) | 34,357.18 |
| R² Score | 0.846 |

---

## 📈 Visualizations

The project includes:

- Distribution plot of house prices
- Correlation heatmap
- Actual vs Predicted prices scatter plot
- Residual plot
- Coefficient importance plot
- Model comparison

---

## 🔬 Coefficient Analysis

Coefficient analysis showed that location and premium property features have the strongest influence on house prices.

The most influential features include:

- Neighborhood (NoRidge, StoneBr, NridgHt)
- Pool quality
- Basement quality
- Kitchen quality
- Exterior materials
- Land contour

Positive coefficients indicate features that increase house prices, while negative coefficients represent features that reduce property value.

---

## 📌 Conclusion

The Linear Regression model achieved strong predictive performance, explaining approximately 87.6% of the variation in house prices. Comparison with Ridge Regression showed that Linear Regression produced lower prediction errors and a higher R² score.

The analysis demonstrates that neighborhood, construction quality, and premium amenities are key determinants of house prices in the Ames Housing dataset.

Future improvements may include:

- Feature engineering
- Hyperparameter tuning
- Testing advanced machine-learning models such as Random Forest and Gradient Boosting

---

## 📁 Repository Structure

```text
house-price-prediction/

├── data/
│   └── train.csv

├── notebooks/
│   └── house_price_prediction.ipynb

├── images/
│   ├── heatmap.png
│   ├── actual_vs_predicted.png
│   ├── residual_plot.png
│   └── coefficient_plot.png

├── README.md

└── requirements.txt
```

---

## 🚀 How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/your-username/house-price-prediction.git
```

2. Navigate to the project directory:

```bash
cd house-price-prediction
```

3. Install the required libraries:

```bash
pip install -r requirements.txt
```

4. Launch Jupyter Notebook:

```bash
jupyter notebook
```

5. Open and run:

```text
house_price_prediction.ipynb
```

---

## 👩‍💻 Author

**Kyauta Ayuba Dabu**

Data Analyst | Datata Scientist | Machine Learning Enthusiast | Python Developer
