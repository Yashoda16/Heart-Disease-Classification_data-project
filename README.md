# Heart-Disease-Classification_data-project

# Overview
This project aims to predict the presence of heart disease in patients based on a variety of medical attributes. Using machine learning techniques, the project identifies key factors that contribute to heart disease and provides actionable insights for healthcare decision-making.

# Dataset
The dataset used in this project contains the following attributes:

Age: The age of the patient.

Gender: Gender of the patient (0 = Female, 1 = Male).

Chest Pain Type: Categorized as 0-3, representing different types of chest pain.

Resting Blood Pressure: The patient’s resting blood pressure (in mm Hg).

Cholesterol: Serum cholesterol in mg/dl.

Fasting Blood Sugar: > 120 mg/dl (0 = No, 1 = Yes).

Resting ECG: Resting electrocardiographic results (0 = Normal, 1 = Abnormality).

Max Heart Rate: Maximum heart rate achieved during testing.

Exercise-Induced Angina: (0 = No, 1 = Yes).

Oldpeak: ST depression induced by exercise relative to rest.

Slope: The slope of the peak exercise ST segment.

Number of Major Vessels: Number of major vessels colored by fluoroscopy (0-3).

Thal: Thalassemia (0 = Normal, 1 = Fixed Defect, 2 = Reversible Defect).

Target: Diagnosis of heart disease (0 = No, 1 = Yes).

# Project Workflow

**1. Data Preprocessing**

Handling Missing Values: Checked for and managed any missing values within the dataset.

Label Encoding: Converted categorical variables into numerical formats.

Outlier Detection: Identified and addressed any outliers to ensure robust model performance.

**2. Exploratory Data Analysis (EDA)**

Conducted EDA to gain insights into the distribution of variables and their relationships with the target variable. Visualized key findings using Tableau dashboards.

**3. Model Building**

Machine Learning Models: Applied Logistic Regression, Random Forest, Gradient Boosting, and Decision Tree classifiers.
Cross-Validation: Performed cross-validation to assess model performance and ensure generalization.
Oversampling: Addressed class imbalance using oversampling techniques, leading to improved performance on minority classes.

**4. Results**

**Model Performance:** Evaluated models based on accuracy, precision, recall, and F1-score.

**Insights:** Generated actionable insights that could assist healthcare professionals in predicting and managing heart disease risk.

# Visualization

Created interactive dashboards using Tableau to visualize patient data and model predictions, helping to uncover trends and relationships in the dataset.

# Conclusion

The project successfully predicted heart disease presence with high accuracy and provided key insights into the factors that contribute to heart disease, potentially aiding in early detection and preventive measures.

# Getting Started

**Prerequisites**

Python 3.x

Jupyter Notebook

Required Python libraries: pandas, numpy, scikit-learn, matplotlib, seaborn, tableau-api-lib

**Running the Project**

Load the dataset.

Run the data preprocessing steps.

Perform EDA and visualize insights.

Train the models and evaluate performance.

Explore the Tableau dashboard for interactive insights

## Tableau Dashboard
You can view the interactive Tableau dashboard [here](https://public.tableau.com/views/HeartDiseaseDataVisualization_17254256599980/Dashboard1?:language=en-US&publish=yes&:sid=&:display_count=n&:origin=viz_share_link&:device=desktop).
