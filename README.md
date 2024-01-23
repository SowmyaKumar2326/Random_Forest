# Random_Forest
Random Forest is a popular machine learning algorithm used for both classification and regression tasks. It is an ensemble learning method that constructs a multitude of decision trees at training time and outputs the class that is the mode of the classes (classification) or mean prediction (regression) of the individual trees.
The objective is to predict taxable income categories ('Risky' or 'Good') based on various features. The dataset includes columns such as Undergrad, Marital Status, Taxable Income, City Population, Work Experience, and Urban.
Taxable Income was categorized into 'Risky' and 'Good' based on a condition: if taxable income is less than or equal to 30000, it was labelled as 'Risky'; otherwise, it was labelled as 'Good'. This becomes the target variable 'y'.
The dataset was split into features (X) and the target variable (y). Mapping was applied to 'Undergrad' and 'Urban' columns, and one-hot encoding (get_dummies) was used for 'Marital Status' and 'Taxable Income' columns.
No missing values were found in the dataset, ensuring data integrity for analysis.
## Modeling:
Random Forest Classifier
The Random Forest Classifier was chosen for modeling. The features ['Undergrad', 'Work Experience', 'Urban', 'Divorced', 'Married', 'Single'] were selected as X variables, and 'Risky' was set as the y variable.
Data scaling was performed using Standard Scaler to standardize the feature values.
The dataset was fitted into the Random Forest Classifier, and predictions were made. The model achieved an accuracy of 82.78%.
## Conclusion
The project successfully analyzed the dataset to predict taxable income categories using a Random Forest Classifier. Through careful preprocessing and feature engineering, the model achieved an accuracy of 82.78%.

