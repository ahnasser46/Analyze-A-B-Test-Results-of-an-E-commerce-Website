# Analyze A/B Test Results

This project is part of the Advanced Data Analysis Nanodegree by Udacity. This project analyzes an A/B test run by an e-commerce website to decide whether to implement a new page or keep the old one.

## Contents
- Introduction
- Probability
- A/B Test
- Regression
- Conclusion

## Introduction
A/B tests compare two versions of a webpage to determine which performs better. This project aims to analyze the results and make recommendations.

## Probability
- Import libraries and load `ab_data.csv`.
- Calculate statistics: number of rows, unique users, conversion rates, and mismatches.
- Handle missing values and duplicates.

## A/B Test
- Formulate hypotheses.
- Perform sampling distribution and simulate conversion rates.
- Calculate p-value and interpret results.

## Regression
- Use logistic regression to predict conversion based on the page.
- Add country as a factor and analyze interactions.

## Conclusion
No significant evidence that the new page leads to more conversions. Further analysis may be needed.

## How to Run
1. Clone the repository.
2. Install necessary libraries (`pandas`, `numpy`, `matplotlib`, `statsmodels`).
3. Run the Jupyter notebook.

## Files
- `Analyze_ab_test_results_notebook.ipynb`: Analysis notebook.
- `ab_data.csv`: Dataset.
- `countries.csv`: User country data.

## License
Licensed under the MIT License.
