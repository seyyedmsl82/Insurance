# Insurance Data Analysis

This repository contains a Python script for analyzing insurance data using the pandas library. The dataset used in this analysis is stored in a CSV file named `insurance.csv`. The script covers various aspects of data exploration, visualization, and regression analysis.

## Getting Started

To run the script, make sure you have Python installed on your system. Additionally, install the required libraries using the following command:

```bash
pip install pandas matplotlib scikit-learn
```

Clone this repository to your local machine:

```bash
git clone https://github.com/your-username/insurance-analysis.git
cd insurance-analysis
```

Run the script:

```bash
python insurance_analysis.py
```

## Data Overview

The analysis begins by loading the insurance dataset using pandas:

```python
import pandas as pd
df = pd.read_csv('insurance.csv')
```

A brief overview of the dataset is displayed using `df.head()`:

```
   age     sex     bmi  children smoker     region      charges
0   19  female  27.900         0    yes  southwest  16884.92400
1   18    male  33.770         1     no  southeast   1725.55230
2   28    male  33.000         3     no  southeast   4449.46200
3   33    male  22.705         0     no  northwest  21984.47061
4   32    male  28.880         0     no  northwest   3866.85520
```

## Exploratory Data Analysis

The script performs exploratory data analysis, including checking for missing values, displaying unique values, and using one-hot encoding for categorical variables.

## Data Visualization

A set of visualizations is generated using matplotlib. The scatter plots show the relationship between certain features and the 'charges' column.

## Regression Analysis

The script utilizes scikit-learn to perform regression analysis. It includes data preprocessing steps, such as scaling and normalization, before applying Support Vector Regression, Decision Tree Regression, and Gradient Boosting Regression.

The mean absolute error for each regression model is printed at the end of the script.

Feel free to explore and modify the script based on your requirements. If you encounter any issues or have suggestions for improvement, please open an issue or submit a pull request.
