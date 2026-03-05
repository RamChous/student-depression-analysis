# Student Depression and Lifestyle Analysis

## Project description
This project is a portfolio data analysis project exploring the relationship between student lifestyle and the likelihood of depression.

The analysis is based on the Student Depression and Lifestyle dataset, which contains information on factors such as sleep, academic workload, social media use, physical activity, stress levels, and academic performance.

The goal of the project is to demonstrate skills in exploratory data analysis (EDA), statistical analysis, and regression modeling.

---

## Project objectives
- Demonstrate data analysis (EDA) skills.
- Investigate student lifestyle factors.
- Find statistical relationships between variables.
- Test statistical hypotheses.
- Build linear regression models.
- Draw analytical conclusions based on data.

---

## Data Description
The dataset contains information on 100,000 students and includes the following data categories:

Primary Variables:
- **CGPA** — student grade point average
- **Study_Hours** — number of hours of study per day
- **Sleep_Hours** — number of hours of sleep
- **Social_Media_Hours** — time spent on social media
- **Physical_Activity** — physical activity
- **Stress_Level** — stress level
- **Department** — faculty
- **Depression** — presence of depression (0/1)

---

## Tools and Libraries Used
- Python
- Jupyter Notebook
Main Libraries:
- **Pandas** — Data Processing
- **NumPy** — Numerical Computing
- **Matplotlib** — Visualization
- **Seaborn** — Statistical Visualization
- **Scipy** — Statistical Tests
- **Scikit-learn** — Regression Modeling

---

## Main Analysis Steps
1. Data Preparation
- Dataset Loading
- Data Structure Overview
- Variable Type Checking
- Missing Value Analysis
- Duplicate Checking
2. Data Cleaning and Transformation
- Renaming Variables
- Creating New Features
- Data Type Conversion
3. Exploratory Data Analysis (EDA)
- Analysis of Variable Distributions
- Visualization of Key Data Characteristics
- Analysis of Relationships between Variables
4. Statistical Hypothesis Testing
The following tests were performed:
- One-sample t-test
- Two-sample t-test
- Paired t-test
- Correlation Analysis (Pearson / Spearman)
- One-way ANOVA
5. Regression Analysis
Models built:
- Simple Linear Regression
- Multiple Linear Regression

---

## Limitations of the Analysis
- This dataset is synthetic and may not fully reflect the real situation.
- Some variables may have a simplified structure.
- Correlation between variables does not necessarily imply causation.

---

## Key Findings
- Stress levels are one of the strongest factors associated with depression.
- CGPA shows a negative association with depression.
- Some lifestyle factors (sleep, study, social media) may influence stress levels and academic performance.
- Regression analysis allows us to assess the impact of various factors on academic performance and stress.

---

## How to run the project
1. Clone the repository
```bash
git clone https://github.com/yourusername/student-depression-analysis
```
2. Go to the project folder
```bash
cd student-depression-analysis
```
3. Run Jupyter Notebook
```bash
jupyter notebook
```
4. Open the file
```bash
notebook.ipynb
```
