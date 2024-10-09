# **Tools and Libraries Used in Our Project**

<div style="display: flex; flex-wrap: wrap; gap: 10px;">
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white" alt="Pandas" style="flex: 1 1 30%;">
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white" alt="NumPy" style="flex: 1 1 30%;">
  <img src="https://img.shields.io/badge/Matplotlib-003366?style=flat&logo=matplotlib&logoColor=white" alt="Matplotlib" style="flex: 1 1 30%;">
  <img src="https://img.shields.io/badge/Seaborn-3776AB?style=flat&logo=seaborn&logoColor=white" alt="Seaborn" style="flex: 1 1 30%;">
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white" alt="Jupyter" style="flex: 1 1 30%;">
  <img src="https://img.shields.io/badge/Google%20Colab-blue?style=flat&logo=google-colab&logoColor=white" alt="Google Colab" style="flex: 1 1 30%;">
  <img src="https://img.shields.io/badge/Plotly-3D1E9E?style=flat&logo=plotly&logoColor=white" alt="Plotly" style="flex: 1 1 30%;">
</div>


# EDA Project - Analysis on Electric Vehicles

## Table of Contents
- [Introduction](#introduction)
- [How to Clone the Project](#how-to-clone-the-project)
- [Steps to Perform EDA](#steps-to-perform-eda)
  - [Preliminary Steps - Inspect the Data](#preliminary-steps---inspect-the-data)
  - [Data Cleaning and Manipulations](#data-cleaning-and-manipulations)
  - [Task 1: Exploratory Data Analysis](#task-1-exploratory-data-analysis)
    - [1. Univariate Analysis](#1-univariate-analysis)
    - [2. Bivariate Analysis](#2-bivariate-analysis)
  - [Task 2: Choropleth Visualization](#task-2-choropleth-visualization)
  - [Task 3: Racing Bar Plot Visualization](#task-3-racing-bar-plot-visualization)
- [Conclusion](#conclusion)

## Introduction
This project aims to perform an Exploratory Data Analysis (EDA) on a dataset related to electric vehicles (EVs). The primary objectives include understanding the distribution of EVs across various states, identifying trends over time, and visualizing relationships between different variables.

## How to Clone the Project
To clone this project repository, follow these steps:

1. **Ensure you have Git installed** on your machine. If you don't have Git, you can download and install it from [git-scm.com](https://git-scm.com/).

2. **Open your terminal or command prompt.**

3. **Run the following command** to clone the repository:

   ```bash
   git clone https://github.com/Angad143/EDA-Project-Analysis-on-Electric-Vehicles.git
   ```

4. **Navigate into the cloned directory:**

   ```bash
   cd your-repository-name
   ```

## Steps to Perform EDA

### Preliminary Steps - Inspect the Data
In this step, we load the dataset and inspect its structure. Key actions include:
- Checking for missing values
- Identifying duplicate records
- Ensuring data types are appropriate for analysis

### Data Cleaning and Manipulations
After identifying issues, we begin the cleaning process, which involves:
- Handling missing values by imputation (mean, median) or removing affected rows/columns.
- Ensuring all data types are correctly set for analysis.

### Task 1: Exploratory Data Analysis

#### 1. Univariate Analysis
**A. Numerical Data**
- **Statistical Non-Visual Analysis:** Summarize the data using measures such as min, max, sum, mean, median, variance, standard deviation, range, and interquartile range (IQR).
- **Visual Analysis:** Utilize plots to understand data distribution and outliers through:
  - Histogram Plot
  - Kernel Density Estimation (KDE) Plot
  - Box Plot (Box-and-Whisker Plot)

**B. Categorical Data**
- **Statistical Non-Visual Analysis:** Summarize data using count, unique values, and value counts.
- **Visual Analysis:** Visualize the distribution of categorical data with:
  - Bar Plot
  - Count Plot
  - Pie Chart

#### 2. Bivariate Analysis
**A. Numerical vs Numerical Data**
- **Statistical Non-Visual Analysis:** Investigate relationships between two numerical variables using:
  - Pearson Correlation Coefficient
- **Visual Analysis:** Employ scatter plots and heatmaps.

**B. Categorical vs Categorical Data**
- **Statistical Non-Visual Analysis:** Examine dependencies using cross-tabulations (frequency tables).
- **Visual Analysis:** Utilize stacked and grouped bar plots.

**C. Categorical vs Numerical Data**
- **Visual Analysis:** Apply box plots and histograms to visualize relationships.

### Task 2: Choropleth Visualization
Create a choropleth map using `plotly.express` to display the number of electric vehicles based on location. This visualization will help identify geographic trends in EV distribution.

### Task 3: Racing Bar Plot Visualization
Develop an animated racing bar plot to illustrate the count of electric vehicle makes over the years. This visualization provides insights into trends and shifts in the EV market.

## Conclusion
The EDA on the electric vehicles dataset offers valuable insights into the distribution and trends of EVs across different states and over time. This analysis not only highlights the current state of electric vehicle adoption but also serves as a foundation for further in-depth studies.
