# Laryngectomy-Analysis

This project presents a reproducible clinical data analysis examining postoperative outcomes among patients undergoing laryngectomy. Using data from the Open.Visualization.Academy R package, the analysis focuses on the relationship between postoperative complications and hospital length of stay.
The workflow was implemented in R using Quarto and structured as an academic-style report with clearly defined Methods, Results, and Discussion sections. Multiple data quality checks were performed to identify and exclude records with missing or inconsistent follow-up, recurrence, or mortality information. An analysis dataset was constructed after filtering problematic records and deriving new variables, including a cumulative complication count and an estimated hospital stay duration.
Exploratory visualizations were used to evaluate patterns between complications and hospital stay, including scatterplots with trend lines, transparency-adjusted plots to address overplotting, sunflower plots for repeated observations, and categorical comparisons using boxplots and violin plots. All figures were produced with consistent styling, descriptive captions, and cross-references to support interpretation.
This project emphasizes reproducible research practices, data validation, clear statistical visualization, and professional scientific reporting, reflecting workflows commonly used in clinical research and health policy analysis.
Tools & Methods
R, Quarto
tidyverse (dplyr, ggplot2)
Reproducible reporting with inline statistical results

Biostatistics Final Project (R + Quarto)

This repository section contains my Final Project for graduate-level Statistical Computing / Biostatistics coursework. The project is a cleaned, reproducible version of my R Assignment 3 work, organized as two Quarto reports using separate datasets:

    CTN-0094 report (clinical trial / demographics + modeling + visualization)
    Laryngectomy report (data quality issue identification + reporting + graphics)

What this demonstrates

    Reports render cleanly with no errors/warnings and no stray/unformatted output
    Code follows tidyverse style and is formatted consistently
    Key results (counts, p-values, etc.) are inserted using inline R code (no hard-coded values)
    Figures are publication-ready with clear who/when/what labels and at least one faceted plot (CTN)
    Methods sections document R version and package versions
    Uses tables appropriate for reporting (e.g., gtsummary demographics table for CTN)

Files

    ctn_report.qmd → rendered output: ctn_report.html
    laryngectomy_report.qmd → rendered output: laryngectomy_report.html

Notes
This project is shared as a portfolio example of reproducible reporting, applied statistical computing, and public-health oriented data analysis in R/Quarto.

