# Tipping Behaviour Analysis

### STAT 301 - Linear Regression

University of British Columbia

---

## Overview

This project investigates tipping behavior using the Restaurant Tips dataset. The objective is to examine how various explanatory variables relate to tip amount using multiple linear regression techniques covered in STAT 301.

The analysis focuses on statistical inference, model interpretation, and regression diagnostics.

This was completed as a **group project** for STAT 301.

---

## Research Question

What factors are significantly associated with tip amount in restaurant transactions?

Specifically, we examine whether:

* Total bill amount influences tip amount
* Party size affects tipping behavior
* Gender or smoker status are associated with tipping differences
* Day of the week or meal time contribute to variation in tips

The response variable is **tip amount (continuous)**.

---

## Dataset

The dataset contains 244 restaurant transactions with the following variables:

* `total_bill` – total bill amount (USD)
* `tip` – tip amount (USD)
* `sex` – gender of payer
* `smoker` – smoker status
* `day` – day of the week
* `time` – meal time (Lunch/Dinner)
* `size` – party size

Source: Kaggle – Restaurant Tips Dataset

---

## Methods

A multiple linear regression model was fitted with tip as the response variable and a combination of numeric and categorical predictors.

Model form:

[
\text{tip} = \beta_0 + \beta_1(\text{bill}) + \beta_2(\text{party_size}) + \beta_3(\text{gender}) + \beta_4(\text{smoker}) + \epsilon
]

The analysis includes:

* Exploratory data visualization
* Model fitting and coefficient interpretation
* Assessment of statistical significance
* Discussion of model assumptions

---

## Key Findings

* **Total bill amount** is the strongest and most statistically significant predictor of tip amount.
* **Party size** shows a positive association with tip amount.
* Gender and smoker status were not statistically significant predictors after controlling for other variables.
* The model explains approximately 47% of the variability in tip amounts.

Overall, bill size is the primary driver of tipping behavior in this dataset.

---

## Repository Structure

```
data/              # Dataset
individual/        # Individual analysis components
report/            # Final report and notebook
README.md
```

---

## Group Members

Arnav Gupta
Thomas Hesselbo 
Gracie Shao
Frances Shen

Just tell me the tone you want.
