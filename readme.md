# An Empirical Validation of Cognitive Complexity as a Measure of Source Code Understandability
This repository contains the data used in and generated by our data analysis and literature search to ensure reproducibility, repeatability, and transparency.

## Data Analysis
The `data-analysis` folder contains all files that relate to the data analysis part of our work.
- The [dataset.xlsx](data-analysis/dataset.xlsx) file contains all the data we used to conduct our meta-analysis including the values for Cognitive Complexity and proxy variables for understandability of all code snippets.
- The [data-analysis.R](data-analysis/data-analysis.R) script contains the code written in R that was used to calculate the correlations, to test for the normality of the data and to generate the forest plots for our meta-analysis.
- The [dataset-descriptions.md](data-analysis/dataset-descriptions.md) document provides summaries of each of the studies and their corresponding datasets.

## Systematic Literature Search
The `systematic-literature-search` folder contains all files that relate to the systematic literature search part of our work.
- The [literature-search-overview.md](systematic-literature-search/literature-search-overview.md) document provides detailed instructions for each step and technical information about the tools that were used.
- The subfolders labeled with `1.1_...` to `6_...` correspond to the files generated by the corresponding step as described in the overview, such as a list of papers remaining after each step and raw export files from the search engines.