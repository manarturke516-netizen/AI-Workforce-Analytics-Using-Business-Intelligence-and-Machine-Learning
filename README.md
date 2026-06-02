# AI Workforce Analytics Using Business Intelligence and Machine Learning

*Student: Manar Turke*  


---

# Project Overview

This project applies **Business Intelligence (BI), Data Analytics, Machine Learning, and Workforce Analytics** to analyze the impact of Artificial Intelligence on employees and organizations.

The study investigates how factors such as:

- Burnout
- Productivity
- Job Satisfaction
- AI Fear
- AI Adoption
- Salary
- Work Environment
- Employee Demographics

influence **Employee Attrition Risk** and workforce performance.

The project combines:

- Exploratory Data Analysis (EDA)
- Interactive Power BI Dashboards
- Predictive Machine Learning Models
- Employee Segmentation using Clustering

to support data-driven HR and organizational decision-making.

---

# Objectives

- Analyze workforce behavior and AI impact on employees.
- Predict employee attrition risk using machine learning.
- Identify key factors affecting employee satisfaction and burnout.
- Segment employees into meaningful workforce groups.
- Build interactive Power BI dashboards for workforce monitoring.

---

# Dataset

The dataset contains workforce and AI adoption information including:

- Employee Demographics
- Job Roles
- Industries
- Company Sizes
- AI Adoption Stages
- Burnout Scores
- Productivity Scores
- Job Satisfaction
- Salary
- Remote Work Types
- AI Replacement Concerns
- Attrition Risk

---

# Data Preprocessing

The following preprocessing steps were performed:

- Missing value validation
- Duplicate record checking
- Data type correction
- Outlier detection using Boxplots and Z-Score
- Feature selection
- Label Encoding for categorical variables
- Data normalization for clustering

### Data Cleaning Workflow

![Data Cleaning](images/Picture2.png)

![Data Transformation](images/Picture3.png)

![Feature Preparation](images/Picture4.png)

---

# Exploratory Data Analysis (EDA)

EDA was performed to understand employee behavior and workforce patterns.

## Descriptive Statistics

![Descriptive Statistics](images/Picture5.png)

Key findings:

- Average employee experience ≈ 10 years
- Average salary ≈ 140K USD
- Hybrid work is the most common work environment
- Medium AI fear is the most frequent category

---

## Numerical Feature Distributions

![Distributions](images/Picture6.png)

Analysis included:

- Salary
- Burnout
- Productivity
- Satisfaction
- AI Upskilling Hours
- Daily AI Usage

---

## Categorical Feature Distributions

![Categorical Distributions](images/Picture7.png)

Analysis included:

- Job Roles
- Countries
- Industries
- Company Sizes
- AI Adoption Stages
- Remote Work Types
- AI Fear Levels

---

## Correlation Analysis

![Heatmap](images/Picture8.png)

### Key Findings

- Burnout and Satisfaction: **-0.63**
- AI Replacement % and Burnout: **0.61**
- AI Replacement % and Satisfaction: **-0.40**
- AI Tool Usage and Productivity: **0.30**

These results indicate that employees who perceive greater AI replacement risk tend to experience higher burnout and lower satisfaction.

---

# Business Intelligence Dashboards

## Dashboard 1: Employee Attrition & AI Impact

![Dashboard 1](images/Picture22.png)

### Insights

- Employee burnout trends
- Productivity analysis
- AI fear impact
- Attrition risk monitoring
- Salary and satisfaction analysis
- Country-level workforce comparison

---

## Dashboard 2: AI Workforce Analytics

![Dashboard 2](images/Picture23.png)

### Insights

- AI fear across industries
- AI adoption maturity
- Burnout and productivity trends
- AI replacement perception
- Company size comparison
- Workforce wellbeing indicators

---

# Machine Learning Models

## Prediction Target

The target variable is:

**Attrition Risk**

Classes:

- Low
- Medium
- High

---

# Logistic Regression

Logistic Regression was used as a baseline classification model.

### Workflow

![Prediction Process](images/Picture.png)

