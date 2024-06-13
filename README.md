# BasicPyAndPandas -- Data Engineering 

## Objective

The objective of this assignment is to assess the ability to perform data manipulation, cleaning, transformation, and analysis using Pandas in Python. The dataset used for this assignment is the "Iris" dataset.

## Dataset

The "Iris" dataset was loaded using the seaborn library.

## Tasks

1. **Load the Dataset:**
   - Loaded the dataset into a Pandas DataFrame.
   - Displayed the first 5 rows of the DataFrame.
   - Displayed the summary statistics of the dataset.

2. **Data Cleaning:**
   - Checked for missing values and handled them appropriately.
   - Ensured that all the column names are in a consistent format (all lowercase).

3. **Data Transformation:**
   - Added a new column `sepal_area` which is the product of `sepal_length` and `sepal_width`.
   - Added a new column `petal_area` which is the product of `petal_length` and `petal_width`.
   - Normalized the values in `sepal_length`, `sepal_width`, `petal_length`, and `petal_width`.

4. **Data Aggregation and Grouping:**
   - Grouped the dataset by species and calculated the mean, median, and standard deviation for `sepal_length`, `sepal_width`, `petal_length`, and `petal_width`.
   - Created a pivot table that shows the mean `sepal_area` and `petal_area` for each species.

5. **Data Visualization:**
   - Plotted the distribution of `sepal_length` for each species.
   - Created a scatter plot of `sepal_length` vs. `sepal_width` colored by species.
   - Created a heatmap to visualize the correlation matrix of the dataset.

6. **Advanced Data Analysis:**
   - Identified the top 10 rows with the highest `sepal_area`.
   - Filtered the dataset to only include rows where `petal_length` is greater than the median `petal_length` of the dataset.
   - Performed additional analysis to explore the relationship between `petal_length` and `petal_width` for each species.

## Getting Started

### Prerequisites

Make sure you have the following libraries installed:

- pandas
- seaborn
- matplotlib
- numpy

You can install them using pip:

```bash
pip install pandas seaborn matplotlib numpy
```

#This README file provides a comprehensive overview of the project, steps to run the code, and a summary of the results and conclusions. You can customize it further based on your specific needs and any additional information you want to include.
