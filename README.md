# fifa-market-value-analysis
My first data analytics project exploring FIFA 22 player market values using R.
** FIFA 22 Market Value Analysis (Mini Project)**
** Project Overview**

This project explores the FIFA 22 players dataset to analyze player market values.
The main objective was to build a simple regression model to predict player market values and identify undervalued vs overvalued players.

This is my first data analytics mini-project — focusing on using R for data cleaning, modeling, and visualization.

**Dataset**

Source: FIFA 22 Player Dataset (Kaggle
)
Key variables:
short_name: Player name
age: Player age
overall: Current overall rating
potential: Potential rating
value_eur: Market value in Euros

** Methods**

Data Cleaning
Handled missing values.
Selected relevant variables.
Exploratory Data Analysis (EDA)
Summarized player characteristics (age, rating, potential).
Visualized basic distributions.
Modeling
Linear Regression:
value_eur=Bo+B1.age+B2.overall+B3.potential+𝜖

**Compared Actual vs Predicted values**.

Identified overvalued and undervalued players.

 Results
 Actual vs Predicted Market Values
I created and uploaded a plot (`Rplot.png`) that shows the relationship between actual and predicted player market values. 
Dots above red line → Overvalued players.
Dots below red line → Undervalued players.

** Code**

 Full R code is available here: fifa_analysis.R

