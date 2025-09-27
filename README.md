# Titanic Pandas Project
 
 
## Overview

This project analyzes the famous Titanic dataset using Python and Pandas.
The goal is to practice data cleaning, exploration, and feature engineering to gain confidence in handling real-world datasets.

## Tools & Libraries

Python

Pandas

Seaborn (for loading dataset)

Jupyter Notebook

 ## Dataset

The dataset is loaded directly from Seaborn:

import seaborn as sns

df = sns.load_dataset("titanic")

## Key Questions Answered

Dataset overview (shape, datatypes, missing values)

Average age and fare of passengers

Gender and survival distributions

Survival rate by:

Gender

Passenger class

Family size

Created new feature: family_size = sibsp + parch + 1

Saved cleaned dataset as titanic_cleaned.csv

## Insights

Women had a much higher survival rate than men

1st class passengers survived more than 3rd class

Larger families had lower survival rates compared to individuals or small families

Fare was strongly linked with passenger class

## Files

titanic_pandas_project.ipynb (Jupyter Notebook with full code)

titanic_cleaned.csv (Cleaned dataset (saved version))

README.md (Project documentation)

## Next Steps

Add visualizations with Matplotlib & Seaborn

Try basic ML models for survival prediction

Upload to GitHub as part of PhD portfolio