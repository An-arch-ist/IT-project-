ESTIMATING SHARE OF AGRICULTURE, FORESTRY AND FISHING IN THE TOTAL GDP OF DIFFERENT COUNTRIES (AS A % OF GDP) USING CHOICE VARIABLES

This project analyzes the economic factors that explain cross-country variations in the share of Agriculture, Forestry, and Fishing as a percentage of GDP. Using World Bank development indicators for 57 countries (2018), the study applies Ordinary Least Squares (OLS) to evaluate the role of key structural variables in determining agricultural GDP contribution.

Project Objective

To identify and estimate how effectively the following factors explain the agricultural sector’s share in national GDP:
Employment in Agriculture (% of total employment) ,Gross Fixed Capital Formation (% of GDP) ,Rural Population (% of total population)

Dataset

Source: World Bank (2018)

Observations: 57 countries

Dataset Link: https://docs.google.com/spreadsheets/d/1LKMyDtdHzWKYkaj5-RaGJdey7ql_taL8/edit?usp=sharing&ouid=107497069306659788870&rtpof=true&sd=true

Variables:

Dependent Variable: Agricultural value-added (% of GDP) 

Independent Variables: Employment in agriculture (% of total employment) , Gross fixed capital formation (% of GDP) , Rural population (% of population) 

Methodology

The project involves the following steps:

1. Exploratory Data Analysis: Descriptive statistics, Boxplots for all key variables, Partial regression plots to visually test linearity

2. OLS Regression Modeling: Model estimation in Python, Interpretation of coefficients, Goodness-of-fit statistics (R², Adjusted R²)

3. Regression Diagnostics: To validate classical linear regression assumptions, the following tests were conducted:

Linearity: Partial regressor plots

Heteroskedasticity: Goldfeld–Quandt test

Normality: Q-Q plots and Shapiro–Wilk test

Multicollinearity: VIFs, IVIFs, Condition Indices

Influence Analysis: Cook’s distance & leverage statistics

4. Model Comparison (Restricted vs Full): ANOVA-based hypothesis testing, AIC & BIC comparison

📈 Key Findings

Employment in Agriculture is highly significant and positively related to agricultural GDP share.

Gross Fixed Capital Formation and Rural Population show positive but statistically insignificant effects.

R² = 0.853, indicating the model explains a large portion of cross-country variation.

No major issues detected in:

Linearity, Heteroskedasticity, Multicollinearity, Normality (based on significance threshold)

Overall, the model indicates that the structural importance of labor in agriculture remains the strongest predictor of agricultural GDP share across countries.

🛠️ Dependencies

Python 3.x , pandas, numpy, matplotlib, seaborn , statsmodels

scipy

