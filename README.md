# 🎓 Student Score Prediction

A machine learning project that predicts students' exam scores based on study habits and lifestyle factors using Linear and Polynomial Regression.

---

## 📋 Overview

This project explores how various student attributes — from study hours and attendance to sleep and parental involvement — correlate with and predict final exam performance. It was built as part of a data science course assignment covering regression modeling and evaluation metrics.

---

## 📂 Project Structure

```
├── student_score_prediction.ipynb   # Main notebook
├── StudentPerformanceFactors.csv    # Dataset (~6,600 records)
└── README.md
```

---

## 📊 Dataset

**Source:** [Student Performance Factors — Kaggle](https://www.kaggle.com/)

| Property | Value |
|---|---|
| Records | ~6,607 students |
| Target variable | `Exam_Score` |
| Features | 19 (numeric + categorical) |

**Key features include:**
- `Hours_Studied`, `Attendance`, `Sleep_Hours`, `Previous_Scores`
- `Parental_Involvement`, `Access_to_Resources`, `Motivation_Level`
- `Tutoring_Sessions`, `Family_Income`, `Teacher_Quality`
- `School_Type`, `Peer_Influence`, `Learning_Disabilities`, and more

---

## 🔧 Workflow

1. **Data Cleaning** — drop duplicates and null values
2. **Exploratory Analysis** — summary statistics + correlation heatmap
3. **Visualization** — scatter plot of study hours vs. exam score
4. **Train/Test Split** — 80/20 split with `random_state=42`
5. **Linear Regression** — baseline model, evaluated with MSE and R²
6. **Visualization** — actual vs. predicted scores + residuals plot
7. **Polynomial Regression (degree=2)** — bonus model for comparison

---

## 📈 Models & Evaluation

| Model | Metric |
|---|---|
| Linear Regression | MSE, R² Score |
| Polynomial Regression (degree 2) | MSE, R² Score |

Both models are compared at the end of the notebook to determine which generalizes better on the test set.

---

## 🛠️ Tech Stack

- **Python 3**
- **Pandas** — data loading and cleaning
- **NumPy** — numerical operations
- **Matplotlib / Seaborn** — visualizations
- **Scikit-learn** — model training and evaluation

---

## 🚀 Getting Started

```bash
# 1. Clone the repo
git clone https://github.com/your-username/student-score-prediction.git
cd student-score-prediction

# 2. Install dependencies
pip install pandas numpy matplotlib seaborn scikit-learn

# 3. Launch the notebook
jupyter notebook student_score_prediction.ipynb
```

Make sure `StudentPerformanceFactors.csv` is in the same directory as the notebook before running.

---

## 📌 Topics Covered

- Regression (Linear & Polynomial)
- Feature selection and data preprocessing
- Model evaluation metrics (MSE, R²)
- Data visualization and residual analysis
