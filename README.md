# Student Exam Score Prediction

A notebook experiment that explores student performance factors and compares Linear Regression with a degree-2 Polynomial Regression model for predicting `Exam_Score`.

## Project files

```text
.
├── student_score_prediction.ipynb
├── StudentPerformanceFactors.csv
└── README.md
```

## Workflow

The notebook loads the supplied CSV, checks missing values, explores summary statistics and correlations, creates a train/test split, and evaluates linear and polynomial regression with Mean Squared Error and R².

## Requirements and usage

Python and Jupyter are required. The notebook imports pandas, NumPy, Matplotlib, Seaborn, and scikit-learn.

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
jupyter notebook
```

Run Jupyter from the repository root, open `student_score_prediction.ipynb`, and execute the cells in order so the relative CSV path resolves.

## Limitations

The notebook is an educational analysis, not a validated student assessment tool. Dataset associations are not causal evidence, and predictions should not be used for consequential decisions about students.
