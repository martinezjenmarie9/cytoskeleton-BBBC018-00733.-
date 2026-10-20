## Overview
* **Purpose:** Contains the R script used to analyze the cell measurements obtained from Fiji.
* **Data Input:** Reads data/fiji_results.csv, which contains measurements of the five manually selected cells.
* **Data Validation:** Checks whether the required measurement columns are available and whether at least five valid cell measurements are present.
* **Statistical Summary:** Calculates the mean cell area, circularity, aspect ratio, and mean fluorescence intensity.
* **Data Export:** Saves the calculated summary statistics as results/cell_summary.csv.
* **Visualization:** Generates PNG figures showing the relationship between cell area and circularity and comparing mean fluorescence intensity among the measured cells.
* **Purpose in the Project:** Automates the analysis of cell morphology and fluorescence measurements using R, making the results easier to summarize, visualize, and document
