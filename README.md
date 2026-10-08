# SWYNEX Data Science Internship — Task 2

## Exploratory Data Analysis

### Objective

The objective of this task was to perform Exploratory Data Analysis (EDA) on the prepared Titanic dataset, identify important patterns, and extract insights that could be useful for machine learning or decision-making.

### Dataset

The Titanic passenger dataset contains information about passengers, including:

* Passenger class
* Sex
* Age
* Number of siblings/spouses
* Number of parents/children
* Fare
* Embarkation port
* Survival status

### Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

### EDA Performed

The following analyses were performed:

* Dataset structure and data types
* Descriptive statistics
* Categorical variable distributions
* Overall survival rate
* Survival rate by gender
* Survival rate by passenger class
* Age distribution
* Age distribution by survival
* Fare distribution by passenger class
* Family size analysis
* Survival rate by family size
* Survival rate by embarkation port
* Correlation analysis
* Correlation heatmap

### Key Insights

1. Female passengers had a substantially higher survival rate than male passengers.
2. First-class passengers had a higher survival rate than second- and third-class passengers.
3. Fare showed a positive relationship with survival.
4. Age had a relatively weak linear relationship with survival.
5. Family size showed very little overall linear correlation with survival, although survival rates varied across family-size groups.
6. Survival rates differed across embarkation ports.
7. Among the numerical variables, Pclass and Fare showed relatively stronger relationships with survival.

### Model-Relevant Observations

The analysis suggests that variables such as `Sex`, `Pclass`, and `Fare` may provide useful information for predicting passenger survival. Other variables may still contribute to a model through non-linear relationships or interactions with other features.

### Repository Contents

* `task2_eda.ipynb` — Complete EDA notebook
* `cleaned_titanic.csv` — Prepared dataset used for analysis
* `README.md` — Project documentation

### Outcome

The EDA helped identify important patterns and relationships in the dataset and provided a foundation for feature selection and machine learning in future tasks.
