Overview

This project aims to predict the likelihood of heart disease based on various health and lifestyle parameters using data analytics and machine learning techniques.
The implementation is carried out in Python, leveraging libraries such as Pandas, Matplotlib, Seaborn, and Scikit-learn.
The workflow includes data preprocessing, exploratory data analysis (EDA), and model preparation for future predictive modeling.

Objective

The primary objective of this project is to analyze medical and lifestyle factors influencing heart disease and develop a data-driven approach to predict its occurrence.

Dataset Description

The dataset used for this project is heart_disease_dataset.csv, containing 1000 records and 16 features.

Key Features

Demographic Data: Age, Gender

Health Indicators: Cholesterol, Blood Pressure, Heart Rate, Blood Sugar

Lifestyle Factors: Smoking, Alcohol Intake, Exercise Hours, Stress Level

Medical History: Family History, Diabetes, Obesity, Exercise Induced Angina, Chest Pain Type

Target Variable: Heart Disease (1 = Presence, 0 = Absence)

Methodology
1. Data Preprocessing

Handled missing values (Alcohol Intake column contained NaN values).

Dropped the Alcohol Intake column due to significant missing data.

Encoded categorical variables using LabelEncoder.

Split the dataset into training (80%) and testing (20%) subsets using train_test_split.

2. Exploratory Data Analysis (EDA)

Visualized distributions and relationships using Seaborn and Matplotlib.

Analyzed correlations among numerical features.

Examined the frequency of categorical features and their relation to heart disease prevalence.

3. Feature Engineering (Optional)

Checked feature uniqueness and importance.

Prepared data for potential integration with classification algorithms such as Logistic Regression, Random Forest, and XGBoost.

Tools and Technologies

Programming Language: Python

Development Environment: Google Colab

Libraries Used:

pandas — data manipulation and analysis

matplotlib and seaborn — data visualization

scikit-learn — preprocessing, encoding, and model splitting

Results

Successfully preprocessed the dataset for modeling.

Conducted thorough EDA to understand key influencing factors.

The prepared data is ready for implementation of machine learning models.

Future Scope

Implement multiple classification models to predict heart disease.

Perform model evaluation using accuracy, precision, recall, and F1-score.

Optimize models using hyperparameter tuning.

Deploy the final model using frameworks like Streamlit or Flask for real-time prediction.

Author

Anshuman Tiwari
B.Tech in Computer Science (AIML)
India

For any queries or collaborations, feel free to connect.
