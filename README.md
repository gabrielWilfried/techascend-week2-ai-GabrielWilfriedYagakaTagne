# TechAscend Cohort 2 – Week 2

**Name:** YAGAKA TAGNE GABRIEL WILFRIED
**Track:** AI
**Slack Username:** @Gabriel

---

## Dataset Used

**StudentPerformanceFactors.csv** — a real-world dataset of **6,607 students** across **20 features** covering academic, behavioural, and socioeconomic factors.

| Column | Type | Description |
|--------|------|-------------|
| `Exam_Score` | Numeric | Final exam score (target variable) |
| `Hours_Studied` | Numeric | Weekly study hours |
| `Attendance` | Numeric | Attendance percentage |
| `Sleep_Hours` | Numeric | Average nightly sleep |
| `Previous_Scores` | Numeric | Scores from prior exams |
| `Tutoring_Sessions` | Numeric | Number of tutoring sessions attended |
| `Parental_Involvement` | Categorical | Low / Medium / High |
| `Motivation_Level` | Categorical | Low / Medium / High |
| `Teacher_Quality` | Categorical | Low / Medium / High |
| `School_Type` | Categorical | Public / Private |
| + 10 more columns | Mixed | Gender, Income, Internet Access, etc. |

---

## Analysis Performed

* Loaded the dataset with `pandas` and inspected shape, data types, and null values
* Printed the first 5 rows and full `.describe()` statistics
* Calculated average, max, min, median, and standard deviation for `Exam_Score`


---

## Key Insights

| Metric | Value |
|--------|-------|
| Average Exam Score | ~67.2 |
| Highest Score | 101 |
| Lowest Score | 55 |

---

## Challenges Faced

* **N/A:** Things work smoothly.

---

## How to Run

```bash
# 1. Install dependencies
pip install pandas matplotlib jupyter

# 2. Launch Jupyter
jupyter notebook week2.ipynb
```

> Requires Python 3.10+ · Dependencies: `pandas`, `matplotlib` · Dataset: `StudentPerformanceFactors.csv`