# Prodigy InfoTech Internship Task 2

## Data Cleaning and Exploratory Data Analysis (EDA) on Titanic Dataset

### Introduction
Welcome to the Prodigy InfoTech Internship Task 2! In this task, I have performed data cleaning and exploratory data analysis (EDA) on the Titanic dataset. The goal is to explore the relationships between variables and identify patterns and trends in the data.

### Dataset
The dataset used for this task is the Titanic dataset. It contains information about passengers aboard the Titanic, including attributes such as PassengerId, Survived, Pclass, Name, Sex, Age, SibSp, Parch, Ticket, Fare, Cabin, and Embarked.

### Data Cleaning
- Loaded the dataset using pandas.
- Checked for missing values in the dataset.
- Removed irrelevant columns such as Ticket and Cabin.
- Filled missing values in the Age and Embarked columns with appropriate values.

### Exploratory Data Analysis (EDA)
- Explored the descriptive statistics of the dataset.
- Calculated the correlation matrix to understand the relationships between numeric variables.
- Visualized the distribution of passengers by gender and survival status.
- Analyzed the distribution of passengers by ticket class and age.
- Investigated the relationship between survival and other variables such as SibSp, Parch, Fare, and Embarked.

### Modeling
- Trained several machine learning models including Logistic Regression, Support Vector Machines, Naive Bayes, K-Nearest Neighbors (KNN), and Decision Tree.
- Evaluated the models using accuracy scores and confusion matrices.
- Selected the best performing model based on the accuracy score.

### Results
The results of the modeling phase are summarized below:

| Model                   | Accuracy Score |
|-------------------------|----------------|
| Naive Bayes             | 0.76           |
| Logistic Regression     | 0.75           |
| Decision Tree           | 0.74           |
| Support Vector Machines | 0.66           |
| KNN                     | 0.66           |

### Conclusion
In conclusion, the Naive Bayes model performed the best among the models evaluated for predicting survival on the Titanic dataset. However, further optimization and fine-tuning of the models could potentially improve performance.

### Next Steps
- Further refine the models by tuning hyperparameters.
- Explore additional feature engineering techniques.
- Experiment with ensemble methods for improved performance.

