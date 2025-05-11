# Graduate University Admissions
## By Mita Crane, Safina Davis, Sneha Khatuwala, Mackenzie Steinbiss

This contains a summary of the Final Project for DS 201. For more in-depth in-sight, please check out our walkthrough video or run our notebook directly in Google Colab linked below.
---

## 📋 Table of Contents

1. [Business Understanding](#business-understanding) \
   a. [Business Objetives](#business-objectives) \
   b. [Data Science Goals](#data-science-goals) 
   c. [Project Plan](#project-plan) 
3. [Data Understanding](#data-understanding)  
4. [Data Preparation](#data-preparation)
5. [Visualizations](#visualizations)
6. [Modeling & Evaluation](#modeling--evaluation)  
7. [Conclusions & Future Directions](#conclusions--future)  
8. [Resources](#resources)

---

## Business Understanding

### Business objectives
The objective is to understand and predict the factors that influence a student’s chance of admission to a university. This insight can help universities optimize admissions strategies and applicants better understand how their profiles affect admission outcomes. Specifically:
  a. Identify which variables (e.g., SAT, GPA, GRE, TOEFL, University rating) have the strongest impact.
  b. Predict a student's likelihood of admission based on their profile.

1. Assess the situation
  a. Resources: The dataset includes key academic metrics and admission outcomes
  b. Constraints:
      a. Limited number of features (might not capture other important factors like extracurriculars, essays).
      b. Possible missing values or biases (e.g., dataset might be skewed towards particular types of students or universities).

2. Risks:
   a. Misinterpretation: Correlation does not imply causation.
   b. Overfitting if models are too complex relative to dataset size.

3. Assumptions: Data is accurate and representative of a general applicant pool.

### Data science goals
1. Perform exploratory data analysis (EDA) to identify patterns, distributions, and relationships.

2. Build predictive models to estimate the probability of admission based on available features.

3. Evaluate model performance using appropriate metrics (e.g., RMSE for regression, R² score).

### Project plan
1. Data Understanding -
  a. Summarize and visualize the dataset.
  b. Check for missing values, outliers, and data types.

2. Data Preparation -
  a. Handle missing values if any.
  b. Normalize or standardize features if necessary.
  c. Create training and test datasets.

3. Modeling -
   a. Train different models (linear regression, decision trees, etc.).
   b. Tune hyperparameters for better performance.

4. Evaluation -
  a. Assess models using appropriate evaluation metrics.
  b. Compare model results to choose the best-performing one.

5. Deployment/Reporting -
  a. Present findings and interpretations.
  b. Share actionable insights (e.g., improving GPA or TOEFL might most strongly impact admission chances).

---

## Data Understanding

1. When was the data acquired?
We do not know the specific date of when the data was acquired but it was uploaded to Kaggle in 2021.

2. Where was the data acquired?
The team that performed the analysis in this report accessed the data used in the report via Kaggle.com. However, based on the description and typical context, it appears to be based on or inspired by the famous "Graduate Admissions" dataset from the University of California, Irvine (UCI) Machine Learning Repository. That original dataset contains similar attributes (GRE, TOEFL, SOP, LOR, CGPA, Research, Chance of Admit) and is often used for machine learning projects.

3. How was the data acquired?
The data was sourced from Kaggle for this project but there is no information in Kaggle as to how the data was originally collected.
Some potential sources could be -
  a. Public university admission records: Some universities publish anonymized admission statistics (scores, GPAs, etc.) online.
  b. Surveys: The creator could have surveyed students who recently applied to graduate schools and self-reported their scores and admission chances.
  c. Simulated data: Sometimes datasets are artificially created based on typical ranges and patterns seen in real admissions.
  d. Research studies: Academic papers sometimes collect and share admissions-related datasets for analysis.

4. What are the attributes of the dataset?
The variables and their descriptions are as follows -
GRE Scores ( out of 340 )
TOEFL Scores ( out of 120 )
University Rating ( out of 5 )
Statement of Purpose (SOP) and Letter of Recommendation (LOR) Strength ( out of 5 )
Undergraduate GPA ( out of 10 )
Research Experience ( either 0 or 1 )
Chance of Admit ( ranging from 0 to 1 )  

| Variable | Description | Data Type |
| --- | --- | --- |
| GRE Scores | Scores on the GRE exam out of 340 | Ratio |
| TOEFL Scores	| Scores on the TOEFL exam out of 120	| Ratio |
| University Rating	| A rating of the university out of 5	| Ordinal | 
| Statement of purpose	| Strength of the statement of purpose out of 5	| Ordinal |
| Letter of recommendation	| Strength of the letter of recommendation out of 5	| Ordinal |
| Undergraduate GPA	| Undergraduate GPA out of 10 | Ratio |
| Research experience	| Research experience (0 = no, 1 = yes) | Nominal |
| Chance of admit	| Chance of getting an admission (ranging from 0 to 1) | Ratio |
---

## Modeling & Analysis

Summarize which algorithms or statistical tests you ran, hyperparameters, and how you evaluated performance.

---


## Data Preparation
None of our colunms had any null values so no changes to our dataset was made
| Variable | Description | Data Type | Null Values? |
| --- | --- | --- | --- |
| GRE Scores | Scores on the GRE exam out of 340 | Ratio | No | 
| TOEFL Scores	| Scores on the TOEFL exam out of 120	| Ratio | No | 
| University Rating	| A rating of the university out of 5	| Ordinal | No |  
| Statement of purpose	| Strength of the statement of purpose out of 5	| Ordinal | No | 
| Letter of recommendation	| Strength of the letter of recommendation out of 5	| Ordinal | No | 
| Undergraduate GPA	| Undergraduate GPA out of 10 | Ratio | No | 
| Research experience	| Research experience (0 = no, 1 = yes) | Nominal | No | 
| Chance of admit	| Chance of getting an admission (ranging from 0 to 1) | Ratio | No | 
---

## Visualizations

Here you embed your graphs. Be sure the filenames match what you saved in `/images`.

### Example: Pollution vs. Cost Scatterplot

![Pollution vs. Healthcare Cost](images/graph1.png)

### Example: Residuals Distribution

![Residuals Plot](images/graph2.png)

*(Add as many as you need; GitHub will render these inline.)*

---

## Conclusions & Next Steps

- **Key findings**  
- **Limitations**  
- **Future work**  

---

## Resources

- **View the notebook on Google Colab:**  
  [Open in Colab](https://colab.research.google.com/drive/YourNotebookID)

- **Watch the project walkthrough on YouTube:**  
  [YouTube Video](https://youtu.be/YourVideoID)

---

> _This README was generated on YYYY-MM-DD._
