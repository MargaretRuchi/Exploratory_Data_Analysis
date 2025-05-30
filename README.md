Exploratory Data Analysis (EDA)

📌 Project Overview
This project explores the famous Titanic dataset to uncover patterns and relationships among passenger features and their survival outcomes. It includes data cleaning, visualization, feature relationships, and key statistical insights.

🗂 Dataset
The dataset used is the train.csv file from the Titanic competition on Kaggle.

📊 Key Steps
Data Cleaning

Filled missing values in Age with median and Embarked with mode

Checked for duplicates and dropped them (if any)

Univariate Analysis

Survival count

Class distribution

Age and Fare distributions

Bivariate Analysis

Survival by Sex

Age distribution vs Survival

Fare vs Passenger Class

Correlation heatmap after encoding categorical features

Encoding

Categorical features like Sex, Embarked were encoded using LabelEncoder for heatmap analysis

Data Visualization

Countplots, Boxplots, Histograms, and Heatmaps using Seaborn and Matplotlib

📸 Plots
All plots are saved in the plots/ folder:

survival_count.png

passenger_class_count.png

age_distribution.png

survived_by_sex.png

age_vs_survival.png

fare_vs_class.png

correlation_heatmap.png

🧰 Tools Used
Python

Jupyter Notebook

Pandas

NumPy

Seaborn

Matplotlib

LabelEncoder (sklearn)

🔗 Follow My Data Science Journey at **[MgTechInsights](https://mgtechinsights.framer.website)**  