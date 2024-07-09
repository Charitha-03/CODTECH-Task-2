*Name*:*CHARITHA CHOWDARY ENUKURTHI*
*Company:*CODTECH IT SOLUTIONS*
*ID:* CT04DA2294*
*Domain*:*Data Analyst*
*Duration*:*15 June to 15 July 2024*
*Mentor*:*SRAVANI GOUNI*

## Overview of the Project

### Project: Predictive modelling with Linear Regression on GOOG dataset

### Objective:
This code performs a linear regression analysis on a dataset to predict the 'Close' price of a stock based on its 'Open' price. The code includes data loading, preprocessing, model training, evaluation, and visualization steps.

### Key activities,Technologies used and key insights are breifly below :

1.Importing Libraries: The necessary libraries for data manipulation, visualization, and machine learning are imported.
2.File Upload and Reading Data: The dataset is uploaded and read into a Pandas DataFrame.
3.Displaying Initial Data Information:The first few rows, summary statistics, and the count of missing values for each column of the dataset are printed to understand the data better.
4.Feature Selection:The 'Open' price is selected as the feature (independent variable), and the 'Close' price is selected as the target (dependent variable).
5.Splitting Data into Training and Test Sets:The dataset is split into training and test sets using an 80-20 split. The random_state is set to 42 to ensure reproducibility.
6.Training the Linear Regression Model:A Linear Regression model is instantiated and trained on the training data.
7.Making Predictions:The trained model is used to make predictions on the test set.
8.Model Evaluation:The Mean Squared Error (MSE) and R-squared (R²) score are calculated to evaluate the model's performance. MSE measures the average squared difference between actual and predicted values, while R² indicates the proportion of the variance in the dependent variable that is predictable from the independent variable.
9.Visualization:A scatter plot and a line plot are created to compare the actual and predicted close prices. The scatter plot shows the actual close prices, and the line plot shows the predicted close prices.
10.Actual vs Predicted Values:A scatter plot is created to show the relationship between the actual and predicted values. A red line is plotted to indicate the ideal prediction line (where predicted values equal actual values).

**Technologies used:**
1.Pandas :For Data manipulation and analysis.
2.Numpy :For numerical computing and array operations.
3.Matplotlib :For data visualisation.
4.Seaborn :For statistical data visualisation.
5.Scikit-learn :For Machine Learning and Data Mining.

**Conclusion**
This code provides a basic example of linear regression analysis using a simple feature (Open price) to predict a target variable (Close price). The model's performance is evaluated using MSE and R², and the results are visualized to understand the relationship between actual and predicted values.

**OUTPUT**

![image](https://github.com/Charitha-03/CODTECH-Task-2/assets/156454784/8fb1bb57-1f86-4482-978a-38794849f6ae)

![image](https://github.com/Charitha-03/CODTECH-Task-2/assets/156454784/900e49e1-20b4-43ab-8bfd-fec6f7218fbb)

![image](https://github.com/Charitha-03/CODTECH-Task-2/assets/156454784/e12bad6a-544f-4c7f-8caa-cf777ea7d25d)

![image](https://github.com/Charitha-03/CODTECH-Task-2/assets/156454784/576ef32e-36e3-4320-808c-776427b433f2)






