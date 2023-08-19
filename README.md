# Exploratory Data Analysis With Python and Pandas

This is a self-initiated project that perform basic exploatory data analysis with python and pandas.

# Analytic methods used in this proejct
  
  1. Apply practical Exploratory Data Analysis (EDA) techniques on any tabular dataset using Python.

  2. Produce data visualizations using Seaborn and Matplotlib

  3. Identify and handle duplicate and missing data

# Content of the project

This project is divided into the following takss:

# Task 1: Initial Data Exploration

  - Import essential libraries such as NumPy, Pandas, Seaborn, Matplotlib and so on.

  - Use Pandas to read in the data, get a brief glimpse of the first few rows, and calculate some quick summary statistics of the numeric columns.

# Task 2: Univariate Analysis

  - Conduct univariate analysis on both continuous and categorical variables.

    - First plot the distribution of customer ratings with seaborn and also overlay the mean, 25th and 75th percentile quantiles calculated using Numpy.

    - Then use Pandas' .hist() method to plot the distribution for all numeric variables.

    - Use Seaborn's .countplot() method, we see the frequency distribution of 'Branch' and 'Payment' which are categorical variables.

# Task 3: Bivariate Analysis

  - Conduct bivariate analysis on both continuous and categorical variables.

    - Use Seaborn to plot scatterplots and regression plots to identify the relationship between customer rating and gross income.

    - Use Seaborn to plot a boxplot to check the difference in aggregate sales figures between the three branches of supermarkets, and to compare sales patterns between men and women.

    - Plot a time series graph to check for trends in gross income over a period of three months.

# Task 4: Dealing With Duplicate Rows and Missing Values

  - Identify and deal with duplicate rows and missing values in our dataset.

    - Calculate the number of duplicate rows and delete them using Pandas.

    - Do the same with missing values, but instead of deleting those rows,  replace missing values by the means of their respective columns.

# Task 5: Correlation Analysis
  - Conduct correlation analysis on the numeric variables in our dataset.

    - Use Numpy to calculate the correlation between two numeric variables.

    - Use pandas to calculate a correlation matrix to show all pairwise correlations of numeric variables.

    - Use seaborn to plot the calculated correlation matrix as a heatmap that is easily interpretable.
