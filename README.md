# Practical-Statistics-for-Data-Scientists

Code reproduction, chapter summaries, and theoretical explanations based on
*Practical Statistics for Data Scientists*, 2nd Edition by Peter Bruce,
Andrew Bruce, and Peter Gedeck.

## About This Repository

This repository contains Python/Jupyter Notebook implementations of the
statistical and data science concepts presented in the book.

Each chapter notebook contains:

- Reproduced Python code based on the examples in the book
- Summaries of the chapter and its major sections
- Theoretical explanations of the statistical concepts
- Outputs and visualizations where appropriate
- Short interpretations of the results

## Chapters

### Chapter 1 — Exploratory Data Analysis

Introduces methods for understanding and exploring datasets before applying
statistical or machine learning methods.

Topics include:

- Structured and rectangular data
- Data frames and indexes
- Estimates of location
- Mean, median, and robust estimates
- Estimates of variability
- Standard deviation and percentiles
- Boxplots, frequency tables, and histograms
- Density plots
- Binary and categorical data
- Probability and expected value
- Correlation and scatterplots
- Exploring relationships between multiple variables
- Hexagonal binning, contours, and multivariable visualization

### Chapter 2 — Data and Sampling Distributions

Introduces sampling and probability distributions and explains how samples
can be used to understand populations.

Topics include:

- Random sampling and sample bias
- Sample size and sample quality
- Sample means and population means
- Selection bias and regression to the mean
- Sampling distributions
- Central Limit Theorem
- Standard error
- Bootstrap resampling
- Confidence intervals
- Normal and standard normal distributions
- QQ plots
- Long-tailed distributions
- Student's t-distribution
- Binomial distribution
- Chi-square distribution
- F-distribution
- Poisson, exponential, and Weibull distributions

### Chapter 3 — Statistical Experiments and Significance Testing

Covers statistical experiments and methods for determining whether observed
differences provide evidence against a null hypothesis.

Topics include:

- A/B testing
- Control groups
- Hypothesis testing
- Null and alternative hypotheses
- Permutation tests
- Statistical significance and p-values
- Alpha
- Type I and Type II errors
- t-tests
- Multiple testing
- Degrees of freedom
- ANOVA
- Two-way ANOVA
- Chi-square tests
- Fisher's exact test
- Multi-arm bandit algorithms
- Statistical power
- Sample size

### Chapter 4 — Regression and Prediction

Introduces regression models for explaining relationships between variables
and making predictions.

Topics include:

- Simple linear regression
- Fitted values and residuals
- Least squares
- Prediction and explanation
- Multiple regression
- Model assessment
- Cross-validation
- Model selection
- Weighted regression
- Factor variables
- Correlated predictors and multicollinearity
- Interactions and main effects
- Regression diagnostics
- Outliers and influential observations
- Heteroskedasticity and non-normality
- Polynomial regression
- Splines
- Generalized Additive Models (GAM)

## Repository Structure

```text
Practical-Statistics-for-Data-Scientists/
├── Chapter-01-Exploratory-Data-Analysis/
│   └── Chapter-01-revised.ipynb
├── Chapter-02-Data-and-Sampling-Distributions/
│   └── Chapter-02.ipynb
├── Chapter-03-Statistical-Experiments-and-Significance-Testing/
│   └── Chapter-03.ipynb
├── Chapter-04-Regression-and-Prediction/
│   └── Chapter-04.ipynb
├── data/
├── requirements.txt
├── .gitignore
└── README.md