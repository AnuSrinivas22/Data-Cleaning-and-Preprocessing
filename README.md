ML Internship Task 1 - Data Cleaning and Preprocessing

Objective
Clean and preprocess the Titanic dataset for use in ML models.

Tools Used
- Python
- Pandas, NumPy
- Matplotlib
- Scikit-learn

Steps Performed
- Handled missing values using median/mode
- Encoded categorical variables
- Standardized numeric features
- Removed outliers using IQR
- Visualized using Matplotlib

>>>>>>> Quick Recap of What We'd Do with the Titanic Dataset
Load the data (typically from titanic.csv).
Handle missing values:
Age: fill with median or use predictive imputation.
Cabin: often dropped due to too many missing values.
Embarked: fill with mode.
Convert categorical variables:
Encode Sex, Embarked, and possibly Pclass, Title, etc.
Engineer features:
Extract titles from names.
Create FamilySize or IsAlone from SibSp + Parch.
Normalize/scale numerical columns like Age and Fare.
Remove outliers in Fare or Age using the IQR method.
