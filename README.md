# 🏠 Housing Price Prediction - Linear Regression (AIML Internship Task 3)

## 📌 Task Objective
Implement and understand **Simple & Multiple Linear Regression** using the **Housing Price Prediction** dataset. The goal is to predict house prices based on various independent variables like area, number of bedrooms, bathrooms, etc.

---

## 🛠️ Tools Used
- Python
- Pandas
- NumPy
- Matplotlib & Seaborn
- Scikit-learn

---

## 📂 Dataset
- File: `Housing.csv`
- Source: [Kaggle - Housing Price Prediction](https://www.kaggle.com/datasets/harishkumardatalab/housing-price-prediction)
- Description: The dataset contains features like area, bedrooms, bathrooms, furnishing status, parking, etc., and the target variable is the price.

---

## 📈 Workflow

### 1. Data Loading & Exploration
- Loaded the dataset using Pandas
- Checked for null values, datatypes, and basic statistics

### 2. Data Preprocessing
- Converted categorical features to numerical using `pd.get_dummies()`
- Dropped unnecessary columns (if any)
- Handled any missing values (none found in this case)

### 3. Feature Selection
- Chose `price` as the target variable (y)
- All other columns as features (X)

### 4. Data Splitting
- Split the data into training and testing sets using `train_test_split`

### 5. Model Building
- Used `LinearRegression()` from Scikit-learn
- Trained the model on the training set

### 6. Model Evaluation
Evaluated the model using:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

### 7. Visualization
- Plotted Actual vs Predicted Prices
- Visualized coefficient interpretation

---

## 📊 Evaluation Metrics

| Metric | Value |
|--------|-------|
| MAE    | _e.g., 570000.23_ |
| MSE    | _e.g., 450000000.32_ |
| R²     | _e.g., 0.79_ |

_(Values will depend on the specific run)_

---

## 📉 Coefficients Interpretation
| Feature         | Coefficient |
|----------------|-------------|
| area           | +342.55     |
| bedrooms       | +110000.33  |
| ...            | ...         |

Higher positive coefficients suggest more influence on increasing price.

---

## 📁 Repository Contents
- `Housing.csv` - Dataset
- `Task3.ipynb` - Jupyter Notebook with complete implementation
- `README.md` - Project description and summary

---

## ✅ Learnings
- Understood Linear Regression assumptions and limitations
- Learned to preprocess data and evaluate regression models
- Practiced model visualization and interpretation

---

