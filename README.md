# Mental Tiredness Prediction

Machine learning project for predicting mental tiredness scores based on behavioral, environmental, workload, sleep, and lifestyle-related features.

## Project Objective

The goal of this project is to analyze factors associated with mental tiredness and build a machine learning model capable of predicting a person's mental tiredness score.

## Dataset

The dataset contains 15,000 observations and includes numerical and categorical features related to:

- Workload
- Sleep
- Screen time
- Deep work
- Notifications
- Context switching
- Caffeine consumption
- Hydration
- Work environment
- Mood
- Work type

### Target Variable

`mental_tiredness_score`

## Sprint 1: Data Understanding & Preprocessing

Completed:

- Data loading and validation
- Initial data inspection
- Missing-value analysis
- Duplicate detection and removal
- Data type inspection
- Exploratory Data Analysis
- Univariate analysis
- Bivariate analysis
- Multivariate analysis
- Correlation analysis
- Outlier detection using IQR
- Categorical feature encoding
- Train-test split
- Feature scaling

## Preprocessing

### Categorical Encoding

One-Hot Encoding was used for nominal categorical variables such as:

- `mood`
- `work_type`
- `work_environment`

### Feature Scaling

StandardScaler was used for numerical features.

The preprocessing transformer was fitted only on the training data to prevent data leakage.

## Dataset Split

- Training: 80%
- Testing: 20%

Final dimensions:

- Training data: 12,000 samples
- Testing data: 3,000 samples
- Processed features: 24

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Status

Sprint 1 completed.

Next: Model development and evaluation.
