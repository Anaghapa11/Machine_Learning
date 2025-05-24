# Machine Learning

# Assignment 1 - Statistical Measures 

# Steps done
1. Checked dataset info, missing values, and summary stats.
2. Used 4 methods:
Mean ± 3*STD,Percentile (5%-95%),IQR,Z-Score.
3. Compared each method to visualize outlier removal.
4. Used histplot, skewness & kurtosis and Applied log transformation to reduce skewness.
5. Plotted heatmap of numerical features.
6. Visualized relationships (price, sqft, price/sqft).


# Assignment 2 - EDA and Preprocessing

# Steps done
1. Loaded the dataset and standardized column names.
2. Explored data: viewed structure, stats, and unique values.
3. Replaced invalid age values (0) with NaN.
4. Handled missing values using mean/median/mode.
5. Removed duplicates and identified outliers using IQR.
6. Filtered data (age > 40, salary < 5000) for analysis.
7. Visualized age vs. salary and people count by place.
8. Encoded categorical features (Label + One-Hot Encoding).
9. Scaled numeric features using StandardScaler and MinMaxScaler.
10. Saved cleaned and scaled datasets for ML use.


# Assignment 3 - Regression

# Steps done
1. Imported necessary libraries for data manipulation, modeling, and evaluation.
2. Loaded the California Housing dataset using fetch_california_housing from sklearn.
3. Converted the dataset into a pandas DataFrame for structured analysis.
4. Explored the dataset and verified that there were no missing values.
5. Separated features and target variable (MedHouseValue) for modeling.
6. Applied feature scaling using StandardScaler to standardize input features.
7. Split the dataset into training and testing sets using an 80-20 ratio.
8. Implemented Linear Regression to model linear relationships in the data.
9. Trained Decision Tree, Random Forest, Gradient Boosting, and Support Vector Regressor models.
10. Evaluated each model using Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared (R²) metrics.
11. Compared model performance and found Random Forest to be the best and Linear Regression to be the least accurate.





