# statistical_analysis_project

# A/B Testing & Causal Inference Project

## Project Overview

This project demonstrates the design, implementation, and analysis of a web signup A/B experiment. The primary objective is to evaluate whether a new signup page design increases user conversions compared to the existing page.

## Dataset

* Simulated dataset of 10,000 users.
* Key columns:

  * `user_id`: Unique identifier for each user.
  * `group`: 'A' (control) or 'B' (treatment).
  * `converted`: Binary outcome indicating signup (1) or not (0).
  * `age`: User age.
  * `device`: Device type (Desktop, Mobile, Tablet).
  * `country`: Country of the user.

## Features

* Randomization check for covariate balance.
* Conversion rate calculation and treatment effect estimation.
* Hypothesis testing (z-test for proportions, logistic regression).
* Regression adjustment controlling for age, device, and country.
* Bootstrap for confidence intervals.
* Power analysis to determine minimum sample size and detectability.

## Tools & Libraries

* Python 3.x
* Pandas
* Numpy
* Matplotlib
* Seaborn
* Scipy
* Statsmodels




2. Install dependencies:

   ```
   pip install pandas numpy matplotlib seaborn scipy statsmodels
   ```
3. Open `ab_experiment_analysis.ipynb` in Jupyter Notebook or Google Colab.
4. Run all cells to reproduce the analysis and visualizations.

## Key Results

* Control conversion rate: 8.0%
* Treatment conversion rate: 9.2%
* Observed lift: +1.2 percentage points
* Statistically significant improvement (p < 0.05)
* Regression-adjusted odds ratio: 1.15 (95% CI: 1.02 - 1.29)

## Recommendations

* Implement the new signup page design.
* Monitor conversion metrics post-implementation.
* Conduct future A/B tests to optimize additional features.

## Author

* [Prateek Kudari]


## License

This project is licensed under the MIT License.
