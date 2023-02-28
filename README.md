# logistic-regression
The code reads in a CSV file called "Churn_Modelling (1).csv" and uses pandas to create a dataframe from it. Then it uses scikit-learn's LabelEncoder to convert categorical variables to numerical variables. It then prints the first five rows of the dataframe, the dataframe's info, and the dataframe's description.
The LabelEncoder from the sklearn.preprocessing module was used to convert categorical variables Surname, Geography and Gender into numerical variables.
The resulting transformed dataframe has no missing values.
The dataframe contains information about customers, including their credit scores, geographic location, age, balance, and whether or not they exited the bank. The "Exited" column is the target variable for a potential machine learning model. 
This dataset can be used to analyze factors that contribute to customer churn in the banking industry. The variables can be used to build predictive models to identify customers who are likely to churn and target them with retention offers.
