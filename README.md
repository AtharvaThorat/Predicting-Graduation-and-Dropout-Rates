

# 🎓 Predicting Graduation and Dropout Rates

**A data-driven journey to understand why students drop out — and how we can predict it before it happens.**

---

## 🧠 Overview

Every year, thousands of students step into universities full of dreams — but not all of them make it to graduation.
Some lose motivation, some face personal struggles, and others simply slip through unnoticed.

This project, **Predicting Graduation and Dropout Rates**, was born from the question:

> “Can data help us recognize who’s at risk — before it’s too late?”

By harnessing the power of **machine learning** and **data engineering**, we built a model that predicts whether a student will graduate, stay enrolled, or drop out — based on their academic, demographic, and socio-economic background.

Our goal isn’t just to predict outcomes — it’s to help educational institutions take action early, to **change those outcomes.**

---

## 🎯 Objective

The core objectives of this project were to:

* Detect students who are likely to **drop out** early in their academic journey.
* Identify **key predictors** of academic success or failure.
* Build and compare predictive models using **Support Vector Machines (SVM)** and **Gaussian Naive Bayes (GNB)**.
* Provide actionable insights for administrators, educators, and policymakers to improve graduation rates.

---

## ⚙️ Methodology

Our journey began with raw data — incomplete, messy, and full of hidden stories.
Step by step, we cleaned, processed, and refined it into meaningful insights.

### 1️⃣ Data Preprocessing & Cleaning

* Missing data? We handled it through imputation (mean, median, mode).
* Outliers? Detected and corrected.
* Feature scales? Normalized for consistency.

### 2️⃣ Feature Selection

We focused on variables that truly influence academic continuity:

* Marital Status
* Application Mode
* Previous Qualification
* Admission Grade
* Scholarship Holder
* Age at Enrollment
* Gender

### 3️⃣ Label Encoding

Categorical variables were numerically encoded using **LabelEncoder**, ensuring our models could interpret every detail.

### 4️⃣ Handling Class Imbalance

Because dropout data was limited, we used **SMOTE (Synthetic Minority Oversampling Technique)** — generating synthetic samples to balance our dataset and prevent bias.

### 5️⃣ Model Building

We explored two distinct algorithms:

* **Support Vector Machines (SVM)** – Finds the perfect hyperplane to separate classes, excelling in high-dimensional data.
* **Gaussian Naive Bayes (GNB)** – A fast, probabilistic classifier based on Bayes’ theorem and Gaussian distributions.

### 6️⃣ Model Evaluation

To measure how well our models understood the data, we used:

* **Accuracy**
* **Precision**
* **Recall**
* **F1-Score**
* **Classification Report**

---

## 📈 Results

| Model                    | Training Accuracy | Testing Accuracy     |
| ------------------------ | ----------------- | -------------------- |
| **SVM**                  | 78.18%            | 75.14%               |
| **Gaussian Naive Bayes** | –                 | 71% overall accuracy |

### 📊 Naive Bayes Classification Summary

| Class    | Precision | Recall | F1-Score |
| -------- | --------- | ------ | -------- |
| Dropout  | 0.81      | 0.69   | 0.75     |
| Enrolled | 0.37      | 0.26   | 0.21     |
| Graduate | 0.71      | 0.86   | 0.78     |

🧩 **Insight:**
The **SVM model** consistently outperformed Naive Bayes — showing higher precision and recall, especially for predicting graduates and dropouts.

---

## 💡 Key Insights

* **Academic performance** and **admission grades** are the strongest predictors of success.
* **Scholarship holders** are significantly more likely to complete their programs.
* **Age and marital status** play subtle yet measurable roles.
* **SVM** proved to be the most effective model for our dataset.

Our analysis doesn’t just reveal who might drop out — it reveals *why*.

---

## 🚀 Future Scope

This project is just the beginning. Future directions include:

1. **Ensemble Models:** Exploring Random Forests, Gradient Boosting, and Neural Networks for improved accuracy.
2. **Hyperparameter Tuning:** Using Grid Search and Randomized Search for optimization.
3. **Feature Engineering:** Applying advanced selection methods like Recursive Feature Elimination.
4. **External Data Integration:** Adding socio-economic and geographic data to improve predictions.
5. **Deployment:** Building an interactive web dashboard for real-time dropout prediction.
6. **Long-Term Validation:** Testing across multiple institutions and semesters for generalization.

---

## 🧩 Tech Stack

* **Languages:** Python
* **Libraries:** NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn
* **Techniques:** Label Encoding, SMOTE, SVM, Gaussian Naive Bayes
* **Tools:** Jupyter Notebook, VS Code, Google Colab

---

## 📁 Repository Structure

```
Predicting-Graduation-and-Dropout-Rates/
│
├── data/                    # Dataset files (if available)
├── notebooks/               # Jupyter notebooks for analysis
├── models/                  # Trained ML models
├── visuals/                 # Graphs and visual outputs
├── scripts/                 # Preprocessing and training scripts
├── report/                  # IEEE-format project report (PDF)
└── README.md                # Project documentation
```

---

## 🏫 Acknowledgments

This project was developed as part of the **Data Engineering Concepts** course at
**Dr. Vishwanath Karad MIT World Peace University, Pune**.

A heartfelt thank you to our mentors and peers for their invaluable guidance, support, and feedback throughout the journey.

---

## 📚 References

1. Aulck, L. *Predicting Student Dropout in Higher Education*, arXiv:1606.06364
2. DelBonifro, F. et al. *Student Dropout Prediction*, LNCS (2020)
3. Solis, M. et al. *Perspectives to Predict Dropout in University Students with Machine Learning*, IEEE IWOBI 2018
4. Strecht, P. et al. *Comparative Study of Classification Algorithms for Student Performance Modeling*, EDM 2015
5. Masci, C. et al. *Student and School Performance Across Countries: A Machine Learning Approach*, Eur. J. Oper. Res. 2018
6. Kotsiantis, S. et al. *Preventing Student Dropout in Distance Learning Using ML Techniques*, 2003

---

## 🏷️ Keywords

`Machine Learning` • `Student Dropout` • `Education Analytics` • `SVM` • `Naive Bayes` • `Classification` • `Predictive Modeling`

---

⭐ **“Data doesn’t just predict — it empowers.”**
This project aims to make education smarter, fairer, and more supportive for every student.

---

Would you like me to make this README even more *GitHub-polished* — e.g., with **badges (Python, Scikit-learn, MIT-WPU)**, and a **“How to Run”** section (setup commands and notebook instructions)?
That would make it look like a complete open-source project page.
