"# Diabetes-Prediction" 
**Data Loading and Exploration:**
The project starts by loading a dataset named "diabetes.csv" using pandas.
The dataset contains information about pregnancies, glucose levels, blood pressure, skin thickness, insulin levels, BMI, diabetes pedigree function, age, and diabetes outcome.
Initial exploration includes checking the first few rows, statistical summary, information about data types, checking for missing values, and duplicated rows.

**Data Visualization:**
Visualizations are used to understand the distribution of the target variable ('Outcome') and to detect outliers using boxplots.
Pair plots are created to observe relationships between variables based on the outcome.

**Data Preprocessing:**
Standard scaling is performed on the features to bring them to a similar scale.
No missing values or duplicate rows are detected, so no imputation or removal is performed.

**Model Building:**
The K-Nearest Neighbors (KNN) algorithm is used for classification.
Train-test split is performed to evaluate the model's performance.
A loop is used to iterate through different values of 'k' (number of neighbors) to find the optimal value that gives the highest accuracy.
The model with the optimal 'k' value is chosen and fitted on the training data.
The accuracy of the model is evaluated on the test data.
Confusion matrix and classification report are generated to evaluate the model's performance further.

**Results:**
The model achieves an accuracy of approximately 77.92% on the test data.
The precision, recall, and F1-score for both classes (diabetic and non-diabetic) are provided in the classification report.
The project concludes with a description of the model's performance and its ability to predict diabetes outcomes based on the given features.

Overall, this project demonstrates a typical machine learning workflow, including data exploration, preprocessing, model building, and evaluation, with a focus on predicting diabetes outcomes.
