# Machine Learning Analysis of Iris Dataset
This code performs an analysis of the Iris dataset using several machine learning techniques.

## Data Import and Preprocessing
The code starts by importing necessary libraries such as pandas, numpy, matplotlib, and seaborn. It reads the Iris dataset using Pandas and checks the shape of the dataset, the summary statistics, the number of observations for each species, and the data types of the columns.

Next, the code performs feature engineering, starting by encoding the categorical feature using the LabelEncoder from the sklearn library. Then it performs feature selection using the SelectKBest function from the sklearn.feature_selection library, which selects the most relevant features for the model using the chi-squared test. The code then applies Principal Component Analysis (PCA) to visualize the dataset in 2D.

## Machine Learning Models
The code then proceeds to build four different models:

Linear Regression
Decision Tree Regressor
Support Vector Regression
Neural Network
For each model, it splits the data into training and testing sets and evaluates the accuracy of the model using relevant metrics such as the R^2 score, Mean Squared Error, Mean Absolute Error, and accuracy.

## Conclusion
Overall, the code provides an excellent example of how to perform data analysis and build machine learning models using Python libraries. It is a great resource for anyone interested in learning how to work with machine learning and perform data analysis.
