# Titanic Dataset – Exploratory Data Analysis (EDA)

## Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) on the Titanic dataset using Python.

The main objective is to explore passenger information, analyze survival patterns, identify missing values, and understand the relationship between passenger characteristics and survival rates.

## Tools & Libraries

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset

The Titanic dataset is loaded directly from Seaborn's built-in datasets.

```python
df = sns.load_dataset('titanic')
```

The dataset contains passenger information such as age, sex, passenger class, fare, family relationships, embarkation town, and survival status.

## Data Cleaning & Preparation

The following preprocessing tasks were performed:

- Inspecting dataset structure and data types using `info()`.
- Identifying missing values.
- Handling missing values in the age column.
- Converting selected columns to smaller integer data types using NumPy.
- Exploring categorical variables and their distributions.

## Exploratory Data Analysis

The analysis covers the following areas:

### 1. Passenger Demographics
- Distribution of male and female passengers.
- Passenger age distribution.
- Number of children and adults.
- Passenger distribution by ticket class.

### 2. Survival Analysis
- Overall survival percentage.
- Survival distribution by gender.
- Survival patterns among children.
- Survival analysis by passenger class.
- Number of male and female passengers who did not survive.

### 3. Passenger Characteristics
- Distribution of passengers traveling alone.
- Passenger distribution by embarkation town.
- Analysis of passengers traveling with family members.
- Passenger fare analysis.

### 4. Missing Values Analysis
- Identifying missing age values.
- Counting passengers with recorded and missing ages.
- Analyzing missing values by gender.
- Checking missing embarkation information.

### 5. Conditional Data Analysis
Using Pandas filtering and Boolean conditions to answer analytical questions, including:
- Passengers older than 40.
- Passengers between 20 and 30 years old.
- Passengers who paid more than 100 for their tickets.
- Female and male survival comparisons.
- Survival analysis across different passenger classes.

## Key Skills Practiced

- Data inspection and exploration
- Data cleaning and preprocessing
- Handling missing values
- Data type conversion
- Pandas filtering and Boolean indexing
- Conditional queries
- Frequency distributions
- Percentage calculations
- Working with categorical and numerical variables

## Project Status

This project represents an introductory stage of learning Data Analysis with Python. Further analysis and visualizations will be added as my skills develop.