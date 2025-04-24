# Data_Cleaning_Preprocessing_Task
# Titanic Data Cleaning & Preprocessing

This project involves cleaning and preprocessing the Titanic dataset to prepare it for machine learning modeling.

## Data Cleaning & Preprocessing Steps

### 1. Handling Missing Values
- `Age`: Filled with the median value.
- `Embarked`: Filled with the most frequent value (mode).
- `Cabin`: Dropped due to high missing data.

### 2. Encoding Categorical Features
- `Sex`: Label encoded (male = 1, female = 0).
- `Embarked`: One-hot encoded.

### 3. Normalizing Numerical Features
- `Age` and `Fare` were standardized using `StandardScaler`.

### 4. Outlier Removal
- Outliers were detected using boxplots and removed using IQR method.

## Conclusion
The cleaned dataset is now ready for machine learning modeling.
