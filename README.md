

---

```markdown
# 🎓 Predicting Graduation and Dropout Rates

A Data Engineering and Machine Learning project aimed at predicting student graduation and dropout rates using data-driven techniques such as **Support Vector Machines (SVM)** and **Gaussian Naive Bayes (GNB)**.

---

## 🧠 Overview

Student dropout is a major issue affecting both individuals and institutions — leading to financial, academic, and societal impacts.  
This project builds a predictive model to identify **students at risk of dropping out** early in their academic journey, allowing educational institutions to implement targeted interventions and improve graduation rates.

Our model leverages **machine learning**, **data preprocessing**, and **statistical modeling** to analyze various demographic, academic, and socio-economic factors influencing student success.



---

## 📊 Objective

The main objective of this project is to:
- Identify students who are at risk of dropping out.
- Analyze academic, demographic, and financial data to find significant predictors.
- Build and evaluate predictive models using **Support Vector Machines** and **Gaussian Naive Bayes**.
- Provide actionable insights for academic administrators and policymakers.

---

## ⚙️ Methodology

### 1. **Data Preprocessing & Cleaning**
- Handled missing data using imputation (mean, median, mode).
- Removed or capped outliers.
- Normalized numerical attributes for uniform scale.

### 2. **Feature Selection**
Selected relevant features including:
- Marital Status  
- Application Mode  
- Previous Qualification  
- Admission Grade  
- Scholarship Holder  
- Age at Enrollment  
- Gender  

### 3. **Label Encoding**
Categorical variables were encoded into numeric form using `LabelEncoder`.

### 4. **Handling Class Imbalance**
Used **SMOTE (Synthetic Minority Oversampling Technique)** to balance the dataset and prevent model bias.

### 5. **Model Implementation**
Two machine learning algorithms were used:
- **Support Vector Machine (SVM):** Finds the optimal hyperplane that separates classes.
- **Gaussian Naive Bayes (GNB):** Uses probabilistic Gaussian distributions for classification.

### 6. **Model Evaluation**
Performance was assessed using:
- Accuracy
- Precision
- Recall
- F1-Score
- Classification Report

---

## 🧾 Results

| Model | Training Accuracy | Testing Accuracy |
|--------|------------------|------------------|
| **SVM** | 78.18% | 75.14% |
| **Gaussian Naive Bayes** | – | 71% overall accuracy |

**Naive Bayes Classification Summary:**
| Class | Precision | Recall | F1-Score |
|--------|------------|--------|----------|
| Dropout | 0.81 | 0.69 | 0.75 |
| Enrolled | 0.37 | 0.26 | 0.21 |
| Graduate | 0.71 | 0.86 | 0.78 |

---

## 🔍 Insights
- **Academic performance** and **admission grades** strongly influence dropout likelihood.
- **Scholarship holders** tend to have higher persistence.
- **Age and marital status** may also impact dropout rates.
- The **SVM model** demonstrated higher predictive power compared to Naive Bayes.

---

## 🚀 Future Scope

1. **Use Ensemble Learning**  
   Apply advanced algorithms such as Random Forests, Gradient Boosting, or Neural Networks.

2. **Hyperparameter Optimization**  
   Implement Grid Search or Randomized Search for improved accuracy.

3. **Feature Engineering**  
   Explore advanced feature selection (e.g., Recursive Feature Elimination).

4. **External Data Sources**  
   Integrate socio-economic and regional data for better contextual modeling.

5. **Deployment**  
   Create a user-friendly interface for real-time dropout prediction.

6. **Longitudinal Study**  
   Validate model performance across multiple academic years and institutions.

---

## 📚 References

1. Aulck, L. *Predicting Student Dropout in Higher Education*, arXiv:1606.06364  
2. DelBonifro, F. et al. *Student Dropout Prediction*, LNCS (2020)  
3. Solis, M. et al. *Perspectives to Predict Dropout in University Students with Machine Learning*, IEEE IWOBI 2018  
4. Strecht, P. et al. *Comparative Study of Classification Algorithms for Student Performance Modeling*, EDM 2015  
5. Masci, C. et al. *Student and School Performance Across Countries: A Machine Learning Approach*, Eur. J. Oper. Res. 2018  
6. Kotsiantis, S. et al. *Preventing Student Dropout in Distance Learning Using ML Techniques*, 2003  

---

## 🧩 Tech Stack

- **Languages:** Python  
- **Libraries:** NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn  
- **Techniques:** Label Encoding, SMOTE, SVM, Gaussian Naive Bayes  
- **Tools:** Jupyter Notebook / VS Code / Google Colab

---

## 📁 Repository Structure

```

Predicting-Graduation-and-Dropout-Rates/
│
├── data/                    # Dataset files (if available)
├── notebooks/               # Jupyter notebooks for analysis
├── models/                  # Saved model files (optional)
├── visuals/                 # Plots and result images
├── scripts/                 # Preprocessing and training scripts
├── README.md                # This file
└── report/                  # IEEE-style project report (PDF)

```

---

## 🏫 Acknowledgments

This project was developed as part of the **Data Engineering Concepts** course at  
**Dr. Vishwanath Karad MIT World Peace University, Pune.**

I thank our faculty mentors and peers for their valuable guidance and support.

---

## 🏷️ Keywords
`Machine Learning`, `Student Dropout`, `Education Analytics`, `SVM`, `Naive Bayes`, `Classification`, `Predictive Modeling`

---
```

---
