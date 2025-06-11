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



# Assignment 4 - Classification Problem

# Steps done
1. The objective was to apply supervised learning techniques to a real-world classification problem.
2. The Breast Cancer Wisconsin Diagnostic Dataset from sklearn was used.
3. The dataset was checked for missing values, and no missing data was found.
4. Feature scaling was performed using StandardScaler.
5. The dataset was split into training and testing sets using an 80-20 ratio.
6. Logistic Regression was implemented as a linear classification model.
7. Decision Tree Classifier was implemented to model non-linear decision rules.
8. Random Forest Classifier was implemented as an ensemble of decision trees.
9. Support Vector Machine (SVM) was implemented to find the optimal separating hyperplane.
10. k-Nearest Neighbors (k-NN) was implemented for instance-based classification.
11. All models were evaluated based on accuracy scores.
12. Support Vector Machine (SVM) achieved the highest accuracy.
13. Decision Tree Classifier had the lowest accuracy among the models.



# Assignment 5 - Clustering Algorithm

# Steps done
1. Loaded the Iris dataset using sklearn.datasets.load_iris().
2. Dropped the target/species column to make it suitable for unsupervised learning (clustering).
3. Applied KMeans clustering with n_clusters=3 to group data into 3 clusters.
4. Explained how KMeans works (centroid-based, iterative algorithm).
5. Described why KMeans is suitable for the Iris dataset (numerical features, natural clusters).
6. Used PCA for dimensionality reduction to visualize clusters in 2D space.
7. Applied Hierarchical clustering using the agglomerative approach and ward linkage.
8. Plotted a dendrogram to visualize the hierarchical relationships between data points.
9. Formed 3 clusters from the dendrogram using fcluster() function.
10. Visualized both clustering results (KMeans & Hierarchical) using scatter plots with PCA components.



# Project - Machine Learning module end project

# Steps done
1. Imported all necessary libraries.
2. Loaded the dataset using pandas.
3. Explored and understood the structure of the dataset.
4. Cleaned the data and handled missing or irrelevant values.
5. Converted categorical features into numerical values using encoding techniques.
6. Scaled numerical features for consistent model input.
7. Split the dataset into training and testing sets.
8. Implemented Linear Regression model.
9. Implemented Decision Tree Regressor model.
10. Implemented Random Forest Regressor model.
11. Implemented Gradient Boosting Regressor model.
12. Implemented Support Vector Regressor (SVR) model.
13. Evaluated all models using R² Score, Mean Squared Error (MSE), and Mean Absolute Error (MAE).
14. Identified Random Forest as the best performing model.
15. Analyzed feature importance using Random Forest.
16. Found engine size and curb weight as top influencing features.
17. Performed hyperparameter tuning using GridSearchCV.
18. Optimized Random Forest model with best parameters.
19. Final tuned model achieved R² score of 0.9549.
20. Concluded Random Forest as the most accurate and reliable model for predicting car prices.

