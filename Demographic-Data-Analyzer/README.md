# [Demographic Data Analyzer](https://www.freecodecamp.org/learn/data-analysis-with-python/data-analysis-with-python-projects/demographic-data-analyzer)

Welcome to the **Demographic Data Analyzer** project! This analysis focuses on extracting insights from demographic data using Pandas, offering answers to various questions related to the dataset.

## Overview

The dataset used in this project was extracted from the 1994 Census database, and it provides detailed information on age, work class, education, marital status, occupation, and more. This project answers several key demographic questions using Python and Pandas.

## Questions Answered

1. How many people of each race are represented in this dataset?
2. What is the average age of men?
3. What is the percentage of people who have a Bachelor's degree?
4. What percentage of people with advanced education (Bachelors, Masters, or Doctorate) make more than 50K?
5. What percentage of people without advanced education make more than 50K?
6. What is the minimum number of hours a person works per week?
7. What percentage of the people who work the minimum number of hours per week have a salary of more than 50K?
8. Which country has the highest percentage of people that earn >50K, and what is that percentage?
9. Identify the most popular occupation for those who earn >50K in India.

### Testing result
```bash
Number of each race:
 race
White                 27816
Black                  3124
Asian-Pac-Islander     1039
Amer-Indian-Eskimo      311
Other                   271
Name: count, dtype: int64
Average age of men: 39.4
Percentage with Bachelors degrees: 16.4%
Percentage with higher education that earn >50K: 46.5%
Percentage without higher education that earn >50K: 17.4%
Min work time: 1 hours/week
Percentage of rich among those who work fewest hours: 10.0%
Country with highest percentage of rich: Iran
Highest percentage of rich people in country: 41.9%
Top occupations in India: Prof-specialty
..........
----------------------------------------------------------------------
Ran 10 tests in 0.274s

OK
```

## Files in This Project

- **`demographic_data_analyzer.py`**: Core script for analyzing the data and answering the above questions.
- **`main.py`**: A simple script to run and test the `demographic_data_analyzer.py` calculations.
- **`test_module.py`**: Unit tests to ensure that the functions in `demographic_data_analyzer.py` work as expected.
- **`adult.data.csv`**: The dataset file containing demographic data.
- **`requirements.txt`**: A list of dependencies, mainly including Pandas.

## Getting Started

To run the project, use the following Replit environment:

[Run the Project on Replit](https://replit.com/@fxrdhan/Demographic-Data-Analyzer?v=1)

This Replit setup allows you to run the analysis and explore the answers directly in an online environment without the need for local setup.

## Dataset Source

Dua, D. and Graff, C. (2019). [UCI Machine Learning Repository](http://archive.ics.uci.edu/ml). Irvine, CA: University of California, School of Information and Computer Science.

## Important Note

THIS PROJECT IS A PERSONAL PROJECT CREATED FOR CERTIFICATION PURPOSES AND SHOULD NOT BE SHARED, FORKED, OR USED BY OTHERS. PLEASE RESPECT THE PRIVACY AND CONFIDENTIALITY OF THIS WORK.
