Exploratory Data Analysis (EDA)

📌 Project Overview
This project explores the famous Titanic dataset to uncover patterns and relationships among passenger features and their survival outcomes. It includes data cleaning, visualization, feature relationships, and key statistical insights.
## 📂 Project Structure

- `train.csv`: The dataset used for EDA
- `EDA.ipynb`: Jupyter Notebook with all EDA steps
- `images/`: Folder containing saved PNG plots
- `README.md`: Project documentation

## 🔍 Key Objectives

- Understand the structure and quality of the dataset
- Visualize and analyze relationships between features
- Identify key factors that influenced survival

---

## 📊 EDA Insights Summary

1. **Survival Rate:**
   - Majority of passengers did **not survive**. Around 62% perished while 38% survived.

2. **Survival by Sex:**
   - **Females had a higher survival rate** than males, indicating possible prioritization during evacuation.

3. **Age Distribution:**
   - Most passengers were aged between **20–30 years**.
   - Age follows a right-skewed distribution with a few older passengers up to age 80+.

4. **Age vs Survival:**
   - Survivors were slightly younger on average, but age alone wasn’t a strong survival indicator.

5. **Passenger Class Count:**
   - The **3rd class** had the highest number of passengers, followed by 1st and 2nd.

6. **Fare Distribution per Class:**
   - Passengers in **1st class paid significantly higher fares**, showing a wide variance compared to other classes.

7. **Correlation Heatmap:**
   - Strong correlation between:
     - **Pclass and Fare** (negative): Higher class, higher fare.
     - **Sex and Survived** (negative): Female passengers (encoded lower) had higher survival odds.
   - Other features showed weak or no strong linear correlation with survival.

---

## 🖼️ Sample Visualizations
   survival_count.png
   passenger_class_count.png
   age_distribution.png
   survived_by_sex.png
   age_vs_survival.png
   fare_vs_class.png
   correlation_heatmap.png

---

## 🛠️ Tools Used

- Python
- Jupyter Notebook
- Pandas
- Seaborn
- Matplotlib

---

## 📁 How to Run

1. Clone this repo
2. Open `EDA.ipynb` in Jupyter
3. Run all cells and view visualizations

---
##🔗 Follow My Data Science Journey at **[MgTechInsights](https://mgtechinsights.framer.website)**  
