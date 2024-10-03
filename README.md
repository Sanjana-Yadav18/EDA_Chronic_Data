# EDA_Chronic_Data_Analytics_Project

# Project Overview

The EDA_Chronic_Data_Analytics project aims to perform comprehensive Exploratory Data Analysis (EDA) on a chronic disease dataset. The primary goal is to explore, understand, and uncover patterns and trends in the dataset that could offer insights into the factors influencing chronic diseases. By analyzing various health indicators, we aim to identify relationships between different medical conditions and derive actionable insights to aid healthcare decision-making.

# Dataset Description

The dataset contains medical information of patients related to chronic disease conditions. It includes 25 columns that describe various physiological and clinical measurements, test results, and disease indicators. Below is a detailed description of the columns in the dataset:

# Columns:

age: Age of the patient.
blood_pressure: Blood pressure levels of the patient.
specific_gravity: Urine specific gravity test results.
albumin: Presence of albumin in urine.
sugar: Presence of sugar in urine.
red_blood_cells: Count of red blood cells.
pus_cell: Count of pus cells in urine.
pus_cell_clumps: Presence of pus cell clumps.
bacteria: Presence of bacteria in urine.
blood_glucose_random: Random blood glucose levels.
blood_urea: Urea levels in blood.
serum_creatinine: Creatinine levels in blood.
sodium: Sodium levels in blood.
potassium: Potassium levels in blood.
haemoglobin: Haemoglobin levels in blood.
packed_cell_volume: Volume of packed red blood cells.
white_blood_cell_count: Count of white blood cells.
red_blood_cell_count: Count of red blood cells.
hypertension: Presence of high blood pressure (yes/no).
diabetes_mellitus: Presence of diabetes (yes/no).
coronary_artery_disease: Presence of coronary artery disease (yes/no).
appetite: Patient's appetite (good/poor).
peda_edema: Presence of pedal edema (swelling in feet).
aanemia: Presence of anemia (yes/no).
class: Target variable indicating whether the patient is suffering from a chronic condition (yes/no).

# Objective

The objective of this project is to:

Perform data cleaning and preprocessing to prepare the dataset for analysis.
Conduct univariate, bivariate, and multivariate analysis to explore patterns in the data.
Visualize the data to gain insights into various chronic disease indicators.
Analyze correlations between different features to understand how they interact with each other and contribute to chronic diseases.

# Steps Performed

1. Data Cleaning and Preprocessing
Handled missing data by either imputing with the median (for numerical variables) or mode (for categorical variables).
Checked for outliers in the dataset using boxplots and removed/treated extreme values where necessary.
Ensured correct data types for each column, especially categorical variables.
2. Univariate Analysis
Examined the distribution of each feature.
Generated summary statistics for numerical features like age, blood pressure, and blood glucose.
Visualized the frequency of categorical features like hypertension, diabetes mellitus, coronary artery disease, etc.
3. Bivariate Analysis
Explored relationships between various features using correlation analysis for numerical data.
Used scatter plots and pair plots to visualize relationships between important health indicators (e.g., blood pressure vs age).
Analyzed categorical vs numerical data using box plots (e.g., blood glucose levels across different diabetes categories).
4. Multivariate Analysis
Created a heatmap of the correlation matrix to understand the strength of relationships between multiple variables.
Explored interactions between multiple categorical variables and their impact on the target class (chronic condition).
Investigated feature importance for predicting chronic conditions based on health indicators.
5. Visualization
Created histograms, box plots, scatter plots, and pair plots to visualize data distributions and relationships.
Used heatmaps for correlation analysis and bar plots for visualizing categorical data.

# Insights and Observations

Blood Glucose: Elevated blood glucose levels were strongly associated with diabetes mellitus.
Hypertension and Age: Older patients showed a higher likelihood of hypertension.
Serum Creatinine and Blood Urea: High levels of serum creatinine and blood urea were linked to poor kidney function, indicating a correlation with chronic conditions.
Anemia: Patients with chronic conditions often exhibited lower haemoglobin levels, indicating a higher occurrence of anemia.
Bivariate Analysis: A strong positive relationship was found between blood pressure and hypertension.

# Tools and Libraries

The following Python libraries were used to perform EDA and visualization:

Pandas: For data manipulation and cleaning.
NumPy: For numerical operations.
Matplotlib: For visualizations.
Seaborn: For advanced data visualization.
SciPy: For statistical analysis.
