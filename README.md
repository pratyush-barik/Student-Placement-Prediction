# Student Placement Prediction

## Description

This project predicts student placement outcomes using academic and skill-based attributes. Data preprocessing, categorical encoding, feature scaling, and classification models including Logistic Regression, Decision Tree, and Random Forest were applied to evaluate placement prediction performance.

---

## Dataset Overview

- **Dataset:** Student Placement Prediction Dataset
- **Records:** 10,000
- **Features:** 10
- **Target Variable:** Placement (Yes/No)

### Dataset Attributes

| Feature | Description |
|----------|-------------|
| College_ID | Unique college identifier |
| IQ | Student IQ score |
| Prev_Sem_Result | Previous semester GPA |
| CGPA | Cumulative Grade Point Average |
| Academic_Performance | Annual academic rating |
| Internship_Experience | Internship completion status |
| Extra_Curricular_Score | Extracurricular involvement score |
| Communication_Skills | Communication skill rating |
| Projects_Completed | Number of projects completed |
| Placement | Placement outcome (Target Variable) |

---

## Objectives

- Analyze factors affecting student placement outcomes.
- Prepare and transform data for machine learning.
- Compare the performance of multiple classification models.
- Identify the most effective model for placement prediction.
- Evaluate prediction accuracy using standard classification metrics.

---

## Data Preprocessing

- Missing value analysis
- Statistical summary generation
- Label encoding of target variable
- One-hot encoding of categorical features
- Feature scaling using StandardScaler
- Train-test split for model evaluation

---

## Machine Learning Models

### Logistic Regression
A linear classification model used as a baseline for placement prediction.

### Decision Tree Classifier
A tree-based model capable of capturing non-linear decision boundaries.

### Random Forest Classifier
An ensemble learning model that combines multiple decision trees to improve prediction performance and reduce overfitting.

---

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## Workflow

1. Load and inspect the dataset.
2. Check for missing values and data consistency.
3. Generate statistical summaries of features.
4. Encode categorical variables.
5. Scale numerical features.
6. Split the dataset into training and testing sets.
7. Train Logistic Regression, Decision Tree, and Random Forest models.
8. Evaluate model performance using classification accuracy.
9. Compare results and identify the best-performing model.

---

## Key Insights

- Academic performance and CGPA strongly influence placement outcomes.
- Internship experience improves placement probability.
- Communication skills and project experience contribute to employability.
- Proper preprocessing improves model effectiveness.
- Ensemble models such as Random Forest can capture complex feature relationships.

---

## Future Enhancements

- Hyperparameter tuning for improved performance.
- Cross-validation based model evaluation.
- Feature importance analysis.
- Additional classification metrics such as Precision, Recall, and F1-Score.
- Deployment as a web-based placement prediction application.
