# vehicle-insurance-cross-sell-analysis
End-to-end vehicle insurance cross-sell analysis using Python, exploratory data analysis, statistical hypothesis testing, feature engineering, and machine learning. Compares classification models to identify potential customers for targeted marketing campaigns.

## 👋 About This Project

Hello! I'm **Poojitha Kore**, an MSc Data Science, AI & Digital Business student with an interest in Data Analytics and Business Intelligence.

This is one of my portfolio projects, developed to strengthen my practical skills in Python, data analysis, statistical methods and machine learning.

In this project, I analyse customer data to understand which existing health insurance customers are more likely to respond positively to a vehicle insurance cross-selling offer.

My objective is to explore customer behaviour, identify meaningful patterns and build a classification model that could support data-driven marketing decisions.

## Business Problem

Insurance companies need to identify potential customers who may be interested in additional insurance products.

The main objective of this project is to analyse customer characteristics and predict the likelihood of a positive response to a vehicle insurance offer.

## Dataset Overview

- **Total records:** 381,109
- **Target variable:** `Response`
- **Response = 0:** Customer did not respond positively
- **Response = 1:** Customer responded positively

## Tools and Technologies

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow

1. Business understanding
2. Data loading and understanding
3. Data cleaning and validation
4. Exploratory Data Analysis (EDA)
5. Statistical hypothesis testing
6. Feature engineering
7. Data preprocessing
8. Machine learning model development
9. Model evaluation and comparison
10. Business insights and recommendations

## Machine Learning Models

I developed and compared three classification algorithms:

- Logistic Regression
- Random Forest
- Decision Tree

Random Forest was selected as the final model based on the validation results.

## Model Performance

The final Random Forest model was evaluated on a separate test dataset.

| Evaluation Metric | Result |
|---|---:|
| Accuracy | 77.86% |
| Precision | 32.67% |
| Recall | 75.99% |
| F1-score | 0.46 |
| ROC-AUC | 0.8527 |
| Average Precision | 0.3566 |

The model achieved a recall of 75.99%, meaning it identified approximately 76% of the actual positive responders in the test dataset.

## Key Findings

- Vehicle damage history and previous insurance status were the most influential features in the Random Forest model.
- Customer age, vehicle age and policy sales channel also contributed to the model's predictions.
- The selected classification threshold was 0.69, based on validation F1-score optimisation.
- The analysis highlights how customer data can support more focused marketing campaigns.

## Limitations

- The model has relatively low positive-class precision.
- The classification threshold was selected using F1-score rather than actual campaign costs and revenue.
- Exploratory analysis and statistical testing were conducted before the train-test split.
- Further validation using independent future campaign data would be useful.

## What I Learned

Through this project, I gained practical experience in:

- Working with a large dataset.
- Performing exploratory and statistical analysis.
- Preparing data for machine learning.
- Comparing classification algorithms.
- Evaluating model performance with imbalanced data.
- Translating analytical results into business insights.

## Future Improvements

I would like to improve this project further by exploring:

- Hyperparameter tuning
- Probability calibration
- Cost-based threshold selection
- Permutation feature importance
- Additional model validation

## 🤝 Feedback and Suggestions

I am continuously learning and improving my data analytics skills.

Suggestions, constructive feedback and recommendations are always welcome! I would appreciate insights from fellow learners, data analysts and professionals that could help me improve this project and my analytical approach.

Thank you for visiting my repository!

## Author

**Poojitha Kore**

MSc Data Science, AI & Digital Business  
Aspiring Data Analyst

- **LinkedIn:** [linkedin.com/in/poojitha-kore](https://www.linkedin.com/in/poojitha-kore)
- **GitHub:** [github.com/Poojithasony](https://github.com/Poojithasony)

