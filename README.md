# Titanic-Survival-Analysis

To analyze the Titanic dataset to uncover insights about passenger demographics, survival rates, and factors influencing survival.

Data Cleaning:
Handled missing values in the Age and Embarked columns.
Converted categorical variables (e.g., Sex, Embarked) to numerical format using one-hot encoding.

Exploratory Data Analysis (EDA):
Distribution Analysis: Visualized the distribution of age, fare, and passenger class.

Survival Rate Analysis: Analyzed survival rates based on gender, passenger class, and embarkation point.
Correlation Analysis: Explored correlations between features and survival rates.

Data Visualization:
Pie Charts: Visualized the distribution of passenger classes and gender.
Bar Charts: Showed survival rates by gender and passenger class.
Stacked Bar Charts: Visualized the survival count by passenger class with a black background.

Modeling:
Logistic Regression: Used to predict survival based on features such as Pclass, Age, and Sex.
Random Forest: Employed to improve prediction accuracy by analyzing feature importance.

Technologies Used:
Programming Language: Python
Libraries:
Pandas: For data manipulation and analysis.
NumPy: For numerical computations.
Matplotlib and Seaborn: For data visualization.
Plotly: For interactive and custom visualizations.

Project Deliverables:
Jupyter Notebook: Contains the step-by-step analysis, visualizations, and modeling.
Presentation: Summarizes key findings and insights from the analysis.
Code Repository: Includes all scripts, data files, and results.
Key Insights:
Survival Rates: Higher survival rates observed for women and children, and for those in first class.

Feature Importance: Pclass, Sex, and Age were significant predictors of survival.

Visualization: The interactive and customized visualizations provided deep insights into the data, particularly when analyzed by passenger class and survival status.

Challenges and Solutions:
Missing Data: Addressed missing values in the Age column using the median age and imputed missing embarkation points based on passenger class and fare.

Imbalanced Data: Applied techniques like stratified sampling to balance the dataset for more accurate model predictions.

