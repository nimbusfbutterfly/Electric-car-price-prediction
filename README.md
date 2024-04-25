# Topic: Electric Car Price Prediction

## Purpose
The purpose of this section is to understand linear and polynomial regression and the various methods for obtaining algorithm parameters.

## Dataset
The dataset used in this section is "EVs - One Electric Vehicle Dataset – Smaller", containing 13 features that affect the price of electric cars. The target column has different price values for these cars.

The dataset is accessible at the following link. Download it to get started:
[Download Dataset](https://www.kaggle.com/datasets/geoffnel/evs)

**Note**: Use the clean version of the dataset.

## Task Description

### Data Preprocessing and Understanding
To use machine learning algorithms and get the right answers, you need to preprocess the data before use. The following steps are required for this section:

1. **Identify Numeric and Categorical Data**:
   Identify numeric and categorical data, then assign numeric values to each unique categorical value in each feature.
   - **Hint**: Use one-hot encoding to convert categorical values to numeric.

2. **Normalize the Data**:
   Normalize the data to ensure consistent scales across features.

3. **Perform Exploratory Data Analysis (EDA)**:
   - Plot histograms and data distributions to understand the dataset's structure.

### Linear Regression
1. **Data Split**:
   Split the available dataset into training and testing with an 80/20 ratio.

2. **Calculate Linear Regression Parameters**:
   - Using the training set, compute linear regression parameters through three methods:
     1. Direct method
     2. Batch Gradient Descent
     3. Stochastic Gradient Descent
   - Record the training time for each method.

3. **Report MSE and R-Squared**:
   - Using the test dataset, report Mean Squared Error (MSE) and R-Squared for each method.

### Polynomial Regression
1. **Data Split**:
   Split the dataset into training and testing with an 80/20 ratio.

2. **Calculate Best Polynomial Degree**:
   - Using the training set, an SGD optimizer, and K-fold Cross-validation, calculate the best polynomial degree for the regression algorithm.
   - **Hint**: Plot the MSE curve against the polynomial degree to find the optimal "knee" point.

3. **Report MSE and R-Squared**:
   - Using the test dataset and the trained model, report MSE and R-Squared values.

### Ridge and Lasso
1. **Data Split**:
   Split the dataset into training and testing with an 80/20 ratio.

2. **Choose an Overfitting Degree**:
   Choose a polynomial degree that is known to cause overfitting for the regression.

3. **Compute Best Regularization Coefficients**:
   - Using the training dataset, an SGD optimizer, and K-fold Cross-validation, compute the best regularization coefficients for both Ridge and Lasso regression.
   
4. **Report MSE and R-Squared**:
   - With the test dataset and trained models, report MSE and R-Squared for both Ridge and Lasso regression.

