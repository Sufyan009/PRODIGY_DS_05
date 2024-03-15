# Traffic Accident Data Analysis 

## Overview
This repository contains the code and analysis for exploring traffic accident data to identify patterns related to road conditions, weather, and time of day. The analysis aims to visualize accident hotspots and contributing factors to improve understanding and decision-making in traffic safety.

## Data Source
The dataset used for this analysis is stored in the file `RTA Dataset.csv`. It contains information about various aspects of traffic accidents including severity, number of casualties, number of vehicles involved, road conditions, weather, time of day, and more.

## Libraries and Tools
- Python programming language
- Libraries:
  - NumPy
  - Pandas
  - Seaborn
  - Matplotlib
  - Scikit-learn
  - Imbalanced-learn (for SMOTE oversampling)
  
## Analysis Steps
1. **Loading Libraries and Data**: Importing necessary libraries and loading the dataset for analysis.
2. **Exploratory Data Analysis (EDA)**: Understanding the structure of the dataset, checking for missing values, exploring distributions, and identifying initial patterns.
3. **Data Visualization**: Visualizing relationships between variables, identifying accident hotspots, and exploring correlations.
4. **Handling Categorical Values**: Using label encoding and dummy variables to handle categorical data.
5. **Feature Selection**: Utilizing chi-square analysis to select important features for modeling.
6. **Model Development**: Creating a K-Nearest Neighbors (KNN) classification model to predict accident severity.
7. **Model Evaluation**: Assessing model performance through accuracy score, classification report, and confusion matrix.

## Model Performance
The KNN model achieved an accuracy of approximately 74% in predicting accident severity on the test dataset. Detailed classification report and confusion matrix are provided for further analysis.

## Repository Contents
- `RTA Dataset.csv`: The raw dataset used for analysis.
- `Traffic_Accident_Analysis.ipynb`: Jupyter Notebook containing the code for data analysis, visualization, model development, and evaluation.
- `README.md`: This file providing an overview of the repository and analysis.

## Instructions
1. Clone the repository to your local machine.
2. Ensure you have Python and necessary libraries installed.
3. Open and run the Jupyter Notebook `Traffic_Accident_Analysis.ipynb` to view the analysis process and results.

Feel free to explore, modify, or extend the analysis as per your requirements.

For any questions or feedback, please contact Sufyan Ahmad at sufianjellani@gmail.com.

Thank you for your interest!