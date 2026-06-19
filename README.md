# Superstore EDA

Exploratory data analysis on the Sample Superstore Sales dataset (Kaggle).

## Objective
Identify the key drivers of profitability and understand why a growing business 
can still generate systematic losses.

## Dataset
9,994 orders across 4 years (2014–2017), 21 features including sales, profit, 
discount, category, region, and order date.

## Key Findings
1. Sales grew from ~$80k to ~$120k monthly peaks (2014–2017), but margin pressure 
   from discounting limits profit growth
2. Discounts above 30% generate negative average profit — a clear value 
   destruction threshold
3. Technology drives profitability ($145k total profit); Furniture contributes 
   only $18k despite 21% of order volume
4. Strong holiday seasonality (Nov–Dec peaks) with consistent January troughs

## Stack
Python · pandas · matplotlib · seaborn · Jupyter