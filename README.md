# Understanding the Demand for a Structured Learning Platform (Edu Era)

This project investigates the market demand for a structured, high-quality digital learning platform (Edu Era) among university students whose academic needs are often unmet by traditional lectures and scattered online resources.

---

## 🎯 Project Objectives

1.  To find out the sufficiency of class lectures in terms of covering the syllabus.
2.  To find out whether students frequently use digital content to supplement class learning.
3.  To find out the sufficiency of existing online resources.
4.  To find out whether there is a need for a structured online platform.

---

## 🧪 Methodology and Data

| Aspect | Details |
| :--- | :--- |
| **Sampling Method** | Convenience sampling using a Google Form distributed via university WhatsApp groups. |
| **Sample Size** | 58 students. |
| **Variables** | 8 variables, including open-ended and closed-ended questions. |
| **Scales Used** | Likert scale (1-5) for questions 4, 6, and 8; binary (Yes/No or 1/0) for question 5. |
| **Analysis Tools** | Python (Pandas, Seaborn, Matplotlib) within Jupyter Notebook, with limited use of Excel. |
| **Statistical Tests** | Wilcoxon Signed-Rank Test and Ordered Logistic Regression. |
| **Key Finding (Q7)** | Data for Question 7 (time spent searching for content) was unreliable due to questionnaire flaws and was excluded from statistical analysis. |

---

## 📊 Key Findings

* **Lecture Sufficiency (Q4):** We rejected the null hypothesis that the median effectiveness of class lectures is average (3). The p-value (~0.00978) was less than 0.05, and the distribution showed a slight left-skewness, suggesting a minority of students rate lectures as poor/very poor.
* **Existing Resource Sufficiency (Q7 in the Report, Q3 in Research Questions):** We failed to reject the null hypothesis that the median sufficiency of existing free online resources is 3 (moderately sufficient). The p-value was high (0.7205).
* **Need for a Structured Platform (Ordered Logistic Regression):**
    * There is a **significant inverse relationship** between the need for a structured platform ($\text{Q8}$) and the sufficiency of class lectures ($\text{Q4}$) ($p=0.0003$).
    * There is a **significant inverse relationship** between the need for a structured platform ($\text{Q8}$) and the sufficiency of existing online digital content ($\text{Q7}$) ($p=0.0003$).

---

## ✅ Conclusion and Recommendation

It is clear from the model that a significant relationship exists between the need for a structured platform ($\text{Q8}$) and the lack of sufficiency in both lectures ($\text{Q4}$) and existing digital content ($\text{Q7}$).

**Recommendation:** The company (Edu Era) should proceed with the platform launch, focusing on universities/colleges where lecture quality is low or insufficient to cover the syllabus.

---

## 📂 Repository Structure

* `report/`: Contains the full project report (`BR_Project_Report_pdf11_.pdf`).
* `data/`: Contains the raw survey data (to be uploaded as `survey_data.csv`).
* `analysis/`: Contains the Jupyter Notebook (`demand_analysis.ipynb`) with all the Python code for data processing, visualization, and statistical modeling.
