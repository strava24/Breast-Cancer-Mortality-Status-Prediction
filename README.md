# Breast Cancer Mortality & Survival Prediction

## 📌 Overview

This project focuses on developing **machine learning models** for early screening of **breast cancer mortality status** and **survival prediction**. The goal is to provide doctors with a predictive tool that supports **treatment planning** and **patient management**.

Breast cancer is one of the leading causes of cancer-related deaths in women, with thousands of cases reported annually. Accurate prediction of mortality and survival time can significantly assist in **personalized treatment decisions** and **improving patient care**.

---

## 🎯 Problem Statement

Doctors often need to estimate whether a breast cancer patient is likely to survive and, if not, predict the survival period. Traditional approaches rely on limited datasets or focus on a single cancer type. This project explores whether **machine learning** can provide reliable predictions for:

1. **Mortality Status** – Predict whether a patient will survive breast cancer or not.
2. **Survival Period** – Estimate how long (in months) a patient is likely to survive if they do not survive.

---

## 📂 Dataset

The dataset is obtained from the **SEER Program (November 2017 update)**, containing historical records of breast cancer patients.

**Key Attributes:**

- `Patient ID` – Unique patient identifier
- `Age` – Patient’s age in years
- `Sex` – Patient’s genomic sex
- `Occupation` – Job field
- `T Stage` – Tumor size (T1–T4)
- `N Stage` – Lymph node involvement (N1–N3)
- `6th Stage` – BI-RADS classification
- `Differentiated` – Comparison of cancer cells vs normal cells
- `Grade` – Nottingham Grading System grade
- `A Stage` – Spread (Regional / Distant)
- `Tumor Size` – Tumor size in millimeters
- `Estrogen Status` – Estrogen receptor status (positive/negative)
- `Progesterone Status` – Progesterone receptor status (positive/negative)
- `Regional Node Examined` – Number of lymph nodes examined
- `Regional Node Positive` – Number of cancer-positive lymph nodes
- `Survival Months` – Months survived after diagnosis
- `Mortality Status` – Alive/Deceased (at study cut-off)

🔗 Further dataset details: [SEER Breast Cancer Data](https://ieee-dataport.org/open-access/seer-breast-cancer-data)

---

## 🔬 Methodology

This project follows the **CRISP-DM** (Cross Industry Standard Process for Data Mining) methodology, adapted to exclude deployment:

1. **Business Understanding** – Define the research problem with doctors.
2. **Data Understanding** – Explore and analyze patient data (mortality & survival).
3. **Data Preparation** – Clean, encode categorical variables, handle missing values, and normalize data.
4. **Modeling** – Train ML models for classification (mortality prediction) and regression (survival period prediction).
5. **Evaluation** – Assess models with appropriate metrics to ensure reliability and usefulness for medical practice.

---

## 🤖 Machine Learning Tasks

1. **Classification Task**

   - Predict whether a patient survives breast cancer.
   - Target variable: `Mortality Status`.
   - Models tested: Logistic Regression, K-Nearest Neigbours , Naive Bayes, Enseimble Model.

2. **Regression Task**
   - Predict the **survival period (in months)** for patients who do not survive.
   - Target variable: `Survival Months`.
   - Models tested: Decission Tree.

---

## 📊 Research Questions

- **Q1:** Can machine learning reliably predict which breast cancer patients are likely to survive?
- **Q2:** For patients who do not survive, can machine learning provide an accurate estimate of their survival period?

---

## 💡 Expected Impact

- Helps doctors **plan treatments more effectively**.
- Provides an **early screening tool** for mortality and survival risk.
- Encourages **data-driven decision-making** in oncology.

---

## 🛠️ Technologies Used

- Python (Pandas, NumPy, Scikit-learn)
- Jupyter Notebook / Google Colab
- Plotly

---

## 📑 Deliverables

- **Predictive models** for mortality and survival.
- **Evaluation report** with model performance metrics.
- **Python Notebook (.ipynb)** with full implementation.

---

## 👨‍⚕️ Audience

This project is designed for **doctors, medical researchers, and data scientists** interested in the application of machine learning in **oncology and survival analysis**.

🔗 For more in detail explanation on the implementation please refer to : [documentation](documentation.pdf)
