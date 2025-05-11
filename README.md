
# 🎓 Graduate University Admissions
## By Mita Crane, Safina Davis, Sneha Khatuwala, Mackenzie Steinbiss

This project contains a summary of the Final Project for DS 201. For more in-depth insight, please check out our walkthrough video or run our notebook directly in Google Colab (linked below).

---

## 📋 Table of Contents

1. [Business Understanding](#business-understanding)
2. [Data Understanding](#data-understanding)
3. [Data Preparation](#data-preparation)
4. [Visualizations](#visualizations)
5. [Conclusions & Future Directions](#conclusions--future-directions)
6. [Resources](#resources)

---

## 💼 Business Understanding

### Business Objectives
To understand and predict factors influencing a student’s chance of admission to a university using metrics like GPA, GRE, TOEFL, etc.

### Data Science Goals
- Perform EDA
- Build predictive models
- Evaluate using RMSE, R², etc.

---

## 📊 Data Understanding

| Variable | Description | Data Type |
|----------|-------------|-----------|
| GRE Scores | GRE exam score out of 340 | Ratio |
| TOEFL Scores | TOEFL exam score out of 120 | Ratio |
| University Rating | Rating out of 5 | Ordinal |
| Statement of Purpose | SOP Strength out of 5 | Ordinal |
| Letter of Recommendation | LOR Strength out of 5 | Ordinal |
| Undergraduate GPA | GPA out of 10 | Ratio |
| Research Experience | 0 = No, 1 = Yes | Nominal |
| Chance of Admit | Admission probability (0 to 1) | Ratio |

---

## 🧹 Data Preparation

| Step | Description |
|------|-------------|
| Null Values | Checked – No missing values were found |
| Type Conversion | All columns are correctly typed (numerical/ordinal) |
| Scaling | Features like GRE, TOEFL, CGPA normalized |
| Encoding | Research converted to 0/1 binary |
| Outlier Detection | Outliers were identified and analyzed |
| Data Split | 80% training and 20% testing set created |

---

## 📈 Visualizations

- GRE vs TOEFL scatterplot by university rating
- Correlation heatmap
- University rating countplot
- Research experience countplot
- CGPA histogram and CGPA vs Chance of Admit scatterplot

---

## ✅ Conclusions & Future Directions

Key findings:
- Higher CGPA and GRE → Higher admission chance
- Research experience positively impacts outcome

**Future Work:**
- Add non-academic features like essays
- Use NLP for recommendations
- Test for fairness/bias
- Use longitudinal performance data

---

## 🔗 Resources

- [Google Colab](https://colab.research.google.com/drive/1MVTng6DKpBt4lx7TXojKAautEbRBaRaz#scrollTo=jpX5BQm1ZEm6)
- [YouTube Presentation](https://youtu.be/YourVideoID)
- [GitHub Pages (IO Page)](https://sneha756.github.io/University-admissions/#content)
