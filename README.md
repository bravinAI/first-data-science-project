# Student Performance Data Analysis

This project explores student performance in Mathematics using the Student
Performance dataset from the
[UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/320/student+performance).
The analysis is documented in a Jupyter notebook and focuses on grade
distributions, study time, school absences, and the relationship between
earlier grades and final grades.

## Project files

- `student_performance_data_analysis.ipynb` — the complete analysis, including
  code, visualizations, findings, and conclusion.
- `student-mat.csv` — the Mathematics dataset used by the notebook. This data
  file is excluded from Git; download it from the UCI dataset page and place it
  in the project root before running the notebook.

The dataset is provided under the
[Creative Commons Attribution 4.0 International (CC BY 4.0) license](https://creativecommons.org/licenses/by/4.0/).

## Run the notebook

Requirements: Python 3.10 or later, Jupyter Notebook (or VS Code with the
Jupyter extension), and `pandas`, `numpy`, and `matplotlib`.

Install the required packages:

```bash
pip install pandas numpy matplotlib
```

Download the Mathematics data file named `student-mat.csv` from the UCI
dataset page, save it next to the notebook, then open and run
`student_performance_data_analysis.ipynb`.

## Analysis overview

The notebook explores dataset structure and missing values, summarizes and
plots final Mathematics grades, compares average grades across study-time
groups, examines absences, and calculates correlations between grades from
earlier periods and final performance. The findings are descriptive and do
not establish cause and effect or predictive accuracy on unseen students.
