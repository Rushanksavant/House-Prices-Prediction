# House-Prices-Prediction
The Ames Housing dataset was compiled by Dean De Cock for use in data science education. It's an incredible alternative for data scientists looking for a modernized and expanded version of the often cited Boston Housing dataset. 

# For missinng values of dataset¶
- Find all columns with str - str_col
- Find columns with missing values in str_col - miss_str_col
- Apply imputer with strategy = 'most frequent'/ 'constant'
- Find all columns with num - num_col
- Find columns with missing values in num_col - miss_num_col
- Apply imputer with strategy = 'mean'/ 'constant'

# OneHotEncoding the Categorical variables of the imputed dataset

# Performing feature selection
# Using Correlation matrix

# Spliting data into training set and validation set

# Creating Training model and fitting appropriate data¶
# Steps:
- Defining a function (get_mae) to get mean absolute errors for diffrent values of max_leaf_nodes by fitting RandomForestRegressor
- Setting a list of values for max_leaf_nodes
- Creating a dictionary(scores) with leaf_size and its corresponding mean absolute error
- Finding the leaf_size with minimum mean absolute error (best_node_val)
- Ultimatly fitting the RandomForestRegressor with the best_node_val

# Making Predictions on validation set
# Calculating accuracy of the model


