# Project Overview
This project demonstrates the complete workflow of a machine learning project, starting from data loading and cleaning, to training multiple models and evaluating their performance. The primary objective is to build a predictive model that can accurately determine whether a patient has diabetes based on their medical attributes.

# Libraries Used
The project utilizes the following libraries:

- Pandas for data manipulation and analysis.
- NumPy for numerical computations.
- Matplotlib for data visualization.
- Scikit-learn for machine learning algorithms and data preprocessing.
# Workflow
1. Importing Libraries
We start by importing the necessary libraries for data manipulation, visualization, and machine learning.

2. Loading Data
The dataset is loaded from an Excel file.

3. Data Cleaning
3.a. Checking for Null Values
We check for any null or NaN values in the dataset.

3.b. Checking for Correlated Columns
We analyze the correlation matrix to identify highly correlated columns. Based on the correlation analysis, we drop certain columns to avoid redundancy.

3.c. Converting Text Data to Integer
We convert the diabetes column from boolean to integer.

4. Data Balancing Check
We check the distribution of the diabetes column to ensure the data is balanced.

5. Splitting Data
We split the data into training and testing sets to evaluate the model's performance on unseen data.

6. Handling Missing Values
We replace zero values in the dataset with the mean value to handle missing data.

7. Training and Testing Models
We train and test various machine learning models and evaluate their performance. The models used include:

- Naive Bayes
- Random Forest
- Logistic Regression
- Decision Tree
- K-Nearest Neighbors
- Support Vector Machine
8. Model Evaluation
We evaluate the models using metrics such as accuracy, confusion matrix, and classification report to determine their effectiveness.

# Conclusion
This project demonstrates the end-to-end process of building and evaluating machine learning models for predicting diabetes. The results from different models provide insights into which algorithm performs best for this specific dataset.
