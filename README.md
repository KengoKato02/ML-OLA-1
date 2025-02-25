# Heart Attack Prediction Analysis

Group Members & Authors:
- Kengo Kato

Link to remote repository:
- https://github.com/KengoKato02/ML-OLA-1

## Overview

This project was made for the OLA 1 assignment and involves data wrangling, exploration, and analysis using a heart attack prediction dataset from Kaggle for my course of Machine Learning at CPH Business Academy taught by Steven William Albury.

## Dataset

The dataset used in this project is taken from Kaggle: [Heart Attack Prediction Dataset](https://www.kaggle.com/datasets/imnikhilanand/heart-attack-prediction). Please download the dataset and place it in a folder named `data` at the root directory. Ensure this folder is excluded from version control by adding it to `.gitignore`.

## Project Structure

- **notebooks/OLA.ipynb**: Contains the Jupyter Notebook with all the data wrangling, exploration, and analysis steps.
- **.gitignore**: Ensures the `data` folder is not tracked by Git.

## Analysis Steps

1. **Data Wrangling**:
   - Loaded the dataset and replaced '?' placeholders with `NaN` for proper analysis.
   - Converted all columns to numeric types where applicable.

2. **Data Exploration**:
   - Used `describe()` and `info()` methods to understand the dataset's structure and summary statistics.
   - Visualized distributions and relationships using seaborn and matplotlib.

3. **Data Cleaning**:
   - Identified and handled missing values.
   - Converted categorical variables into numerical format using one-hot encoding.

4. **Feature Engineering**:
   - Binned the `age` column into categories: Young, Middle-aged, and Senior.
   - Applied one-hot encoding to the `cp` (chest pain type) column.

5. **Descriptive Statistics**:
   - Calculated mean, median, and standard deviation for numerical features.
   - Analyzed frequency of categorical features.

6. **Data Visualization**:
   - Created box plots for numerical features to identify distributions and outliers.
   - Generated bar charts for categorical features to understand their distribution.

7. **Insights & Conclusion**:
   - Observed correlations between age and cholesterol, age and maximum heart rate, and chest pain type and oldpeak.
   - These insights can guide further analysis and model building.

## Requirements

- Python 3.13 and virtual enviroment setup running ipykernel
- Libraries: pandas, numpy, matplotlib, seaborn

1. Run the Jupyter Notebook:
   ```bash
   jupyter notebook notebooks/OLA.ipynb
   ```

## Conclusion

This project provides an stastical analysis of the heart attack prediction dataset with currently no trained models, offering insights into the relationships between various health indicators and heart attack risk.
