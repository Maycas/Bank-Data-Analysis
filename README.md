# DATA ANALYTICS

## Cleaning, Scaling and Visualization

### Preprocessing

With a given data set containing the details of a bank's customer list (`./data/churn_data_before_preprocessing.csv`), here's an example on how to use preprocessing techniques in order to be able to clean and transform the dataset.

Steps followed:

1. Check and remove duplicates

2. Uni-variate analysis:

    a) Identify the type of each feature
    
    b) Calculate Mean, median, quantiles for continues
    
    c) Plot a histogram or frequency tables for categorical

3. Outliers:
    
    a) Identify the outliers, if any

    b) Choose the correct treatment to remove them

4. Missing values:

    a) Identify missing values

    b) Impute missing values with your preferred way

5. Transform categorical variables

6. Scale the data set


### Visualization

After cleaning the data set, it's time to do some exploratory data analysis, which is the first step in building a model to predict churn. Since this process is usually very large, we will look at a subset of the total plots needed to complete this.

1. First look at the differences in churn rates, split by the different categorical variables. Produce the appropriate visualisation to compare the average churn rate, split by: 
i. Geography
ii. Gender
iii. Tenure

2. We would also like to know how the data is distributed. Some models require features to be normally distributed, and highly skewed variables can affect summary statistics if left unchecked. Produce the appropriate visualisation for the distribution of:
i. Geography
ii. Age
iii. Credit Score

3. Combine all of the above visualisations into a subplot.

4. Get the correlation between all columns using df.corr(). Create a bar plot that shows the correlation of each feature with the target:

    a) Order the bars so that the feature with the highest correlation is the first bar
    
    b) Add the correlation value to the top of each bar
    
    c) Add a line to the figure which shows the average correlation (hint: This will require adding an extra trace)
