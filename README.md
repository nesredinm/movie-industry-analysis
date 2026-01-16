# Movie Industry Analysis

## Overview
This project explores factors that influence a movie’s revenue, such as budget, audience engagement, production company, and release year. The goal is to understand which variables matter most and how they relate to revenue.

## Hypotheses
- Movies with higher budgets tend to generate higher revenue.
- Movies with higher audience engagement (vote count) tend to earn more.
- Production company influences revenue outcomes.
- Release year affects revenue due to overall industry growth.

## Data
The dataset was sourced from Kaggle Movie Dataset.
Some values for budget, revenue, rating, company, and runtime are missing, mainly because this information is not always publicly available.

## Methodology
- Exploratory Data Analysis (EDA)
- Correlation analysis for numeric features
- Log transformation for highly skewed financial variables
- Categorical analysis for production companies

## Key Findings
- Budget is the strongest factor associated with revenue.
- Audience engagement (vote count) is the second strongest factor.
- Production company provides additional context but should be considered alongside budget.
- Release year shows a general upward trend in revenue.

## Conclusion
Budget and audience engagement are the main drivers of movie revenue, while company and year provide supporting context.

## Tools & Technologies
Python, Pandas, NumPy, Matplotlib, Seaborn