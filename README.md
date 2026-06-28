# Olympic-Athlete-EDA
# 🏅 Olympic Athletes Exploratory Data Analysis (EDA)

## Project Overview
This project performs Exploratory Data Analysis (EDA) on the Olympic Athletes dataset to uncover trends and patterns in athlete participation, demographics, and sports across different Olympic Games.

The analysis focuses on understanding athlete characteristics, participation trends, and the distribution of key variables using Python and data visualization libraries.

---

## Objectives

- Clean and preprocess the Olympic athletes dataset.
- Handle missing values appropriately.
- Analyze athlete demographics such as age, gender, height, and weight.
- Identify the most popular sports.
- Examine athlete participation across Olympic years.
- Visualize data distributions and detect outliers.
- Generate meaningful insights and recommendations from the dataset.

---

## Dataset

The dataset contains information about Olympic athletes, including:

- Athlete Name
- Sex
- Age
- Height
- Weight
- Team
- NOC
- Games
- Year
- Season
- City
- Sport
- Event
- Medal

---

## Tools & Technologies

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## Data Cleaning

The following preprocessing steps were performed:

- Removed duplicate records.
- Identified missing values using `isnull()`.
- Filled missing numerical values (Age, Height, Weight) using the **median** to reduce the effect of outliers.
- Verified data types.
- Checked dataset consistency.

---

## Exploratory Data Analysis

The following visualizations were created:

### Age Distribution
Shows the distribution of athletes across different age groups.

### Gender Distribution
Displays the proportion of male and female athletes.

### Height vs Weight Scatter Plot
Illustrates the relationship between athletes' height and weight.

### Top 10 Sports
Identifies the sports with the highest number of participating athletes.

### Athlete Participation by Year
Shows participation trends across Olympic Games.

### Height Box Plot
Detects outliers and visualizes the spread of athletes' heights.

### Weight Box Plot
Detects outliers and visualizes the spread of athletes' weights.

### Correlation Heatmap
Shows the relationships between numerical variables such as Age, Height, Weight, and Year.

---

## Key Insights

- Male athletes participate more frequently than female athletes.
- Athlete participation has generally increased over the years.
- Athletics, Swimming, and Football are among the most popular sports.
- Most athletes are between 20–30 years old.
- Height and weight show a positive correlation.
- Height and weight contain several outliers, which are common due to differences between sports.
- Median imputation effectively handled missing numerical values without being heavily influenced by extreme values.

---

## Future Improvements

- Interactive dashboards using Power BI or Tableau.
- Medal prediction using Machine Learning.
- Sport-specific trend analysis.
- Time-series analysis of Olympic participation.

---

## Author

**Yahvi Chaudhary**
---

## ⭐ If you found this project useful, consider giving it a star!
