# Pandas 101 Exercises

This repository contains my solutions to a curated subset of the **101 Pandas Exercises** from MachineLearningPlus.

The purpose of this project is not to complete every exercise mechanically, but to work through the most useful pandas questions for my current level. The selected exercises are intended to build practical confidence with pandas fundamentals, Series and DataFrame operations, indexing, filtering, grouping, missing data handling, feature engineering, joining datasets, and basic data preparation for machine learning.

The exercises are completed in Jupyter Notebook format so that each solution can include code, outputs, explanations, and short reflections.

## Source

The exercises are based on the pandas practice exercises from:

- MachineLearningPlus — 101 Pandas Exercises for Data Analysis
- URL: https://machinelearningplus.com/python/101-pandas-exercises-python/

At the time of working through this repository, the published exercise list contains 75 questions and appears to be unfinished or “to be continued”.

This repository contains my own solutions, notes, and explanations.

## Learning Goals

The main goals of this project are to:

- Improve my practical pandas fluency.
- Become comfortable working with Series and DataFrames.
- Practise selecting, filtering, sorting, grouping, and transforming tabular data.
- Understand common data-cleaning patterns such as handling missing values and renaming/reordering columns.
- Practise importing data from CSV files and inspecting DataFrame structure.
- Build confidence with groupby, joins, dummy variables, date handling, and basic feature engineering.
- Strengthen my foundations for machine learning, data analysis, and real-world dataset preparation.
- Create a clear record of my progress through a focused pandas practice set.

## Selected Exercises

The main selected exercises are:

```text
1, 2, 3, 4, 5,
6, 7, 8, 9, 10,
11, 12, 13, 14, 15,
17,
20, 21, 22, 23,
26,
30, 31,
33, 34, 36, 37, 38, 39, 40, 41, 42, 43, 44, 45,
49, 50, 51, 52, 53, 54,
57, 58,
62, 64,
67, 68, 69, 70, 71, 72, 73, 74, 75
```

These exercises were chosen because they cover the most relevant pandas skills for my current stage of learning and for future machine learning work.

## Optional Exercises

The following exercises are optional extension tasks:

```text
16. Positions of items of Series A in Series B
18. Convert the first character of each element in a Series to uppercase
19. Calculate the number of characters in each word in a Series
24. Filter words that contain at least 2 vowels
25. Filter valid emails from a Series
27. Compute Euclidean distance between two Series
28. Find all local maxima or peaks in a numeric Series
32. Compute autocorrelations of a numeric Series
35. Create a DataFrame with rows as strides from a given Series
46. Set the number of rows and columns displayed in output
47. Format or suppress scientific notation in a DataFrame
48. Format all values in a DataFrame as percentages
56. Swap two rows of a DataFrame
59. Find which column contains the highest number of row-wise maximum values
60. Create a new column containing the nearest column by Euclidean distance
61. Find the maximum possible correlation value of each column against other columns
63. Create a column containing the penultimate value in each row
65. Compute the correlation of each row with the succeeding row
66. Replace both diagonals of a DataFrame with 0
```

These may be completed after the core set, depending on time and relevance.

## Later Exercises

The following exercises are more puzzle-like or lower priority for now and may be revisited later:

```text
29. Replace missing spaces in a string with the least frequent character
55. Reshape a DataFrame to the largest possible square after removing negative values
```

## Repository Structure

```text
pandas-101-exercises/
│
├── README.md
├── 101_pandas_exercises.ipynb
├── requirements.txt
└── .gitignore
```

## How to Run

Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/pandas-101-exercises.git
cd pandas-101-exercises
```

Create and activate a virtual environment:

```bash
python3 -m venv .venv
source .venv/bin/activate
```

Install the required packages:

```bash
pip install -r requirements.txt
```

Open the notebook:

```bash
jupyter notebook
```

Or open the folder in VS Code:

```bash
code .
```

## Progress Tracking

Progress will be tracked directly inside the notebook, with each exercise containing:

- The exercise number
- The problem statement
- My solution
- Output where relevant
- Short notes or explanation where useful

## Notes

This is a learning repository. The focus is on understanding practical pandas operations properly rather than simply producing the shortest possible answer.

Some solutions may be revisited and improved as my understanding develops. The aim is to build usable pandas fluency for data analysis, machine learning preparation, and real-world tabular data workflows.