Title: Exploratory Data Analysis (EDA) of the Titanic Dataset using Python

Libraries:

pandas (pd): Data manipulation and analysis
numpy (np): Numerical computations
matplotlib.pyplot (plt): Data visualization
seaborn (sns): Statistical data visualization
Dataset:

1. Name: Titanic Dataset (Subset for brevity)
2. Number of Rows: 12
3. Number of Columns: 12
4. Columns:
5. PassengerId
6. Survived
7. Pclass
8. Name
9. Sex
10.Age
11. SibSp
12. Parch
13. Ticket
14. Fare
15. Cabin
16. Embarked
17. Code Summary:

Import Libraries
Import necessary libraries for data analysis and visualization
Embedded Titanic Dataset
Define a subset of the Titanic Dataset with 12 rows and 12 columns
Create DataFrame
Create a Pandas DataFrame from the embedded dataset
Exploratory Data Analysis (EDA)
Summary Statistics: Print summary statistics of the dataset using df.describe()
Distributions:
Age Distribution: Plot a histogram of the Age column using sns.histplot()
Survival Distribution: Plot a count plot of the Survived column using sns.countplot()
Passenger Class Distribution: Plot a count plot of the Pclass column using sns.countplot()
Correlations (Numerical Features):
TO DO: Implement correlation analysis for numerical features (incomplete in the provided code)
Output:

Summary statistics of the dataset
Three plots:
Age distribution histogram
Survival distribution count plot
Passenger class distribution count plot
Next Steps:

Complete the correlation analysis for numerical features
Explore additional EDA techniques (e.g., pairwise plots, box plots, violin plots)
Consider modeling or machine learning approaches to predict Survived based on other features
