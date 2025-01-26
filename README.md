# California Housing Price Prediction

This project demonstrates the application of various regression algorithms to predict median house values in California using the **California Housing Dataset** from `sklearn`. The dataset contains information about house features and prices, providing an excellent opportunity to explore supervised learning techniques.

---

## **Objective**
The objective of this project is to evaluate regression algorithms and compare their performance on the California Housing dataset. Metrics such as **Mean Squared Error (MSE)**, **Mean Absolute Error (MAE)**, and **R-squared (R²)** are used to determine the best-performing model.

---

## **Key Components**

### 1. **Data Loading and Preprocessing**
- The California Housing dataset was loaded using `fetch_california_housing` from `sklearn`.
- The data was converted into a pandas DataFrame for easier manipulation.
- Preprocessing steps included:
  - Handling missing values (if any).
  - Standardizing features using `StandardScaler`.

### 2. **Regression Algorithms Implemented**
The following regression algorithms were trained and evaluated:
- **Linear Regression**
- **Decision Tree Regressor**
- **Random Forest Regressor**
- **Gradient Boosting Regressor**
- **Support Vector Regressor (SVR)**

### 3. **Model Evaluation**
The performance of each algorithm was evaluated using:
- **Mean Squared Error (MSE)**
- **Mean Absolute Error (MAE)**
- **R-squared Score (R²)**

---

## **Results**

| Algorithm                | MSE       | MAE       | R²         |
|--------------------------|-----------|-----------|------------|
| Linear Regression        | 0.5559    | 0.5332    | 0.5758     |
| Decision Tree Regressor  | 0.4940    | 0.4539    | 0.6230     |
| Random Forest Regressor  | 0.2552    | 0.3274    | 0.8053     |
| Gradient Boosting Regressor | 0.2940 | 0.3717    | 0.7756     |
| Support Vector Regressor | 0.3570    | 0.3986    | 0.7276     |

### **Best-Performing Algorithm**
- **Random Forest Regressor**: Achieved the lowest MSE and MAE, and the highest R² score of 0.8053, making it the most effective model for this dataset.

### **Worst-Performing Algorithm**
- **Linear Regression**: Its assumption of a linear relationship between features and the target variable led to the highest error metrics and the lowest R² score of 0.5758.

---

## **Technologies Used**
- **Python**: Programming language for implementation.
- **Jupyter Notebook**: Interactive environment for coding and visualization.
- **Libraries**: 
  - `pandas`: Data manipulation and analysis.
  - `sklearn`: Machine learning algorithms and utilities.
  - `numpy`: Numerical computations.

---

