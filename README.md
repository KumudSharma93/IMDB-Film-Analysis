# Analyzing the Relationship Between IMDB Ratings with Film Indicators: Prediction & Diagnostics

## Introduction
This project investigates the relationship between various film attributes and IMDB ratings, using data from the IMDB film database. The dataset includes factors such as:
- **Film ID**  
- **Release Year**  
- **Length**  
- **Budget**  
- **Votes**  
- **Genre**  
- **IMDB Rating**  

The central research question examines whether specific film attributes contribute to IMDB ratings greater than seven. A Generalized Linear Model (GLM) analysis was performed to uncover these relationships. This study was conducted as part of the University of Glasgow MSc Data Analytics program (2023-24) for the course *Data Analysis Skills*, using a dataset provided by course instructors.

---

## Project Objectives
The key objectives of this study include:
1. Performing **Data Wrangling** to clean and preprocess the dataset.  
2. Conducting **Exploratory Data Analysis (EDA)** to identify patterns and trends.  
3. Applying **Formal Data Analysis (FDA)** using Generalized Linear Models (GLM) to evaluate the relationship between film properties and IMDB ratings.  
4. Conducting **Model Checking and Diagnostics** to assess model validity and predictive accuracy.

---

## Files and Structure

- **R Folder**:  
  - `project_analysis.qmd`: Quarto markdown file for Generalized Linear Models (GLM), data wrangling, and analysis.  
  - `project_report.pdf`: PDF version of the complete project report, including analysis and results.  
---

## Tools and Technologies

- **Languages**: R  
- **Techniques**: Generalized Linear Models (GLM), Predictive Modelling, Data Validation, Model Optimization, Statistical Diagnostics
- **Version Control and Collaboration**: GitHub (used for team collaboration, version control, and project management)   
- **Libraries**:  
  - **R**:  
    - `ggplot2`  
    - `dplyr`  
    - `tidyverse`  
    - `gt`  
    - `patchwork`  
    - `gridExtra`  
    - `moderndive`  
    - `MASS`  
    - `knitr`  
    - `GGally`  
    - `skimr`  
    - `ggpubr`  
    - `sjPlot`  
    - `broom`  
    - `pROC`  
    - `janitor`

## Insights

The final GLM model (high_rating ~ length + budget + genre) was selected for its superior performance, with length, budget, and genre identified as significant predictors of IMDB ratings greater than 7. The model outperformed alternatives based on its lowest BIC, statistical significance, and robust residual diagnostics, while variables like release year added minimal predictive value.

