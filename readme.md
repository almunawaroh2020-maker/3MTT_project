# Marketing ROI Analysis Using Simple Linear Regression

## Project Overview

This project applies **Simple Linear Regression** to evaluate the relationship between marketing expenditure and sales. The objective is to identify the marketing channel (TV, Radio, or Social Media) with the strongest influence on sales and provide a data-driven recommendation for marketing budget allocation.

The analysis was conducted using Python and the `statsmodels` library, following a complete data science workflow that includes data cleaning, exploratory data analysis (EDA), model development, regression diagnostics, and business interpretation.

---

## Project Objectives

* Load and clean the marketing dataset.
* Perform exploratory data analysis (EDA).
* Examine relationships between marketing channels and sales.
* Identify the most suitable predictor variable using correlation analysis.
* Build a Simple Linear Regression model using Ordinary Least Squares (OLS).
* Validate regression assumptions using diagnostic plots and statistical tests.
* Interpret model outputs in a business context.
* Recommend the marketing channel with the highest expected return on investment (ROI).

---

## Dataset

The dataset contains the following variables:

| Variable     | Description                          |
| ------------ | ------------------------------------ |
| TV           | TV advertising expenditure           |
| Radio        | Radio advertising expenditure        |
| Social_Media | Social media advertising expenditure |
| Sales        | Product sales                        |

---

## Technologies Used

* ipywidgets
* io
* Python 3
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Statsmodels
* SciPy

---

## Project Workflow

1. Import required libraries.
2. Load the marketing dataset.
3. Inspect and clean the data.
4. Perform exploratory data analysis (EDA).
5. Generate correlation matrix and visualizations.
6. Select the independent variable with the strongest correlation.
7. Build a Simple Linear Regression model.
8. Evaluate model performance.
9. Validate regression assumptions using:

   * Linearity
   * Normality
   * Homoscedasticity
   * Independence of errors
10. Interpret findings and provide business recommendations.

---

## Regression Diagnostics

The following diagnostic techniques were used to evaluate the regression model:

* Residual Histogram
* Q-Q Plot
* Shapiro-Wilk Test
* Jarque-Bera Test
* Breusch-Pagan Test
* Durbin-Watson Statistic

These diagnostics confirmed that the regression assumptions were satisfied.

---

## Key Findings

* TV advertising demonstrated the strongest positive correlation with sales.
* The Simple Linear Regression model achieved an R² value of approximately **0.999**, indicating excellent predictive performance.
* TV advertising expenditure was found to have a statistically significant positive effect on sales (**p < 0.001**).
* Residual diagnostic tests indicated that the assumptions of linear regression were satisfied.

---

## Business Recommendation

Based on the statistical analysis, TV advertising is the most influential marketing channel in predicting sales. Organizations seeking to maximize marketing return on investment (ROI) should prioritize TV advertising expenditure, as it demonstrated the strongest relationship with sales and the highest predictive capability among the available marketing channels.

---

## Repository Structure

```text
marketing-roi-analysis/
│
├── regression_analysis.ipynb
├── marketing.csv
├── README.md
└── requirements.txt
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/marketing-roi-analysis.git
```

Navigate to the project folder:

```bash
cd marketing-roi-analysis
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

Or install them manually:

```bash
pip install pandas numpy matplotlib seaborn statsmodels scipy
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
regression_analysis.ipynb
```

---

## Future Improvements

Potential enhancements to this project include:

* Multiple Linear Regression using all marketing channels.
* Cross-validation for model evaluation.
* Feature engineering.
* Prediction on unseen data.
* Marketing budget optimization based on expected ROI.

---

## Author

**Moshood Abeeb/chatGPT**

---

## License

This project is part of 3MTT ML/AI cohort mini project.
