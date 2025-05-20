# GWAS--Rheumatoid-Arthritis-

📝 Project Overview

This project involves exploring and analyzing Genome-Wide Association Study (GWAS) summary statistics. Specifically, this notebook works with data from a study on Rheumatoid Arthritis (RA). The analysis includes reading the summary statistics, visualizing p-values (e.g., histograms, Manhattan plots), and identifying significant genomic regions associated with RA.

The primary goal is to understand how to handle and interpret GWAS summary statistics, a common data type in bioinformatics.

## 📁 Files in this Repository

* **`BGGN239_mcvicker_notebook1.Rmd`**: The R Markdown file containing the source code, narrative, and analysis steps for exploring the RA GWAS data.
* **`BGGN239_mcvicker_notebook1.nb.html`**: The rendered HTML version of the R Markdown notebook, providing a viewable report of the analysis.
* **`RA_GWAS.txt`**: A text file containing the GWAS summary statistics for Rheumatoid Arthritis used in the notebook. (Note: These data appear to be thinned for class purposes, with original data from Okada et al., Nature 2014).

## 🛠️ Tools & Technologies

* **R:** For statistical analysis and scripting.
* **R Markdown:** For creating reproducible notebooks combining code, output, and narrative.
* **Key R functions/packages used include:** `read.table()`, `head()`, `nrow()`, `hist()`, `plot()`, basic data subsetting and manipulation.

## 🚀 How to Run/Use

1.  **Prerequisites:**
    * An R environment with R Markdown support (e.g., RStudio).
2.  **To view the analysis:**
    * Open `BGGN239_mcvicker_notebook1.nb.html` in a web browser.
3.  **To run the analysis:**
    * Open `BGGN239_mcvicker_notebook1.Rmd` in RStudio.
    * Ensure the data file `RA_GWAS.txt` is in the same directory as the Rmd file, or update the file path within the script.
    * Run the R code chunks sequentially within the Rmd file.

## ✨ Key Concepts Demonstrated

* Reading and performing initial exploratory data analysis (EDA) on GWAS summary statistics.
* Generating histograms of p-values to observe distribution.
* Creating Manhattan plots to visualize genome-wide association signals.
* Identifying and zooming into regions with highly significant p-values.
