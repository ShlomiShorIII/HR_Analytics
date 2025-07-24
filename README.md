# 🔍 Employee Attrition Analysis

## About the Project
This project was completed as part of a university data analysis course.  
The main objective was to analyze the **Attrition** target column – indicating whether an employee left the company – and to build predictive models using both Exploratory Data Analysis (EDA) and machine learning algorithms.

## Objectives
- Identify the most influential factors affecting employee attrition.
- Build statistical models capable of predicting attrition in advance.
- Generate actionable business insights to help organizations reduce attrition rates.

## Workflow
1. **EDA** – Initial analysis to understand trends and patterns in the data.
2. **Feature Engineering** – Creating new variables based on stagnation, satisfaction, and work-life balance.
3. **Class Balancing** – Handling imbalanced classes between leavers and non-leavers.
4. **Model Building & Comparison** – Applying Logistic Regression, Decision Trees, and other models.
5. **Business Insight Extraction** – Translating results into practical recommendations for employee retention.

## Key Insights
- Low satisfaction and poor work-life balance were strong predictors of attrition.
- Monthly income consistently appeared among the top predictors in models, even though it was not prominent in the EDA.
- Feelings of professional stagnation were identified in the EDA but did not emerge as strong predictors in modeling.
- The best-performing model was Logistic Regression with engineered features, achieving a Recall of 74.3% and an F1 Score of 0.495.

## Dataset Information
The dataset used in this project is publicly available on Kaggle:  
🔗 **[HR Analytics Dataset – Kaggle](https://www.kaggle.com/datasets/saadharoon27/hr-analytics-dataset)**  
The page includes column descriptions and metadata explaining each feature in the dataset.

## Tools and Language
- Programming Language: **Python**
- Main Libraries: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`

## How to Run the Code
1. Open the notebook file: `HR Analytics Dataset - Shlomi Shor III.ipynb`.
2. Make sure the dataset file `Employee-Attrition.csv` is in the same directory.
3. Run the code cells in order from top to bottom.

## Project Files
- `HR Analytics Dataset - Shlomi Shor III.ipynb` – Main notebook with the entire analysis process.
- `Employee-Attrition.csv` – The employee dataset used for modeling and analysis.
- `Presentation.pdf` – Summary presentation including workflow, insights, model comparison, and business recommendations.

## Credits
Created by:  
**Shlomi Shor III**
