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
| **Statistical Tests** | Wilcoxon Signed-Rank Test and Ordered Logistic Regression(OLR). |
| **Key Finding (Q7)** | Data for Question 7 (time spent searching for content) was unreliable due to questionnaire flaws and was excluded from statistical analysis. |

---

### 📊 Key Findings

| Test / Variable | Result | P-value | Conclusion |
| :--- | :--- | :--- | :--- |
| **Q4 Wilcoxon Test** (Lecture Sufficiency) | Median ≠ 3 | ~0.00978 | **Reject H₀**: Ratings are significantly different from "Average". |
| **Q7 Wilcoxon Test** (Existing Resources) | Median = 3 | 0.7205 | **Fail to Reject H₀**: Median is statistically "Moderately Sufficient". |
| **Q4 in OLR** (Lecture Sufficiency) | Inverse Relationship | 0.0003 | **Significant** (Lower lecture sufficiency leads to Higher demand for platform). |
| **Q7 in OLR** (Resource Sufficiency) | Inverse Relationship | 0.0003 | **Significant** (Lower resource sufficiency leads to Higher demand for platform). |

---

## ✅ Conclusion and Recommendation

It is clear from the model that there is a significant relationship between the need for a structured online platform ($\text{Q8}$), the sufficiency of lectures ($\text{Q4}$), and the sufficiency of existing digital contents ($\text{Q7}$).

**Recommendation:** The company (Edu Era) should proceed with the platform launch, focusing on students of universities/colleges/regions where the lecture quality is low or insufficient to cover the syllabus. For that purpose, the company may consider carrying out a survey in a few specific university/colleges/regions.
