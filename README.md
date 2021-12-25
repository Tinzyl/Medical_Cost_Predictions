# Medical_Cost_Predictions

### In this project, I built a RandomForestRegressor model to predict the medical cost of a patient using the given features. The dataset was taken from [Kaggle](https://www.kaggle.com/mirichoi0218/insurance). The features that were used were the following:
1. Age
2. Sex
3. BMI
4. Number of Children
5. If the person is a smoker or not
6. The region were the person lives

### Steps which were taken to build the model were as follows:
1. Performed EDA, which included:
    - Checking for null values
    - Checking for outliers
    - Checking for any correlation
2. Alter data based on the results of EDA
3. Performed One-Hot-Encoding
4. Split the data into 80% training data and 20% test data
5. Fit the data into the model

## Results
### When the model was tested on the test data, it produced an accuracy of **82.94%**.
