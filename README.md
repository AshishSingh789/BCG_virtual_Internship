# BCG X Virtual Internship - Data Science Project
This repository contains the work I completed during the BCG X Virtual Internship (June 2024 - September 2024) offered through Forage. The project focused on analyzing customer churn for a company named PowerCo, utilizing the full data science process from business understanding to model evaluation.

# Project Overview
As part of this virtual internship, I worked on various tasks that mirror the typical responsibilities of a Data Scientist at BCG X. These tasks were designed to give hands-on experience in solving business problems using data-driven methodologies.

# Tasks Completed:
# 1. Business Understanding & Hypothesis Framing
Framed PowerCo's problem in the context of customer churn.
Defined key hypotheses and identified important factors such as pricing, customer service, and energy preferences (clean energy vs. conventional).
Outlined the data requirements needed to investigate customer churn and provided an approach for analyzing these factors.


# 2. Exploratory Data Analysis (EDA)
Analyzed historical customer and pricing data, along with churn indicators.
Explored data types, generated descriptive statistics, and visualized distributions to understand underlying patterns.
Used Python (Jupyter notebook) to perform these analyses, focusing on key attributes affecting churn.


# 3. Feature Engineering & Modelling
Created new features to enhance the predictive capability of the model, such as extracting date components and combining columns to form meaningful features.
Evaluated which columns could be removed or combined to improve model performance.
Combined the provided datasets to create a final dataset for modeling.


# 4. Modeling and Evaluation
Built and trained a Random Forest classifier using the scikit-learn library to predict customer churn.
Evaluated the model using performance metrics like accuracy, precision, and recall.
Discussed the justification for chosen evaluation metrics and provided a summary of the model's performance.
Provided insights and recommendations on how PowerCo could reduce churn based on the model’s predictions.


# Repository Structure
bash
Copy code
├── data/
│   └── data_for_predictions.csv   # Final dataset for modeling (not uploaded here)
├── notebooks/
│   ├── task1_business_understanding.ipynb
│   ├── task2_exploratory_data_analysis.ipynb
│   ├── task3_feature_engineering.ipynb
│   └── task4_modeling_and_evaluation.ipynb
├── README.md                      # Project README file
└── .gitignore                     # Git ignore file for data and sensitive files


# Technologies Used
Python
Jupyter Notebooks
Pandas, NumPy for data manipulation
Matplotlib, Seaborn for data visualization
Scikit-learn for machine learning (Random Forest)
Conclusion
Through this internship, I gained hands-on experience with real-world data science problems, from formulating business problems to building and evaluating predictive models. The work provided a comprehensive understanding of the key stages in the data science workflow, from EDA to feature engineering and modeling.

For more details on the individual tasks, check out the Jupyter notebooks in the repository.
