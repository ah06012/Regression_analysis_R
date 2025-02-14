# Short README

This repository demonstrates a simple linear regression workflow in R Markdown using population data:

1. **Setup**: Load required packages (`ggplot2`, `dplyr`, `broom`, `ggpubr`, `ggfortify`, `formattable`) in `Gousto.Rmd`.

2. **Data**: A CSV file (`population_data.csv`) with `Time` and `Population` columns is used. Modify file paths as needed.

3. **Analysis**:  
   - Fit a linear model (`lm(Population ~ Time)`).  
   - Evaluate model assumptions via diagnostic plots (e.g., residuals, Q-Q).  
   - Predict future values with confidence and prediction intervals.

4. **Usage**:  
   - Place `population_data.csv` in the same folder as `Gousto.Rmd`.  
   - Open `Gousto.Rmd` in RStudio and click *Knit* to generate HTML/Word/PDF output.

5. **Notes**:  
   - This example uses a simple linear model; check assumptions carefully.  
   - For more complex relationships, consider alternative approaches (polynomial terms, transformations, etc.).
