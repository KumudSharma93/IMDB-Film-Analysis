# Analyzing the Relationship Between IMDB Ratings with Film Indicators: Prediction & Diagnostics

## 1. Introduction
This project investigates the relationship between various film attributes and IMDB ratings, leveraging data from the IMDB film database. The dataset includes factors such as:
- **Film ID**  
- **Release Year**  
- **Length**  
- **Budget**  
- **Votes**  
- **Genre**  
- **IMDB Rating**  

The central research question examines whether specific film attributes contribute to IMDB ratings greater than seven. A Generalized Linear Model (GLM) analysis was performed to uncover these relationships. This study was conducted as part of the University of Glasgow MSc Data Analytics program (2023-24) for the course *Data Analysis Skills*, using a dataset provided by course instructors.

---

## 2. Project Objectives
The key objectives of this study include:
1. Performing **data wrangling** to clean and preprocess the dataset.  
2. Conducting **exploratory data analysis (EDA)** to identify patterns and trends.  
3. Applying **formal data analysis (FDA)** using Generalized Linear Models (GLM) to evaluate the relationship between film properties and IMDB ratings.  
4. Conducting **model checking and diagnostics** to assess model validity and predictive accuracy.

---

## 3. Methodology
This analysis was conducted using R, a powerful statistical programming language, and GitHub was team collaboration. The key steps involved:

### 3.1 Data Wrangling

- Cleaning and transforming the raw dataset.

- Handling missing values and outliers.

- Converting categorical variables (e.g., genre) into usable formats.

### 3.2 Exploratory Data Analysis (EDA)

Visualizing distributions, trends, and relationships.

Understanding how attributes like budget, duration, and votes correlate with IMDB ratings.

##3 3.3 Formal Data Analysis (FDA)

Building and fitting a Generalized Linear Model (GLM) to predict IMDB ratings.

Identifying key film attributes that influence ratings greater than seven.

### 3.4 Model Checking and Diagnostics

Evaluating model assumptions (linearity, residuals, etc.).

Validating predictive accuracy and robustness of the model.


---

## 5. Key Results

Identified key predictors of IMDB ratings greater than seven, including votes, budget, and duration.

Highlighted the influence of genre and release year on film ratings.

Diagnosed model performance using residual analysis and validated predictions.

---

## 6. Tools and Technologies

Programming Language: R

Libraries: tidyverse, ggplot2, dplyr, caret, MASS

Statistical Methods: Generalized Linear Models (GLM), diagnostics tools



Note: This repository is for educational purposes only. The dataset is proprietary and provided exclusively for coursework.
