🚢 Titanic Dataset Exploratory Data Analysis (EDA)
📌 Overview

This project performs Exploratory Data Analysis (EDA) on the famous Titanic dataset using Python libraries like Pandas, NumPy, Matplotlib, and Seaborn.

The goal is to analyze passenger data, uncover patterns, and understand factors that influenced survival.

📂 Dataset

The dataset is loaded directly using Seaborn:

df = sns.load_dataset('titanic')

It contains information such as:

Passenger class (pclass)
Gender (sex)
Age (age)
Fare (fare)
Survival status (survived)
And more...
🛠️ Technologies Used
Python 🐍
Pandas (Data manipulation)
NumPy (Numerical operations)
Matplotlib (Visualization)
Seaborn (Statistical visualization)
📊 Steps Performed
1. Data Loading & Inspection
Display first few rows
Check dataset shape
View dataset info (data types, null values)
2. Descriptive Statistics
Summary statistics for numerical columns
Summary for categorical columns
3. Data Visualization
🔹 Univariate Analysis
Survival count
Passenger class distribution
Gender distribution
Age distribution (Histogram)
Fare distribution (Boxplot)
🔹 Bivariate Analysis
Age vs Fare (Scatter plot)
Age vs Survival (Boxplot)
Fare vs Passenger Class
Survival rate by gender
Survival rate by class and gender
🔹 Correlation Analysis
Correlation matrix of numerical features
Heatmap visualization
📈 Key Insights (Examples)
Females had a higher survival rate than males
Passengers in higher classes had better survival chances
Fare and passenger class are strongly related
Age distribution shows most passengers were young adults
▶️ How to Run
Clone this repository or download the notebook
Install dependencies:
pip install pandas numpy matplotlib seaborn
Run the Jupyter Notebook:
jupyter notebook
📌 Project Structure
├── Titanic_EDA.ipynb
├── README.md
🚀 Future Improvements
Handle missing values more thoroughly
Feature engineering
Build a machine learning model for survival prediction
Add interactive visualizations (Plotly)
