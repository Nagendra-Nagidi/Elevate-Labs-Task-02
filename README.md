# Elevate-Labs-Task-02

In the above Taskfolder you can find all the necessary files regarding Task 2.In the Jupyter file 'task2_solutions.ipynb', I have done the Exploratory Data Analysis on the Titanic-Dataset, and that is also provided. I have mainly used pandas,matplotlib, and seaborn to complete task 2 in the following manner:

#### 1. Data Summary:
Basic statistics (mean, median, quartiles) were generated for numerical features like age, fare, and passenger class using the describe method.

#### 2.Visualisations
Distributions: Histograms and boxplots for numeric features (e.g., age, fare) to identify skewness, outliers, and data spread.

#### 3.Relationships: 
Pairplots: Visualized pairwise interactions between numerical features (e.g., age vs. fare, fare vs. passenger class) using scatterplots and diagonal KDE plots to highlight clusters and non-linear relationships.\n
Correlation Heatmap: Quantified linear associations between features using Pearson correlation coefficients, revealing strong positive links (e.g., fare and survival) and negative correlations (e.g., passenger class and survival).


#### 4.Patterns&Trends
Survival rates by gender, passenger class, age groups, and fare brackets were analyzed using bar plots.\n
A line plot revealed age-related trends in survival probability.

#### 5.Key Inferences
Gender: Women survived at significantly higher rates (~75%) than men (~20%).\n
Class: 1st-class passengers had the highest survival odds (63%), emphasizing socio-economic influence.\n
Fare & Class Correlation: Higher fares (linked to 1st class) strongly correlated with survival.\n
Age: Children (<12) in the 1st/2nd class had better survival rates than those in the 3rd class.

