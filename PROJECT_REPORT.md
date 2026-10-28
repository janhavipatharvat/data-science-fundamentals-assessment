# Project Report: Data Science Fundamentals Assessment

**Intern name:** ______________________  **Date:** 28 October 2026
**GitHub repository:** ______________________ (paste your link here)

---

## 1. Introduction

This project demonstrates the foundational knowledge needed for data science. It is delivered as one reproducible Jupyter notebook that explains each concept and then applies it in code, finishing with four practical assignments.

## 2. Objectives

1. Understand data science fundamentals
2. Apply Python programming basics
3. Learn statistical foundations
4. Understand data types and structures
5. Follow data science best practices
6. Complete fundamentals assignments

## 3. Tools and Technologies

Python 3, Jupyter Notebook, NumPy, pandas, Matplotlib, and the Python standard library (`statistics`, `random`, `itertools`, `pathlib`).

## 4. Work Done, Task by Task

### Task 1: Data Science Fundamentals
- Described the eight-stage lifecycle: problem definition, collection, cleaning, EDA, modelling, evaluation, deployment, monitoring.
- Compared descriptive, diagnostic, predictive and prescriptive analysis, with examples.
- Listed use cases in healthcare, finance, retail, telecom, transport, agriculture and education.
- **Outcome:** a clear view of how data science turns raw data into decisions.

### Task 2: Python Programming Basics
- Covered variables, data types, operators, conditionals, loops (including `break` and `continue`), functions, lambdas and comprehensions.
- Used lists, tuples, dictionaries and sets, including set operations and unpacking.
- Wrote, appended to, and read a text file, with `FileNotFoundError` handling.
- **Outcome:** working fluency in the Python needed for data analysis.

### Task 3: Statistical Foundations
- Computed mean, median, mode, variance, standard deviation, range, quartiles, IQR and percentiles.
- Detected outliers with the 1.5 × IQR rule and showed that one outlier (95) pulls the mean far above the median.
- Calculated probability for two dice exactly, conditionally and by simulation, which showed the law of large numbers.
- Built a correlation matrix and scatter plots contrasting strong and no correlation.
- **Outcome:** can pick the right summary measure and avoid mistaking correlation for causation.

### Task 4: Data Types and Structures
- Built a DataFrame with numerical, nominal, ordinal, datetime and text columns.
- Converted each to its proper type, with ordered categoricals for ordinal data.
- Used one-hot encoding for nominal data, extracted month and weekday from dates, cleaned text and counted words.
- Filled missing ages with the median.
- **Outcome:** each data type was handled according to its properties.

### Task 5: Best Practices
- Contrasted poor and good function naming, with docstrings and type hints.
- Preserved raw data with `.copy()`, fixed random seeds and printed library versions for reproducibility.
- Wrote a responsible-interpretation checklist covering sample size, causation, outliers, chart honesty, privacy and uncertainty.
- **Outcome:** analysis that is readable, reproducible and honest about its limits.

### Task 6: Fundamentals Assignments
1. **Python programming:** FizzBuzz, palindrome check, word frequency, primes up to 50, and set operations.
2. **Statistics from scratch:** wrote mean, median, mode and variance functions, then checked them against NumPy with `assert`.
3. **Data manipulation:** on a 203-row synthetic sales dataset with injected duplicates and missing prices, removed duplicates, imputed prices by category median and added revenue and month columns. Then ran group-by aggregations, ranked the top orders and built a pivot table.
4. **Analysis and visualisation:** plotted monthly revenue, revenue by category and the revenue distribution, and reported skewness and correlation.

## 5. Key Findings

- Duplicates and missing values were fully resolved by the cleaning function, leaving no missing values.
- Revenue is right-skewed, so the median describes a typical order better than the mean.
- Quantity and revenue are positively correlated, as expected from revenue = quantity × price.

## 6. Challenges and Learnings

- Choosing between mean and median depends on skew and outliers.
- Imputation should be a deliberate, documented decision.
- Fixed seeds and a "Restart & Run All" check make results reproducible.

## 7. Limitations

The sales dataset is synthetic, so findings illustrate technique rather than real business conclusions.

## 8. Conclusion

The project covers all six objectives and shows a complete path from concepts to a cleaned, analysed dataset. Next steps are deeper visualisation, hypothesis testing and an introduction to machine learning with scikit-learn.

## 9. Repository Contents

`Data_Science_Fundamentals_Assessment.ipynb`, `README.md`, `PROJECT_REPORT.md`, `requirements.txt`
