# carsDB-distribution-analysis
Exploratory data analysis and correlation study of the **carsDB dataset** using **R** and **ggplot2**.

## How to run
1. Open `notebooks/dist_analysis.Rmd` in RStudio.
2. Ensure `data/carsDB.csv` exists.
3. Knit to HTML or run chunks interactively.
4. Optional: Save plots to `results/` with ggsave().

## Key findings
- **wt vs disp:** strong positive correlation (~0.89).
- **wt vs mpg:** strong negative correlation (~-0.87).
- **wt vs hp:** moderate positive correlation (~0.66) with a few outliers.
