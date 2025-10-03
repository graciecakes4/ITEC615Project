# ITEC 615 Regression Project
## Project Overview

This project is a class research project aimed at predicting salaries for data professionals using regression analysis. The dataset includes a variety of features such as job designation, age, department, past experience, and performance ratings, which serve as predictors for employee salaries. The study explores the relationship between these variables and employee compensation, providing insights into the factors influencing pay in data-related roles.

## Objectives
### Primary Goal:
    •	Build a regression model to accurately predict employee salaries.

### Secondary Goals:
    •	Analyze the importance of different features (e.g., designation, past experience).
    •	Evaluate model performance using appropriate metrics like Mean Absolute Error (MAE) and R-squared.
    •	Provide actionable insights on salary determinants.

## Dataset Description

The dataset includes the following key features:

    •	Personal Information: First Name, Last Name, Gender, Age
    •	Employment Details: Designation, Date of Joining (DOJ), Department
    •	Performance Metrics: Ratings, Leaves Used, Leaves Remaining
    •	Salary Information: Current Salary
    •	Professional Experience: Past Work Experience (years)

## Methodology

    1.	Data Preprocessing:
    •	Handle missing values, encode categorical variables, and normalize numerical data.
    •	Conduct exploratory data analysis (EDA) to understand feature relationships and distributions.
    2.	Feature Engineering:
    •	Engineer new features if necessary (e.g., tenure from DOJ).
    •	Select relevant features for the regression model.
    3.	Model Building:
    •	Train multiple regression models (e.g., Linear Regression, Ridge, Lasso) to predict salaries.
    •	Evaluate models using cross-validation and test datasets.
    4.	Interpretation:
    •	Identify the most influential predictors of salary.
    •	Interpret the regression coefficients to derive insights.

## Results

## Deliverables
    •	Project Presentation (PowerPoint)
    •	Final r file
    
## Technologies Used
    •	rStudio
    
# Task assignments

## Petros
  1. Offer a preliminary description of the data set. For example, indicate the size of the data source, describe the variables, and include any other data profile information that would be of interest.
  2. Generate relevant data visual plots that explore multicollinearity for the quantitative variables and normality for the quantitative variables as well.  Also, use R code to confirm the levels of the categorical variables.
  3. Using R code, produce a full Regression Model that consists of quantitative and categorical variables.  Make use of the R generated dummy variable matrices

## Max
  4. Using only the quantitative variables as predictors, produce a model using matrix methods. Also use matrix methods to find the fitted values and the residuals
  5. Produce an output summary table to be used to analyze and evaluate the full model (Adjusted R squared, Standard Error, Significance of Variables, ect…)
  6. Use procedures and techniques explored in class to produce confidence intervals for the independent quantitative variables of your model. Choose at least two of the quantitative variables to find confidence intervals for.

## Grace
  7. Now produce a reduced model (removing variables of your choice with justification). Use R summary coding for both models and offer justification for choosing one model over the other.
  8. Research and apply a model analysis technique not discussed in class to your full model or reduced model.  Fully explain the technique or procedure and how it is being applied to your specific model.
  9. Offer final summary perspectives about the data and the models that you produce, suggesting how your models or model analysis enhanced your understanding of the data.   (4 or 5 sentences)
