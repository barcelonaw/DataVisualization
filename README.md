# Data Preprocessing and Transformation / Data Analysis and Linear Regression / Tableau Portfolio


## Concepts Covered

### Library Import

- Importing essential libraries: Pandas, NumPy, Matplotlib, preprocessing from sklearn, cluster from sklearn, and auth and files from google.colab.

### Data Preprocessing

- Loading datasets ('insurance.csv' and 'Admission_Predict_Ver1.1_small_data_set_for_Linear_Regression.csv') using Pandas.
- Dropping unnecessary columns using the `drop` function.
- Normalizing numeric columns using the `normalize_numeric_minmax` function.

### Simple Linear Regression

- Implementing simple linear regression using Scikit-learn's `LinearRegression`.
- Splitting the data into training and testing sets using `train_test_split`.
- Predicting values using the linear regression model.
- Visualizing and evaluating model performance with scatter plots, root mean squared error (RMSE), and R-squared (coefficient of determination).

### Multiple Linear Regression

- Extending the analysis to multiple linear regression.
- Selecting features ('age' and 'bmi') for input and 'charges' as the output.
- Fitting a multiple linear regression model using Scikit-learn.
- Performing analysis using Statsmodels' Ordinary Least Squares (OLS) method.
- Visualizing predictions and model surface in a 3D space.

### Data Visualization

- Visualizing relationships using Seaborn's `pairplot`.
- Creating scatter plots to compare true and predicted values for different sets.

### Data Transformation Functions

- Defining `to_xy` function to transform DataFrame columns into features and labels suitable for machine learning, encoding the target variable based on its data type.
- Defining `encode_text_index` function to encode text values to numerical indexes using label encoding.

### Initialization Function

- Creating a class constructor, `__init__`, with parameters for cluster count (`k`), random seed (`seed`), and maximum iterations (`max_iter`).

### Dummy Encoding Function

- Implementing `encode_text_dummy` function to create dummy variables from categorical data and appending them to the DataFrame.

### Google Colab Authentication and Data Upload

- Demonstrating how to authenticate users via Google Colab and enabling file uploads.

### Data Loading and Preprocessing

- Reading a CSV file ('imdb_dataset.csv') into the `data` DataFrame using Pandas.
- Handling missing data by dropping columns with all missing values.
- Selecting columns with numerical data types, excluding those with data type 'object'.
- Checking for missing values within the dataset.
- Excluding rows with infinite values.

### Displaying Processed Data

- Displaying the processed `data` DataFrame, providing insights into the cleaned numerical data after preprocessing steps.

