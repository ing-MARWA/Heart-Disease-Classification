# Heart-Disease-Classification
# Heart Disease Analysis

This project focuses on analyzing a dataset called `heart_2020_cleaned.csv` to gain insights into heart disease. The dataset contains various features such as age, sex, smoking habits, alcohol drinking habits, and more. Let's go through the steps taken in this analysis:

## Importing Libraries

We start by importing the necessary libraries for data analysis and visualization: `pandas`, `numpy`, `matplotlib.pyplot`, and `seaborn`.

## Reading Data

Next, we read the data from the CSV file using `pd.read_csv()` function. We also check the shape of the data to understand the number of rows and columns.

## Data Information

We then print the head of the data to get a glimpse of the dataset. After that, we check the data types of the columns using `HeartDiseaseData.dtypes` and display the general information of the dataset using `HeartDiseaseData.info()`. Lastly, we check the number of null values in the dataset using `HeartDiseaseData.isnull().sum()`.

## Creating DataFrame and Dropping NaN Values

To ensure the quality of our analysis, we create a new DataFrame called `HeartDataFrame` by dropping the rows that contain at least one NaN value using the `dropna()` function. We then check the new size of the data using `HeartDataFrame.shape`.

## Analyzing Features

We analyze various features in the dataset to gain insights into heart disease. Some of the features we analyze include:

- Alcohol Drinking: We calculate the percentage of alcohol drinkers who have heart disease and the number of alcohol drinkers who have and haven't heart disease.
- Smoking: We calculate the number of smoking persons who have and haven't heart disease.
- Sex: We calculate the number of males and females in the dataset and the number of males and females who have and haven't heart disease.
- Age Category: We count the number of heart disease cases for each age category.
- Asthma: We count the number of persons who have and haven't asthma.

## Visualization

We use various visualization techniques to better understand the data. Some of the plots we create include:

- Countplot of Alcohol Drinking Vs Heart Disease patients in the dataset.
- Countplot of Smoking Vs Heart Disease persons in the dataset.
- Countplot of Gender Vs Heart Disease persons in the dataset.
- Countplot of Age Category Vs Heart Disease persons in the dataset.
- Boxplot of Physical Health Vs Heart Disease persons in the dataset.
- Boxplot of Sleep Time Vs Heart Disease persons in the dataset.

These visualizations help us visualize the distribution and relationships between different variables in the dataset.

## Conclusion

In conclusion, this analysis provides insights into heart disease based on the `heart_2020_cleaned.csv` dataset. The analysis includes data cleaning, feature analysis, and visualization to better understand the factors associated with heart disease.
