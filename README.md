# -aiml-Heart-Disease-Prediction-Using-Logistic-Regression
The purpose of this project is to predict the risk of developing cardiovascular disease (CVD) within the next ten years for patients using logistic regression.

google collab link--> https://colab.research.google.com/drive/1LYhlxG6pPUCMZpLtW94Bj3JIi5BACD-9
dataset link--> https://media.geeksforgeeks.org/wp-content/uploads/20240307152534/framingham.csv

**1) Purpose of the project:**
The purpose of this project is to predict the risk of developing cardiovascular disease (CVD) within the next ten years for patients using logistic regression. By analyzing various demographic and health-related factors from the Framingham Heart Study dataset, the project aims to identify individuals who may be at higher risk of CVD, enabling early intervention and preventive measures.

**2) Concept of AIML used: Logistic Regression**
Logistic Regression is a statistical and machine learning technique used for binary classification tasks, such as predicting whether an event will occur or not (in this case, whether a patient will develop CVD in the next ten years). Unlike linear regression, which predicts continuous values, logistic regression predicts the probability of a binary outcome based on one or more independent variables. It works by fitting a logistic curve to the data, which allows for the estimation of the probability of the event occurring.

**3) Tech stack used:**
- **Programming Language:** Python
- **Libraries and Frameworks:**
  - Pandas: For data manipulation and analysis.
  - NumPy: For numerical computations.
  - Scikit-learn: For machine learning tasks, including logistic regression modeling.
  - Matplotlib and Seaborn: For data visualization.
- **Data Source:** Framingham Heart Study dataset (framingham.csv)
- **Other Tools:** google collab  for coding and execution.

This project primarily utilizes Python along with various libraries and tools commonly used in data science and machine learning projects.

**Dataset Description:**
The dataset from Framingham, Massachusetts, contains health-related factors like demographics, behavior, medical history, and clinical measurements. The goal is to predict the 10-year risk of coronary heart disease (CHD) for each patient.

**Project Workflow:**

1. **Data Preparation:** Load dataset, drop irrelevant columns, handle missing values.

2. **Data Analysis and Visualization:** Explore data distribution and relationships using EDA and visualizations.

3. **Data Splitting:** Split dataset into 70% training and 30% testing sets.

4. **Model Training:** Use Logistic Regression to predict CHD risk after standardizing features.

5. **Model Evaluation:** Assess model accuracy using accuracy_score(), confusion matrix, and classification report.

6. **Results Interpretation:** Understand model performance and guide further actions in clinical practice for identifying individuals at higher risk of CHD.
