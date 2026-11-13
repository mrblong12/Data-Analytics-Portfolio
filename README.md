# Matthew Blong - Data Analytics Portfolio
## About
Hi, I'm Matthew! And while finishing up my Bachelors in Psychology, I took two foundational classes, Quantitative Psychology and Psychological Archival Data Science, which exposed me to the many possibilities that statistical analysis and data science had to offer. In those classes, I learned for the first time to code in both SAS and R programming languages. These experiences excited my curiosity and made me want to dive deeper into this field. After taking some time away from school and working as a Patient Access Specialist at the University of Colorado Emergency Department (one of the busiest in the country!), I decided to jump back into my studies and enrolled in Colorado State University's Masters in Applied Statistics Program. Upon graduating, I gained invaluable skills in statistical analysis and programming to prepare me as a future Data Scientist.

## Table of Contents
- [Portfolio Projects](https://github.com/mrblong12/Data-Analytics-Portfolio#portfolio-projects)
  - Python
      - [Exploring Breast Cancer Classification with Machine Learning](https://github.com/mrblong12/Data-Analytics-Portfolio#exploring-breast-cancer-classification-with-machine-learning)
      
  - R
      - [Classification of Leopard Frogs Native to Colorado](https://github.com/mrblong12/Data-Analytics-Portfolio#classification-of-leopard-frogs-native-to-colorado)
      - [Effects of Exercise and Sleep on Cognitive Function](https://github.com/mrblong12/Data-Analytics-Portfolio#effects-of-exercise-and-sleep-on-cognitive-function)
      - [Final Project: an Exploration of the 'airquality' Dataset](https://github.com/mrblong12/Data-Analytics-Portfolio#data-visualization-of-new-york-state-air-quality-metrics)
  - Power BI
      - [Exploring the Reasons behind Attrition](https://github.com/mrblong12/Data-Analytics-Portfolio#ibm-hr-employee-attrition-rates)
  - [Education](https://github.com/mrblong12/Data-Analytics-Portfolio#education)
  - [Contact](https://github.com/mrblong12/Data-Analytics-Portfolio#contacts)
      
  

## Portfolio Projects
In this section I will list data analytics projects briefly describing the technology stack used to solve cases.



### Exploring Breast Cancer Classification with Machine Learning
**Code:** [`Breast_Cancer_Classification_Code.ipynb`](https://github.com/mrblong12/Portfolio-Projects/blob/main/Breast_Cancer_Classification_Code.ipynb)

**Report:** [`Model Comparison in Breast Cancer Classification: a Machine Learning Project`](https://github.com/mrblong12/Portfolio-Projects/blob/main/Breast%20Cancer%20Classifcation%20Project.pdf)

**Goal:** compare several machine learning models (deep neural network, logistic regression, support machine vector, random forests, and XGBoost) to demonstrate which model is best suited for this classification.

**Description:** Using data from the University of Wisconsin, we use test out several machine learning algorithms and after extensive fine tuning, determine which algorithm through performance metrics such as accuracy and F1 score best predicts whether digitizes breast FNA’s are malignant or benign. 

**Skills:** machine learning algorithms, feature importance, fine tuning

**Technology:** Python, pandas, random, tensorflow, numpy, sklearn, keras_tuner

**Results:** Through our exploration of different machine learning models, we found that, after fine tuning our hyper parameters, our Support Machine Vector model produced the highest test accuracy and F1-score, which is the harmonic mean of precision and recall, for predicting malignant versus benign tumors from the Breast Cancer Wisconsin Diagnostic Data Set.


### Classification of Leopard Frogs Native to Colorado
**Code:** [`Classification_of_Leopard_Frogs.rmd`](https://github.com/mrblong12/Portfolio-Projects/blob/main/Final%20ReportV2%20(1).Rmd)

**Report:** [`Classification of Leopard Frogs Native to Colorado: an Exploratory Analysis`](https://github.com/mrblong12/Portfolio-Projects/blob/main/Classification%20of%20Leopard%20Frogs%20Native%20to%20Colorado.pdf)

**Goal:**  Investigate three machine learning methods (Random Forest, Multinomial Logistic Regression, and GLMET) to optimize classification between Northern Leopard Frogs, Plains Leopard Frogs, and hybrids.

**Description:** After cleaning data and preliminary exploratory analysis, we test out several machine learning algorithms and after fine tuning our hyper-parameters, we determine the best algorithm to predict frog species through metrics, such as precision, recall, F1 score, and balanced accuracy.

**Skills:** data cleaning, machine learning algorithms, data visualization, feature importance, fine tuning

**Technology:** R, kableExtra, ggplot2, dplyr, emmeans, effects, pbkrtest, table1, tidyverse, caret, ranger, MLmetrics, C50, gbm, table1, kernlab, ggthemes

**Results:** High accuracy metrics, such as precision, recall, F1 score, and balanced accuracy, across species and inherent feature selection leads us to believe that GLMNET is the best machine learning method for leopard frog species classification using categorical physical identifiers.



### Effects of Exercise and Sleep on Cognitive Function
**Code:** [`Island_Project_final.rmd`](https://github.com/mrblong12/Portfolio-Projects/blob/main/Island_Project_final.Rmd)

**Report:** [`Effects of Exercise and Sleep on Cognitive Function: a Repeated Measures Study`](https://github.com/mrblong12/Portfolio-Projects/blob/main/Effects%20of%20Exercise%20and%20Sleep%20on%20Cognitive%20Function.pdf)

**Goal:** Understand how varying levels of aerobic exercise intensity and sleep duration affect performance on mental aptitude tests measuring attention, memory, and mental arithmetic.

**Description:** Through a simulated population with *The Islands* website, we had participants perform various aerobic exercise of varying levels of difficulty and then complete a variety of mental aptitude tests over several weeks in order to study the relationship between exercise and cognitive acuity. 

**Skills:** Linear Mixed Models, data visualization, data collection, hypothesis testing, repeated measures, data cleaning

**Technology:** R, Excel, kableExtra, ggplot2, lme4, nlme, lmerTest, dplyr, emmeans, effects, pbkrtest, table1

**Results:** We found that sleep moderated the negative effects of the highest intensity exercise type, possibly suggesting that how much sleep a participant received the night before can improve cognitive ability after physical exhaustion from aerobic exercise.



### Data Visualization of New York State Air Quality Metrics
**Code:** [`Air_Quality_Visualization_Code.rmd`](https://github.com/mrblong12/Portfolio-Projects/blob/main/Air%20Quality%20Visualization%20in%20R%20-%20code.Rmd)

**Report:** [`Final Project: an Exploration of the 'airquality' Data Set`](https://github.com/mrblong12/Portfolio-Projects/blob/main/Air-Quality-Visualization-in-R.pdf)

**Goal:** Understand how meteorological factors and air quality measurements affect (or simply have a relationship with) daily maximum temperature through various data visualizations.

**Description:** Through exploring several visualizations, such as ridgeline plots, 3D scatter plots, time series plots, and correlation matrices, determine the relationships between different air quality metrics and infer their subsequent environmental impact. 

**Skills:** EDA, data cleaning, data visualization, linear regression, correlation

**Technology:** R, tidyverse, ggplot2, dplyr, reshape2, ggExtra, ggridges, rgl

**Results:** In all, through this visual and quantitative exploration of the ‘airquality’ data set in R, we found key factors such as Ozone (ppb) and Solar Radiation (Langley) that may influence Temperature (°F), which could provide key findings toward understanding and predicting the effects of air quality on rising temperatures by encouraging further interest in how to decrease levels of pollutants that contribute toward smog-forming reactions.


### IBM HR Employee Attrition Rates
**Code:** [`Employee_Attrition_Rate_Group_Project`](https://github.com/mrblong12/Portfolio-Projects/blob/main/Employee%20Attrition%20Rate%20Group%20Project.pbix)

**Report:** [`Power BI Attrition Rate Project`](https://github.com/mrblong12/Portfolio-Projects/blob/main/Power%20BI%20Report.pdf)

**Goal:** Analyze employee attrition and retention through the IBM HR simulated data set

**Description:** With Power BI, we transformed and visualized the data, allowing for insights into what factors contribute most to attrition and how these patterns can inform a company's human resources and business strategies. Employee attrition remains a pressing concern for businesses, as it directly impacts operational costs and efficiency1. By analyzing factors salary, education, and job satisfaction with Power BI, we aim to provide actionable insights into which attributes have the most impact on employee attrition in order to develop strategies to reduce turnover and improve retention.


**Skills:** data visualization, data modeling, BI dashboards

**Technology:** Power BI

**Results:** Our visualizations and analyses suggest that salary is a significant factor in employee attrition, with employees in lower salary ranges exhibiting higher turnover rates, whereas education, job satisfaction, and job level also play a role albeit to a lesser extent.


## Education
Colorado State University: 
Master's in Applied Statistics - MAS, Statistical Science,
Aug 2024 - June 2026

University of North Carolina at Chapel Hill:
Bachelor's of Science, Psychology,
2017 - 2022

## Contacts
- LinkedIn: [@MatthewBlong](https://www.linkedin.com/in/matthew-blong-330117316/)
- Email: mrblong12@gmail.com
