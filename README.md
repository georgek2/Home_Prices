# Home_Prices
Working with Home_Prices data set from Kaggle

    > Decision_Tree
         * Exploring the data before modelling
        + Model_One
            Dropping all the columns with categorical variables and missing values
        
        + Model_Two
            Imputing the missing entries in the numerical columns only
            Dropping categorical columns
        
        + Model_Three
            Imputing the missing values in numerical columns.
            Label encoding the categorical columns with low cardinality and no missing values.
            
    > Random Forest
        * Using the RandomForestRegressor
         + Model_One
             Drop all features with missing values
             Plus categorical features