### Results

![Logistic Regression Results](images/Picture24.png)

![ROC Curve](images/Picture26.png)

### Performance

| Metric | Value |
|----------|----------|
| Accuracy | 80% |
| AUC Score | 0.93 |
| Model Type | Linear Classification |

### Summary

The model successfully identified employee attrition patterns and provided interpretable insights regarding:

- Burnout
- Satisfaction
- Productivity
- Salary
- AI Fear

---

# Random Forest

Random Forest was implemented to capture more complex workforce relationships.

### Results

![Random Forest Results](images/Picture27.png)

![Random Forest Evaluation](images/Picture29.png)

### Performance

| Metric | Value |
|----------|----------|
| Accuracy | 87% |
| AUC Score | 0.97 |
| Model Type | Ensemble Classification |

### Summary

The Random Forest model achieved superior performance by capturing nonlinear relationships among workforce variables.

---

# Model Comparison

| Metric | Logistic Regression | Random Forest |
|----------|----------|----------|
| Accuracy | 80% | 87% |
| AUC Score | 0.93 | 0.97 |
| Performance | Good | Excellent |
| Complexity Handling | Moderate | High |
| Prediction Quality | Strong | Stronger |

### Best Model

✅ **Random Forest**

Reasons:

- Higher Accuracy
- Higher AUC
- Better classification performance
- Captures complex workforce behaviors
- Lower misclassification rate

---

# Employee Clustering

K-Means Clustering was used to identify workforce segments.

### Clustering Visualization

![Clustering](images/Picture28.png)

### PCA Cluster Visualization

![Cluster Visualization](images/Picture30.png)

---

## Cluster 0: High Productivity Balanced Employees

Characteristics:

- High productivity
- Good satisfaction
- High salary
- Moderate burnout
- Effective AI usage

### Business Action

- Retention programs
- Leadership development
- Performance rewards

---

## Cluster 1: High Burnout & High AI Fear Employees

Characteristics:

- Highest burnout
- Lowest satisfaction
- Highest AI replacement concern
- Lower productivity

### Business Action

- Burnout reduction initiatives
- AI communication programs
- Reskilling and support plans

---

## Cluster 2: Satisfied & Stable Employees

Characteristics:

- Highest satisfaction
- Lowest burnout
- Low AI fear
- Stable productivity

### Business Action

- Maintain current environment
- Encourage continuous development
- Retention and loyalty programs

---

# Technologies Used

### Business Intelligence

- Microsoft Power BI

### Data Analysis

- Python
- Pandas
- NumPy

### Machine Learning

- Scikit-Learn
- Logistic Regression
- Random Forest
- K-Means Clustering
- PCA

### Visualization

- Matplotlib
- Seaborn
- Power BI

### Development Environment

- Google Colab

---

# Business Value

This project provides answers to three key business questions:

### What is happening?

Answered through:

- Power BI Dashboards
- Workforce Analytics
- KPI Monitoring

### What is likely to happen?

Answered through:

- Logistic Regression
- Random Forest Predictions

### Who should management focus on?

Answered through:

- Employee Clustering
- Workforce Segmentation

---

# Key Results

### Predictive Analytics

- Logistic Regression Accuracy: **80%**
- Random Forest Accuracy: **87%**
- Best Model: **Random Forest**

### Workforce Insights

- Burnout strongly increases attrition risk.
- AI replacement fear negatively affects employee satisfaction.
- Job satisfaction reduces employee turnover risk.
- Productivity is associated with AI tool adoption.

### Clustering Insights

Three workforce groups were identified:

1. High Productivity Employees
2. High Burnout & High AI Fear Employees
3. Stable & Satisfied Employees

---

# Conclusion

The integration of Business Intelligence, Machine Learning, and Workforce Analytics successfully transformed workforce data into actionable organizational insights.

The project demonstrates how AI-driven analytics can help organizations:

- Improve employee retention
- Reduce burnout
- Support AI adoption
- Increase workforce productivity
- Enable data-driven HR decision-making

