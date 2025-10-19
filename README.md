# Understanding the Demand for a Structured Learning Platform (Edu Era)

[cite_start]This project investigates the market demand for a structured, high-quality digital learning platform (Edu Era) among university students whose academic needs are often unmet by traditional lectures and scattered online resources[cite: 29, 27].

---

## [cite_start]🎯 Project Objectives [cite: 31]

1.  [cite_start]To find out the sufficiency of class lectures in terms of covering the syllabus[cite: 32].
2.  [cite_start]To find out whether students frequently use digital content to supplement class learning[cite: 33, 34].
3.  [cite_start]To find out the sufficiency of existing online resources[cite: 35].
4.  [cite_start]To find out whether there is a need for a structured online platform[cite: 36].

## 🧪 Methodology and Data

| Aspect | Details |
| :--- | :--- |
| **Sampling Method** | [cite_start]Convenience sampling using a Google Form distributed via university WhatsApp groups[cite: 15]. |
| **Sample Size** | [cite_start]58 students[cite: 16]. |
| **Variables** | [cite_start]8 variables, including open-ended and closed-ended questions[cite: 16]. |
| **Scales Used** | [cite_start]Likert scale (1-5) for questions 4, 6, and 8; binary (Yes/No or 1/0) for question 5[cite: 17, 18]. |
| **Analysis Tools** | [cite_start]Python (Pandas, Seaborn, Matplotlib) within Jupyter Notebook, with limited use of Excel[cite: 20, 21]. |
| **Statistical Tests** | [cite_start]Wilcoxon Signed-Rank Test and Ordered Logistic Regression[cite: 66, 212]. |
| **Key Finding (Q7)** | [cite_start]Data for Question 7 (time spent searching for content) was unreliable due to questionnaire flaws and was excluded from statistical analysis[cite: 22, 231]. |

## 📊 Key Findings

* **Lecture Sufficiency (Q4):** We rejected the null hypothesis that the median effectiveness of class lectures is average (3). [cite_start]The p-value (~0.00978) was less than 0.05, and the distribution showed a slight left-skewness, suggesting a minority of students rate lectures as poor/very poor[cite: 91, 92, 110].
* [cite_start]**Existing Resource Sufficiency (Q7 in the Report, Q3 in Research Questions):** We failed to reject the null hypothesis that the median sufficiency of existing free online resources is 3 (moderately sufficient)[cite: 182, 166]. [cite_start]The p-value was high (0.7205)[cite: 152].
* **Need for a Structured Platform (Ordered Logistic Regression):**
    * [cite_start]There is a **significant inverse relationship** between the need for a structured platform ($\text{Q8}$) and the sufficiency of class lectures ($\text{Q4}$) ($p=0.0003$)[cite: 214, 215].
    * [cite_start]There is a **significant inverse relationship** between the need for a structured platform ($\text{Q8}$) and the sufficiency of existing online digital content ($\text{Q7}$) ($p=0.0003$)[cite: 217, 218].

## [cite_start]✅ Conclusion and Recommendation [cite: 227]

[cite_start]It is clear from the model that a significant relationship exists between the need for a structured platform ($\text{Q8}$) and the lack of sufficiency in both lectures ($\text{Q4}$) and existing digital content ($\text{Q7}$)[cite: 227].

[cite_start]**Recommendation:** The company (Edu Era) should proceed with the platform launch, focusing on universities/colleges where lecture quality is low or insufficient to cover the syllabus[cite: 228, 194].

---

## 📂 Repository Structure

* `report/`: Contains the full project report (`BR_Project_Report_pdf11_.pdf`).
* `data/`: Contains the raw survey data (to be uploaded as `survey_data.csv`).
* `analysis/`: Contains the Jupyter Notebook (`demand_analysis.ipynb`) with all the Python code for data processing, visualization, and statistical modeling.
