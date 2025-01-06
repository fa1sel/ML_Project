Classification of drugs based on features like Age, Sex ,Blood Pressure Levels (BP),Cholesterol Levels and  Na to Potassium Ratio into Drug type


Libraries Used
1. Scikit-learn
Modules and Functions:
load_iris: Load the Iris dataset.
GridSearchCV: Perform hyperparameter tuning.
train_test_split: Split data into training and testing sets.
RandomForestClassifier: Random Forest algorithm for classification.
KNeighborsClassifier: K-Nearest Neighbors algorithm.
SVC: Support Vector Classification.
classification_report: Generate detailed classification metrics.
LabelEncoder: Encode labels to numeric format.
StandardScaler: Standardize features by removing the mean and scaling to unit variance.
2. Pandas
Used for: Data manipulation and analysis.





Data set has 200 entries 


Data Loading: Load the dataset using pandas.

Label Encoding: Convert categorical variables (e.g., Sex, BP, Cholesterol, Drug) into numerical values using LabelEncoder.

Feature Selection: Select features (Age, Sex, BP, Cholesterol, Na_to_K) and target variable (Drug).

Train-Test Split: Split the data into training and testing sets (80-20 split).

Purpose: Prepare the data for machine learning models by converting categorical data and splitting the dataset.


